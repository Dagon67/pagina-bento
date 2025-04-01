# Página Bento

Uma landing page moderna e responsiva construída com HTML5, SCSS e JavaScript puro. O projeto utiliza as melhores práticas de desenvolvimento web e oferece uma experiência de usuário fluida e agradável.

## Características

- Design moderno e minimalista
- Totalmente responsivo (mobile-first)
- Animações suaves e otimizadas
- Performance otimizada
- SEO-friendly
- Acessibilidade implementada
- Código limpo e bem documentado
- Zero dependências externas (exceto Font Awesome)

## Tecnologias Utilizadas

- HTML5 semântico
- SCSS (com arquitetura modular)
  - Variáveis
  - Mixins
  - Funções
  - Aninhamento
  - Partials
- JavaScript ES6+
  - Modules
  - Intersection Observer
  - Animações otimizadas
  - Event handling
- Font Awesome 6.0.0
- Google Fonts (Inter)

## Estrutura do Projeto

```
pagina-bento/
├── index.html
├── css/
│   ├── style.css
│   └── animations.css
├── scss/
│   ├── style.scss
│   ├── _variables.scss
│   ├── _mixins.scss
│   └── animations.scss
├── js/
│   ├── main.js
│   └── animations.js
├── img/
│   ├── logo.svg
│   ├── hero.svg
│   └── about.svg
└── README.md
```

## Seções da Página

1. **Header**
   - Logo responsivo
   - Menu de navegação
   - Botão CTA
   - Menu mobile otimizado

2. **Hero Section**
   - Título principal com animação
   - Subtítulo descritivo
   - Botão CTA principal
   - Imagem ilustrativa

3. **Recursos**
   - Cards animados
   - Ícones interativos
   - Descrições claras
   - Layout em grid responsivo

4. **Sobre**
   - Texto informativo
   - Imagem complementar
   - Layout flexível

5. **Contato**
   - Formulário validado
   - Feedback visual
   - Mensagens de erro/sucesso
   - Proteção contra spam

6. **Footer**
   - Links úteis
   - Redes sociais
   - Informações legais
   - Layout responsivo

## Recursos Técnicos

### Performance
- Lazy loading de imagens
- CSS minificado e otimizado
- JavaScript modular
- Imagens otimizadas (SVG/WebP)
- Fontes com preload
- Cache eficiente
- Gzip habilitado

### Acessibilidade
- HTML semântico
- ARIA labels
- Contraste adequado
- Navegação por teclado
- Textos alternativos
- Focus visible

### SEO
- Meta tags otimizadas
- Open Graph tags
- Schema.org markup
- Sitemap XML
- Robots.txt
- URLs amigáveis

### Animações
- Scroll-based
- Hover effects
- Transições suaves
- Loading states
- Feedback visual
- Performance otimizada

## Instalação

1. Clone o repositório:
```bash
git clone https://github.com/Dagon67/pagina-bento.git
cd pagina-bento
```

2. Para desenvolvimento com SCSS:
```bash
# Instalar Sass globalmente
npm install -g sass

# Compilar SCSS
sass scss/style.scss css/style.css --watch
sass scss/animations.scss css/animations.css --watch
```

3. Servidor local (opcional):
```bash
# Usando Python
python -m http.server 8000

# Ou usando Node.js
npx serve
```

## Personalização

### Cores
```scss
// Em scss/_variables.scss
$primary-color: #4A90E2;
$secondary-color: #2C3E50;
$accent-color: #E74C3C;
```

### Fontes
```scss
// Em scss/style.scss
$font-primary: 'Inter', sans-serif;
$font-secondary: 'Arial', sans-serif;
```

### Breakpoints
```scss
// Em scss/_variables.scss
$mobile: 576px;
$tablet: 768px;
$desktop: 1024px;
```

## Boas Práticas

1. **HTML**
   - Semântica correta
   - Acessibilidade
   - Validação W3C
   - Estrutura lógica

2. **CSS/SCSS**
   - BEM methodology
   - Mobile-first
   - Reutilização
   - Variáveis
   - Modularização

3. **JavaScript**
   - ES6+ features
   - Event delegation
   - Error handling
   - Performance
   - Clean code

## Contribuindo

1. Fork o projeto
2. Crie sua Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a Branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request



## Contato

[@Dagon67](https://github.com/Dagon67)

Link do Projeto: [https://github.com/Dagon67/pagina-bento](https://github.com/Dagon67/pagina-bento)
