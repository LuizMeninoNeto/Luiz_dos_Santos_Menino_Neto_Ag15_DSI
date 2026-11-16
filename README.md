# Portfólio Profissional - Desenvolvimento Web

**Nome do aluno:** Luiz dos Santos Menino Neto

## Descrição do Portfólio
Este projeto é um portfólio pessoal e profissional desenvolvido para apresentar minhas formações, projetos acadêmicos e técnicos na área de Engenharia de Controle e Automação e Desenvolvimento de Sistemas. O site serve como um cartão de visitas digital interativo e responsivo.

## Tecnologias Utilizadas
- HTML5
- CSS3
- Bootstrap 5
- FontAwesome (Ícones)
- GitHub Pages (Hospedagem)

## Link do Site Publicado
[🔗 Acessar Portfólio no GitHub Pages](https://SEU_USUARIO.github.io/NOME_DO_REPOSITORIO/) *(Lembre-se de substituir pelo seu link real após a publicação)*

## Explicação do Funcionamento do Projeto
O site é uma *Single Page Application* (SPA) estática. Ele possui um menu de navegação superior fixo que permite a rolagem suave até as seções específicas:
1. **Perfil:** Apresentação inicial e resumo das qualificações.
2. **Habilidades:** Seção de destaque técnico.
3. **Projetos:** Exposição de projetos desenvolvidos (ex: Estação de Solda Inteligente, Automações Google Workspace), dispostos em um sistema de *cards* em grade.
4. **Contato:** Formulário de comunicação e links para redes profissionais.
A responsividade (adaptação para celulares e tablets) é garantida inteiramente pelo sistema de *grid* do Bootstrap.

## Descrição do Recurso Novo Adicionado
Para ir além do modelo base da aula, foram implementados dois recursos novos:
1. **Nova Seção de "Habilidades":** Uma área dedicada ao mapeamento das *hard skills*.
2. **Animações e Efeitos Visuais (Hover e Smooth Scroll):** Efeitos de interatividade onde os cards de projetos e as caixas de habilidades se movem e ganham sombra ao passar o mouse.

## Explicação de Como Esse Recurso Foi Implementado
- **A nova seção** foi construída no arquivo HTML (`<section id="habilidades">`) aproveitando o grid do Bootstrap (`row`, `col-md-4`) para garantir o alinhamento lado a lado no desktop e empilhado no mobile. Ícones vetoriais via *FontAwesome* foram integrados para ilustrar cada habilidade.
- **As animações (*Hover*)** foram feitas utilizando CSS puro no arquivo `style.css`. Foi aplicada a propriedade `transition: transform 0.3s ease` na classe base dos elementos (`.project-card` e `.skill-box`). Na pseudo-classe `:hover`, a propriedade `transform: translateY(-10px)` (ou `scale`) foi acionada para criar o efeito de "levitação" dos cards ao interagir com o cursor do usuário, melhorando a experiência de interface (UI).
