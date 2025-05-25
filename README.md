# 🎥 YouTube Grid Layout - Desafio CSS

Uma página estática inspirada no YouTube, construída com **HTML5** e **CSS3** (Grid Layout e Flexbox), que exibe um grid de vídeos com sidebar de navegação responsiva.

---

## 📌 Descrição

Este projeto tem como objetivo praticar os conceitos de CSS Grid e Flexbox ao recriar um layout de listagem de vídeos ao estilo YouTube:

- Barra lateral fixa com itens de navegação e ícones.
- Cabeçalho com logo e campo de busca.
- Grid responsivo de cartões de vídeo (miniaturas, avatar do canal, título e meta informações).
- Mobile-first: adaptação para dispositivos menores via media queries.

## ✨ Funcionalidades

- Layout em grade dinâmico usando `grid-template-columns: repeat(auto-fit, minmax(...))`.
- Sidebar responsiva com `display: flex` e `align-items: center` para ícones alinhados.
- Cartões de vídeo com efeito hover e transição suave.
- Estrutura de pastas organizada para HTML, CSS, ícones e imagens.

---

## 📁 Estrutura de Pastas

```
desafio-2-grid/
├── index.html          # Página principal
├── README.md           # Documentação do projeto
└── src/
    ├── styles/
    │   └── style.css   # Estilos gerais e layout
    ├── icons/          # Ícones da sidebar
    │   ├── home.png
    │   ├── compass.png
    │   └── ...
    └── images/         # Miniaturas e avatar do canal
        ├── image 1.png
        ├── Channel Avatar.png
        └── ...
```

---

## 🛠️ Tecnologias

- HTML5
- CSS3 (Grid Layout, Flexbox, Media Queries)
- Google Fonts: [Roboto](https://fonts.google.com/specimen/Roboto)

---

## 📥 Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/desafio-2-grid.git
   ```
2. Abra o arquivo `index.html` no seu navegador preferido.

---

## 🎨 Personalização

- Altere cores e fontes em `src/styles/style.css`.
- Substitua miniaturas em `src/images/` e ícones em `src/icons/`.
- Ajuste o número de colunas ou gaps do grid conforme necessidade.

---

## 📄 Licença

Este projeto está disponível sob a licença [MIT](LICENSE).

---

## 🤝 Contribuição

Contribuições são bem-vindas! Abra uma issue ou envie um pull request para sugestões, correções ou melhorias.

---

## 📫 Contato

- LinkedIn: https://www.linkedin.com/in/joannabraccini

---

<p align="center">Desenvolvido com ❤️ por Joanna</p>
