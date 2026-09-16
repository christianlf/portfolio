# 🌐 Portfolio Pessoal - Christian Lindoso Froz

Portfolio web moderno e responsivo desenvolvido com HTML5, CSS3 e JavaScript puro.

![Portfolio Preview](https://img.shields.io/badge/Status-Online-success)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## ✨ Características

### Design Moderno
- 🎨 **Gradient Tech Theme** - Paleta de cores moderna com gradientes vibrantes
- 🌓 **Dark Mode** - Interface escura profissional
- 📱 **Totalmente Responsivo** - Funciona perfeitamente em mobile, tablet e desktop
- ⚡ **Animações Suaves** - Transições e efeitos visuais fluidos
- 🎭 **Efeitos Interativos** - Hover effects, parallax, typing animation

### Seções

1. **Hero** - Apresentação impactante com animação de digitação
2. **Sobre Mim** - Biografia, localização e estatísticas
3. **Projetos** - Grid com 3 projetos em destaque
4. **Habilidades** - Categorias de skills técnicas
5. **Contato** - Links para GitHub, LinkedIn e email

### Funcionalidades JavaScript

- ✅ Menu mobile funcional
- ✅ Scroll suave entre seções
- ✅ Animação de digitação no título
- ✅ Scroll reveal para elementos
- ✅ Efeito parallax no hero
- ✅ Contador animado nas estatísticas
- ✅ Efeito tilt nos cards de projeto
- ✅ Active state na navbar ao scrollar
- ✅ Easter egg (Konami Code 🎮)

## 🚀 Como Usar

### Visualização Local

1. **Clone ou baixe os arquivos:**
   ```bash
   # Estrutura de arquivos:
   portfolio/
   ├── index.html
   ├── style.css
   ├── script.js
   └── README.md
   ```

2. **Abra o `index.html` no navegador:**
   - Duplo clique no arquivo
   - Ou arraste para o navegador
   - Ou use Live Server no VS Code

### Deploy no GitHub Pages

1. **Crie um repositório no GitHub:**
   ```bash
   # Exemplo de nome: portfolio
   # Deixe como público
   ```

2. **Faça upload dos arquivos:**
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Portfolio website"
   git branch -M main
   git remote add origin https://github.com/SEU_USUARIO/portfolio.git
   git push -u origin main
   ```

3. **Ative o GitHub Pages:**
   - Vá em **Settings** > **Pages**
   - Source: **Deploy from a branch**
   - Branch: **main** / **root**
   - Clique em **Save**

4. **Seu site estará disponível em:**
   ```
   https://SEU_USUARIO.github.io/portfolio/
   ```

### Deploy Alternativo (Netlify/Vercel)

**Netlify:**
1. Acesse [netlify.com](https://netlify.com)
2. Arraste a pasta do portfolio
3. Site publicado automaticamente!

**Vercel:**
1. Acesse [vercel.com](https://vercel.com)
2. Import repository do GitHub
3. Deploy automático!

## 🎨 Personalização

### Cores

Edite as variáveis CSS em `style.css` (linhas 10-30):

```css
:root {
    --primary: #6366f1;           /* Azul principal */
    --secondary: #0ea5e9;         /* Azul secundário */
    --accent: #8b5cf6;            /* Roxo accent */
    
    /* Ou use outros gradientes: */
    --gradient-primary: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}
```

**Paletas recomendadas:**

**Tech Blue (atual):**
```css
--primary: #6366f1;
--secondary: #0ea5e9;
```

**Neon Green:**
```css
--primary: #10b981;
--secondary: #14b8a6;
```

**Sunset Orange:**
```css
--primary: #f59e0b;
--secondary: #ef4444;
```

**Purple Dream:**
```css
--primary: #a855f7;
--secondary: #ec4899;
```

### Conteúdo

**Trocar informações pessoais** (em `index.html`):

1. **Nome e título** (linha ~40):
   ```html
   <h1 class="hero-name">Seu Nome Aqui</h1>
   <p class="hero-title">Seu Cargo</p>
   ```

2. **Links sociais** (linha ~60):
   ```html
   <a href="SEU_GITHUB_URL">...</a>
   <a href="SEU_LINKEDIN_URL">...</a>
   <a href="mailto:SEU_EMAIL">...</a>
   ```

3. **Projetos** (linha ~150+):
   - Edite os 3 cards de projeto
   - Adicione mais copiando a estrutura `<div class="project-card">`

4. **Habilidades** (linha ~300+):
   - Adicione/remova skills
   - Agrupe por categorias

### Adicionar Foto de Perfil

Substitua o ícone placeholder por uma imagem:

```html
<!-- Em index.html, linha ~80 -->
<div class="avatar-placeholder">
    <i class="fas fa-code"></i>  <!-- Remover -->
</div>

<!-- Adicionar: -->
<img src="sua-foto.jpg" alt="Seu Nome" style="width: 100%; height: 100%; border-radius: 50%; object-fit: cover;">
```

## 📸 Para Instagram

### Compartilhar Link

1. **Publique no GitHub Pages**
2. **Use um encurtador de link:**
   - [bit.ly](https://bitly.com) → `bit.ly/portfolio-christian`
   - [tinyurl.com](https://tinyurl.com) → `tinyurl.com/christian-dev`

3. **Post no Instagram:**
   ```
   💼 Confira meu portfolio!
   🔗 Link na bio
   
   #desenvolvedor #python #portfolio #dev
   #analidedados #ti #programacao
   ```

### QR Code para Bio

1. Gere um QR Code do seu portfolio:
   - [qr-code-generator.com](https://www.qr-code-generator.com/)
   - Cole a URL do GitHub Pages

2. Salve a imagem do QR Code

3. Use como destaque nos Stories do Instagram!

### Stories Template

**Crie um story com:**
- Foto do portfolio (screenshot)
- "Link na bio 🔗"
- QR Code no canto
- Swipe up (se tiver +10k seguidores)

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura semântica
- **CSS3** - Estilização moderna (Grid, Flexbox, Animations)
- **JavaScript (Vanilla)** - Interatividade sem frameworks
- **Font Awesome** - Ícones
- **Google Fonts (Inter)** - Tipografia moderna

## 📱 Responsividade

Breakpoints:
- 📱 **Mobile:** < 480px
- 📱 **Tablet:** 481px - 768px
- 💻 **Desktop:** > 768px

Testado em:
- ✅ iPhone (Safari)
- ✅ Android (Chrome)
- ✅ iPad
- ✅ Chrome Desktop
- ✅ Firefox Desktop
- ✅ Edge Desktop

## 🎯 Performance

- ✅ **100% HTML/CSS/JS puro** - Sem dependências pesadas
- ✅ **Carregamento rápido** - Apenas 3 arquivos
- ✅ **SEO Otimizado** - Meta tags apropriadas
- ✅ **Acessibilidade** - ARIA labels e navegação por teclado

## 📝 Checklist de Deploy

- [ ] Personalizar nome e título
- [ ] Atualizar links sociais (GitHub, LinkedIn, Email)
- [ ] Editar projetos (adicionar seus repositórios)
- [ ] Atualizar habilidades técnicas
- [ ] Trocar foto de perfil (opcional)
- [ ] Testar em mobile
- [ ] Fazer deploy (GitHub Pages/Netlify/Vercel)
- [ ] Encurtar URL
- [ ] Gerar QR Code
- [ ] Adicionar link na bio do Instagram
- [ ] Postar no Instagram

## 🐛 Troubleshooting

**Problema: Animações não funcionam**
- Solução: Certifique-se que o `script.js` está linkado corretamente

**Problema: Menu mobile não abre**
- Solução: Verifique se o Font Awesome está carregando

**Problema: Cores não aparecem**
- Solução: Verifique o arquivo `style.css` está no mesmo diretório

**Problema: GitHub Pages não atualiza**
- Solução: Limpe o cache do navegador (Ctrl+Shift+R)

## 📞 Contato

**Christian Lindoso Froz**
- 📧 Email: christianlindoso18@gmail.com
- 💼 LinkedIn: [christian-lindoso-froz](https://www.linkedin.com/in/christian-lindoso-froz)
- 🐙 GitHub: [christianlf](https://github.com/christianlf)
- 📍 Localização: Campinas, SP

## 📄 Licença

Este projeto está sob a licença MIT. Sinta-se livre para usar como base para seu próprio portfolio!

---

**✨ Desenvolvido com ❤️ por Christian Lindoso Froz**

Se gostou, dê uma ⭐ no repositório!
