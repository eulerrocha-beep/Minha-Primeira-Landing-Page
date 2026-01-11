# 🎨 Landing Page - Trilha de CSS da DIO

> Uma colaboração para construir uma Landing Page profissional e responsiva da Trilha de CSS da DIO

## ℹ️ Sobre o Projeto

Este projeto é uma Landing Page moderna criada para apresentar a Trilha de CSS da DIO. A página foi originalmente desenvolvida como um desafio da plataforma DIO, e foi completamente revisada para garantir responsividade em todos os dispositivos, incluindo suporte otimizado para iOS e dispositivos móveis pequenos.

### ✨ Características

- ✅ **100% Responsivo** - Funciona perfeitamente em celulares, tablets e desktops
- ✅ **Otimizado para iOS** - Suporte completo para Safari e navegadores móveis
- ✅ **Design Moderno** - Gradientes, efeitos e animações suaves
- ✅ **Performance** - Imagens otimizadas com lazy loading
- ✅ **Acessibilidade** - Semântica HTML correta e suporte a múltiplos navegadores

## 👨‍💻 Créditos

- **HTML e Estrutura**: Original da trilha DIO
- **CSS Responsivo e Otimizações**: Desenvolvido e mantido por Euler Rocha (eulerrocha-beep)
  - Responsividade mobile-first
  - Compatibilidade com iOS 9+
  - Media queries para todos os tamanhos de tela
  - Otimizações de performance e acessibilidade

## 🚀 Como Rodar Localmente

### Pré-requisitos

- Nenhum! Este é um projeto estático puro (HTML + CSS)
- Um navegador moderno (Chrome, Firefox, Safari, Edge)

### Instalação

1. **Clone o repositório:**
```bash
git clone https://github.com/eulerrocha-beep/Minha-Primeira-Landing-Page.git
cd Minha-Primeira-Landing-Page
```

2. **Abra o arquivo `index.html`:**

#### Opção 1: Abrir no Navegador Diretamente
- Abra o explorador de arquivos
- Navegue até a pasta do projeto
- Clique duas vezes em `index.html`

#### Opção 2: Usando um Servidor Local (Recomendado)

**Com Python 3:**
```bash
python -m http.server 8000
```
Acesse: `http://localhost:8000`

**Com Python 2:**
```bash
python -m SimpleHTTPServer 8000
```
Acesse: `http://localhost:8000`

**Com Node.js (http-server):**
```bash
npm install -g http-server
http-server
```
Acesse: `http://localhost:8080`

**Com Live Server (VS Code):**
- Instale a extensão "Live Server"
- Clique com botão direito em `index.html`
- Selecione "Open with Live Server"

## 📱 Responsividade

O projeto foi otimizado para os seguintes breakpoints:

| Dispositivo | Resolução | Status |
|-------------|-----------|--------|
| Celular Extra Pequeno | 320px | ✅ Otimizado |
| Celular Pequeno | 480px | ✅ Otimizado |
| Tablet | 768px | ✅ Otimizado |
| Desktop | 1024px+ | ✅ Otimizado |
| Landscape | Altura < 600px | ✅ Otimizado |

### Testado em:

- ✅ iPhone (iOS 9+)
- ✅ Android (Chrome, Firefox, Samsung Internet)
- ✅ iPad e Tablets
- ✅ Navegadores Desktop (Chrome, Firefox, Safari, Edge)

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura semântica
- **CSS3** - Estilos avançados:
  - Flexbox
  - CSS Grid (pronto para uso)
  - Media Queries
  - Gradientes Lineares
  - Animações e Transições
  - CSS Clamp para tipografia fluida
  - Backdrop Filter (com fallback)

## 📝 Estrutura do Projeto

```
Minha-Primeira-Landing-Page/
├── index.html                 # Arquivo HTML principal
├── style.css                  # Estilos CSS (Responsivo)
├── README.md                  # Este arquivo
└── assets/
    └── images/
        ├── banner.png         # Banner principal
        ├── logo.png           # Logo da DIO
        ├── woman-code.png     # Imagem seção transform world
        └── dio-logo.png       # Logo rodapé
```

## 🎯 Funcionalidades do CSS

### Responsividade Mobile-First
- Valores fluidos com `clamp()`
- Padding e margins adaptativos
- Fontes escaláveis
- Imagens responsivas

### Compatibilidade iOS
- Meta tag `viewport-fit=cover` para notch
- Prefixos `-webkit-` para propriedades CSS
- Touch feedback otimizado
- Suporte a Safe Area Insets

### Otimizações
- Lazy loading de imagens
- `will-change` para animações suaves
- Transições CSS para melhor performance
- Backdrop filter com fallback

## 🔗 Links Úteis

- [DIO - Digital Innovation One](https://dio.me)
- [Figma do Desafio](https://www.figma.com/file/3PiokoJj9IhGDnNiWAJbz7/DIO---Desafio-01?node-id=2%3A6)
- [MDN - CSS Responsivo](https://developer.mozilla.org/pt-BR/docs/Learn/CSS/CSS_layout/Responsive_Design)
- [Can I Use - Browser Support](https://caniuse.com/)

## 📄 Licença

Este projeto é fornecido como está para fins educacionais.

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se livre para:
- Reportar bugs
- Sugerir melhorias
- Enviar pull requests

---

**Desenvolvido com ❤️ por Euler Rocha**
