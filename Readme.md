# 🚀 Eletric Blue Jogos - Landing Page

Landing page profissional para a editora **Eletric Blue Jogos**, focada em metodologia ativa através de jogos analógicos print-and-play.

## 📋 Conteúdo

A landing page apresenta:

- ✨ **Hero Section**: Proposta de valor clara e chamadas para ação
- 🎯 **Missão**: 6 pilares da pedagogia ativa com jogos analógicos
- 🎲 **Nossos Jogos**: Cards dos 3 jogos publicados (Dengueside Survival, Dengue Blitz, Blind Code)
- 📚 **Pedagogia**: Seção sobre desenvolvimento psicomotor e caso de uso real em sala de aula
- 🖨️ **Print & Play**: Modelo de negócio acessível com opções de entrega
- 💬 **Case Study**: Depoimento validado de educador
- 🎓 **CTA Final**: Chamada para ação com download gratuito
- 📞 **Footer**: Links de navegação e recursos

## 🔧 Como usar no GitHub Pages

### Opção 1: Repositório específico para a landing page

```bash
# 1. Crie um repositório no GitHub chamado:
# eletric-blue-jogos (ou o nome que preferir)

# 2. Clone o repositório localmente
git clone https://github.com/seu-usuario/eletric-blue-jogos.git
cd eletric-blue-jogos

# 3. Copie o arquivo landing_eletric_blue.html
cp landing_eletric_blue.html index.html

# 4. Commit e push
git add index.html
git commit -m "Adicionar landing page Eletric Blue Jogos"
git push origin main

# 5. Vá às configurações do repositório
# Settings → Pages
# Selecione "main" como branch de source
# Salve

# 6. A página estará disponível em:
# https://seu-usuario.github.io/eletric-blue-jogos/
```

### Opção 2: Usar como `index.html` em um site existente

Se você já tem um repositório pessoal (`seu-usuario.github.io`):

```bash
# 1. Copie landing_eletric_blue.html para o repositório
cp landing_eletric_blue.html seu-usuario.github.io/

# 2. Se quiser como página raiz, renomeie para index.html
mv seu-usuario.github.io/landing_eletric_blue.html seu-usuario.github.io/index.html

# 3. Ou crie uma pasta específica
mkdir seu-usuario.github.io/eletric-blue
cp landing_eletric_blue.html seu-usuario.github.io/eletric-blue/index.html

# 4. Commit e push
cd seu-usuario.github.io
git add .
git commit -m "Adicionar Eletric Blue Jogos"
git push origin main
```

## 🎨 Customização

### Cores
No arquivo HTML, localize a seção `:root` do CSS e customize:

```css
:root {
    --primary: #2563eb;           /* Azul principal */
    --primary-dark: #1e40af;
    --accent: #06b6d4;            /* Ciano/turquesa */
    --accent-dark: #0891b2;
    --success: #10b981;           /* Verde */
    --warning: #f59e0b;           /* Âmbar */
    --text-primary: #1f2937;      /* Texto escuro */
    --text-secondary: #6b7280;    /* Texto cinza */
    /* ... outros */
}
```

### Logotipo
Procure por `<span class="logo">⚡ Eletric Blue Jogos</span>` e customize com seu próprio logotipo ou adicione uma imagem:

```html
<a href="#" class="logo">
    <img src="seu-logo.png" alt="Eletric Blue Jogos" height="40">
</a>
```

### Links do Ludopedia
Os links para os jogos estão em vários lugares. Se mudar de plataforma, busque:
- `https://ludopedia.com.br/jogo/dengueside-survival`
- `https://ludopedia.com.br/jogo/dengue-blitz`
- `https://ludopedia.com.br/jogo/blind-code`

E substitua pelos seus links.

### Seções
Você pode:
- **Remover seções**: Copie/cola as seções (`<section>`) inteiras e delete
- **Reordenar**: Mova as seções para cima/baixo
- **Adicionar**: Duplique uma seção e customize o conteúdo

## 📱 Responsividade

A landing page é totalmente responsiva e funciona bem em:
- 📱 Mobile (< 768px)
- 📱 Tablet (768px - 1024px)
- 💻 Desktop (> 1024px)

Todos os breakpoints estão configurados ao final do CSS com `@media (max-width: 768px)`.

## ✅ Checklist pré-publicação

Antes de fazer deploy, verifique:

- [ ] Cores estão atualizadas com identidade visual
- [ ] Links para jogos estão corretos
- [ ] Informação de contato está atualizada
- [ ] Telefone/email estão no footer se necessário
- [ ] Logo customizado está adicionado
- [ ] Descrição de cada jogo está correta
- [ ] Testou em mobile
- [ ] Testou links internos (#sections)
- [ ] Testou links externos (Ludopedia, etc)

## 🔍 SEO

A página já tem meta tags otimizadas para Google:

```html
<meta name="description" content="...">
<meta name="keywords" content="...">
<meta property="og:title" content="...">
<meta property="og:description" content="...">
```

Você pode customizar essas tags no `<head>` para melhorar posicionamento.

## 🚀 Próximos passos

### Depois de publicar a landing page:

1. **Newsletter**: Adicione formulário de email (Mailchimp, ConvertKit, etc)
2. **Blog**: Crie um blog com posts sobre educação e jogos
3. **Loja**: Integre com WooCommerce ou Shopify para vender kits prontos
4. **Comunidade**: Fórum ou Discord para educadores compartilharem experiências
5. **Analytics**: Adicione Google Analytics para medir engajamento

## 📧 Contato & Support

Para suporte ou dúvidas sobre a landing page:
- Abra uma issue no repositório
- Entre em contato através do email no site

---

**Desenvolvido com ❤️ para Eletric Blue Jogos**
