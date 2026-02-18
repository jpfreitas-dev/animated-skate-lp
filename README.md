# 🛹 Snitap Patins - Animated Landing Page


[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://html.spec.whatwg.org/)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://www.w3.org/Style/CSS/)

Uma landing page moderna e altamente animada para a marca fictícia **Snitap Patins**, desenvolvida com HTML5 e CSS3 puro, sem dependências externas.


---


## 🎯 Seções Implementadas

#### 1. **Navegação (Header)**
- Logo da marca com link para home
- Ícone de carrinho de compras com badge de quantidade
- Design minimalista e intuitivo

#### 2. **Hero Section**
- Título principal com animação de texto rotativo
- Alternância dinâmica de conceitos-chave: "radical", "divertida", "saudável"
- Dois botões de call-to-action:
  - "Comprar Agora" com ícone de sacola
  - "Veja em Ação" com ícone de play
- Imagem de patins com elementos decorativos animados (elipse, estrelas)

#### 3. **Banner Animado**
- Scroll infinito contínuo com gradiente animado de fundo
- Replicação automática de imagens para efeito perfeito de loop
- Sem JavaScript - totalmente baseado em CSS

#### 4. **Galeria de Fotos**
- Grid responsivo com imagens de usuários
- Cards com efeito de stagger animation
- Informações do usuário com avatar e handle das redes sociais
- Atributo `data-delay` para animações sincronizadas

#### 5. **Footer**
- Logo e nome da marca
- Links de navegação (Sobre, Lojas, Política de Privacidade)
- Links de redes sociais (Instagram, Facebook, YouTube, TikTok)
- Layout flexível e responsivo

---

## 🛠 Tecnologias Utilizadas
- **HTML5**: Estrutura semântica
- **CSS3**: Estilização e animações 

### Fontes Utilizadas

- **Montserrat** (peso 500) - Corpo do texto
- **Syne** (peso 700) - Títulos e headings
- **Inter** (peso 500) - Suporte adicional

---

## 📁 Estrutura do Projeto

```
animated-skate-lp/
├── 📄 index.html                 # Arquivo principal HTML
├── 📄 README.md                  # Este arquivo
├── 📁 styles/
│   ├── index.css                 # Importa todos os estilos
│   ├── global.css                # Variáveis e reset global
│   ├── nav.css                   # Estilos da navegação
│   ├── hero.css                  # Hero section com animações
│   ├── banner.css                # Banner animado
│   ├── gallery.css               # Galeria responsiva
│   └── footer.css                # Rodapé
└── 📁 assets/
    ├── logo.svg                  # Logo da marca
    ├── banner.svg                # Elemento para banner
    ├── 📁 hero/
    │   ├── ellipse.svg           # Elemento decorativo
    │   ├── patins-image.png      # Imagem principal
    │   ├── stars-1.svg           # Animação de estrelas
    │   └── stars-2.svg           # Animação de estrelas
    ├── 📁 icons/
    │   ├── shopping-bag.svg      # Ícone de carrinho
    │   ├── play.svg              # Ícone de play
    │   ├── instagram.svg         # Ícone Instagram
    │   ├── facebook.svg          # Ícone Facebook
    │   ├── youtube.svg           # Ícone YouTube
    │   └── tiktok.svg            # Ícone TikTok
    └── 📁 images/
        ├── 01.png                # Foto da galeria
        ├── 02.png                # Foto da galeria
        ├── 03.png                # Foto da galeria
        ├── 04.png                # Foto da galeria
        └── person.png            # Avatar de usuário
```

### Estrutura das Cores

O projeto utiliza um design system de cores definido em `global.css`:

```css
:root {
  --snitap-sun: #ffcd1e;        /* Amarelo - destaque */
  --snitap-sky-mid: #06b6d4;    /* Azul cyan - primário */
  --snitap-sky-light: #67e8f9;  /* Azul claro - secundário */
  --snitap-joy-mid: #db2777;    /* Rosa/Magenta - destaque */
  --snitap-joy-light: #f472b6;  /* Rosa claro */
  --snitap-leaf-mid: #16a34a;   /* Verde - complementar */
}
```

---

## Animações CSS Implementadas

### ✨ Rotação de Texto (Hero)
```css
animation: text-rotation 6s steps(4, end) infinite;
```
Alterna entre múltiplos textos na hero section criando impacto visual.

### Scroll Infinito (Banner)
```css
animation: rolling 20s linear infinite;
```
Cria efeito de fita rolante contínua com imagens.

### Gradiente Animado (Banner)
Fundo com gradiente que se move continuamente na seção banner.

### Stagger Animation (Galeria)
As imagens aparecem com delay progressivo para criar efeito cascata.



