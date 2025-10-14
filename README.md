# Portfolio — Guilherme Oliveira

Visualize o portfolio online: https://gaog-dev.github.io/Portfolio/

Descrição
- Página pessoal com foco em apresentação de projetos, habilidades e contato.
- Layout responsivo com animações, ring LED no hero, efeitos de partículas, cursor personalizado e modais de projeto.

Funcionalidades principais
- Hero com foto em anel circular animado (LED giratório).
- Títulos das seções (Sobre, Habilidades, Projetos, Contato).
- Cards de projetos com overlay e botão que abre modal com detalhes (permanece na mesma página).
- Animações AOS, partículas de fundo e typing effect no subtítulo.
- Cursor e follower customizados.
- Formulário de contato com feedback visual.
- Compatível com desktop e mobile.

Como rodar localmente
1. Clone ou copie os arquivos para uma pasta local.
2. Abra `portfolio.html` diretamente no navegador ou use um servidor simples:
   - Python 3: `python -m http.server 8000` (na pasta do projeto) e acesse http://localhost:8000
   - VS Code: abra a pasta e use Live Server.

Estrutura (resumo)
- portfolio.html — página principal
- assets/ — imagens e recursos estáticos
- (CSS e scripts estão embedados em portfolio.html)

Customizações rápidas
- Alterar foto: substituir `assets/profile.png`.
- Ajustar projetos: editar blocos em `#projects` ou usar modais existentes.
- Cores/gradientes: variáveis CSS em :root no topo do arquivo.

Contato
- Email: gaoliveira2077@gmail.com

Licença
- Conteúdo do portfolio é de uso pessoal. Ajuste conforme necessário.
