## 💻 YouTube Clone (Layout com CSS Grid)

Este projeto é um clone do layout da página principal do YouTube, focado em utilizar o **CSS Grid** para criar uma estrutura moderna e responsiva. O objetivo principal é demonstrar a aplicação de técnicas de layout avançadas para recriar a interface familiar de uma das maiores plataformas de vídeo do mundo.

![Visão geral do layout do YouTube Clone implementado com CSS Grid]('assets/images/screenshot.png')

---

### ✨ Recursos e Foco

* **Estrutura Principal com CSS Grid:** Uso de `grid-template-rows`, `grid-template-columns` e `grid-template-areas` no `body` para definir o layout do cabeçalho, barra lateral e conteúdo principal.
* **Grid de Vídeos Responsivo:** O contêiner de vídeos (`.main-content`) utiliza `grid-template-columns: repeat(auto-fit, minmax(280px, 1fr))` para garantir que o layout se ajuste dinamicamente à largura da tela.
* **Componentes Fixos/Sticky:** Aplicação de `position: sticky` no `header` e `aside` para que o cabeçalho e a barra lateral permaneçam visíveis durante a rolagem do conteúdo.
* **Limitação de Texto (`-line-clamp`):** O título do vídeo é limitado a 2 linhas, replicando o comportamento visual do YouTube.
* **Efeitos de Interação (Hover):** Transições e efeitos de escala (`transform: scale`) nos vídeos para uma melhor experiência do usuário.

---

### 🛠️ Tecnologias Utilizadas

| Tecnologia | Descrição |
| :--- | :--- |
| **HTML5** | Estrutura semântica do projeto. |
| **CSS3** | Estilização, com foco em **CSS Grid** para o layout principal e responsividade. |
| **Google Fonts (Roboto)** | Tipografia padrão do YouTube. |

---

### 📂 Estrutura de Arquivos

```
youtube-clone/
├── assets/
│   ├── css/
│   │   └── style.css       # Folha de estilos principal
│   └── images/             # Diretório com todos os ícones e imagens
├── index.html              # Arquivo principal (a marcação HTML)
└── README.md               # Este arquivo
---

### Projeto Feito Para o Curso de Formação CSS Web Developer da DIO.

