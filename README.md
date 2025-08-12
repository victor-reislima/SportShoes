# 🏃‍♂️ SportShoes - Loja Virtual de Tênis

Uma loja virtual completa e responsiva especializada em tênis esportivos, desenvolvida com HTML, CSS e JavaScript puro.

## 📋 Descrição

A SportShoes é uma loja virtual fictícia que oferece uma experiência completa de compra de tênis esportivos. O projeto foi desenvolvido seguindo as melhores práticas de design responsivo e UX, com foco em simplicidade e usabilidade.

## ✨ Funcionalidades

### 🏠 Página Inicial (index.html)
- **Banner principal** com chamada para ação
- **Produtos em destaque** com efeitos hover
- **Categorias** de produtos (Corrida, Basquete, Casual, Treino)
- **Navegação fixa** com menu responsivo
- **Rodapé** com informações de contato e redes sociais

### 🛍️ Página de Produtos (produtos.html)
- **Lista completa** de produtos com filtros por categoria
- **Sistema de filtros** interativo (Todos, Corrida, Basquete, Casual, Treino)
- **Cards de produtos** com hover effects
- **Links "Ver mais"** para detalhes do produto

### 📦 Página de Produto (produto.html)
- **Galeria de imagens** com thumbnails interativas
- **Informações detalhadas** do produto
- **Seleção de tamanho** e cor
- **Controle de quantidade**
- **Especificações técnicas**
- **Produtos relacionados**

### 📞 Página de Contato (contato.html)
- **Formulário de contato** completo
- **Informações de contato** da empresa
- **Mapa interativo** (Google Maps)
- **FAQ** com accordion
- **Links para redes sociais**

### ℹ️ Página Sobre (sobre.html)
- **História fictícia** da empresa
- **Valores e missão**
- **Equipe** com fotos e biografias
- **Números** da empresa
- **Depoimentos** de clientes

## 🎨 Design e UX

### Características Visuais
- **Design moderno** e minimalista
- **Paleta de cores** azul (#2563eb) e tons neutros
- **Tipografia** Inter (Google Fonts)
- **Ícones** Font Awesome
- **Imagens** de alta qualidade do Unsplash

### Efeitos e Animações
- **Hover effects** em cards de produtos
- **Transições suaves** em botões e links
- **Zoom** em imagens de produtos
- **Overlay** com botão "Ver mais"
- **Transformações** em elementos interativos

### Responsividade
- **Mobile-first** approach
- **Grid responsivo** que se adapta a diferentes telas
- **Menu mobile** com ícone hambúrguer
- **Layout flexível** para tablets e desktops

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura semântica
- **CSS3** - Estilos e animações
  - Flexbox e Grid para layout
  - Media queries para responsividade
  - CSS custom properties
  - Transições e transformações
- **JavaScript** - Interatividade
  - Filtros de produtos
  - Galeria de imagens
  - FAQ accordion
  - Formulário de contato
- **Font Awesome** - Ícones
- **Google Fonts** - Tipografia
- **Unsplash** - Imagens de produtos

## 📱 Responsividade

O site é totalmente responsivo e funciona perfeitamente em:

- 📱 **Mobile** (320px - 768px)
- 📱 **Tablet** (768px - 1024px)
- 💻 **Desktop** (1024px+)

### Breakpoints
- `@media (max-width: 768px)` - Mobile
- `@media (max-width: 480px)` - Mobile pequeno

## 🚀 Como Usar

1. **Clone ou baixe** os arquivos do projeto
2. **Abra** o arquivo `index.html` em qualquer navegador moderno
3. **Navegue** pelas páginas usando o menu superior
4. **Teste** a responsividade redimensionando a janela

## 📁 Estrutura do Projeto

```
SportShoes/
├── index.html          # Página inicial
├── produtos.html       # Lista de produtos
├── produto.html        # Detalhes do produto
├── contato.html        # Página de contato
├── sobre.html          # Página sobre a empresa
├── styles.css          # Estilos CSS
└── README.md           # Documentação
```

## 🎯 Funcionalidades JavaScript

### Filtros de Produtos
```javascript
// Filtra produtos por categoria
filterBtns.forEach(btn => {
    btn.addEventListener('click', function() {
        const category = this.getAttribute('data-category');
        // Lógica de filtro...
    });
});
```

### Galeria de Imagens
```javascript
// Troca imagem principal ao clicar nas thumbnails
function changeImage(thumbnail, newSrc) {
    document.getElementById('mainImage').src = newSrc;
    // Atualiza classes ativas...
}
```

### FAQ Accordion
```javascript
// Toggle para expandir/recolher respostas
faq-question.addEventListener('click', function() {
    // Lógica do accordion...
});
```

## 🎨 Paleta de Cores

- **Azul Principal**: `#2563eb`
- **Azul Escuro**: `#1d4ed8`
- **Cinza Escuro**: `#1f2937`
- **Cinza Médio**: `#6b7280`
- **Cinza Claro**: `#f8f9fa`
- **Branco**: `#ffffff`

## 📞 Informações de Contato (Fictícias)

- **E-mail**: contato@sportshoes.com
- **Telefone**: (11) 99999-9999
- **Endereço**: Rua das Flores, 123 - São Paulo/SP
- **Horário**: Seg-Sex 9h-18h, Sáb 9h-16h

## 🔧 Personalização

### Cores
Para alterar as cores do site, edite as variáveis CSS no arquivo `styles.css`:

```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #1d4ed8;
    /* ... outras cores */
}
```

### Produtos
Para adicionar novos produtos, edite o arquivo `produtos.html` e adicione novos cards seguindo a estrutura:

```html
<div class="product-card" data-category="categoria">
    <div class="product-image">
        <img src="url-da-imagem" alt="Nome do Produto">
        <div class="product-overlay">
            <a href="produto.html?id=X" class="btn-secondary">Ver mais</a>
        </div>
    </div>
    <div class="product-info">
        <h3>Nome do Produto</h3>
        <p class="price">R$ 0,00</p>
    </div>
</div>
```

## 📝 Licença

Este projeto foi desenvolvido para fins educacionais e de demonstração. Todas as imagens são do Unsplash e estão disponíveis para uso livre.

## 🤝 Contribuição

Sinta-se à vontade para contribuir com melhorias, correções de bugs ou novas funcionalidades!

---

**Desenvolvido com ❤️ para demonstrar habilidades em desenvolvimento web front-end.**
