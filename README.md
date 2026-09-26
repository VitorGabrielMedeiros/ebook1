# Página de Vendas - Ebook Agenda com IA

## 📦 Arquivos Inclusos

- `index.html` - Estrutura HTML da página
- `style.css` - Toda a estilização
- `script.js` - Animações de entrada (Intersection Observer)

## 🚀 Como Usar

### Localmente
1. Descompacte o arquivo ZIP
2. Abra o `index.html` no seu navegador (duplo clique)
3. A página deve funcionar normalmente com todas as animações

### No GitHub Pages

1. **Crie um novo repositório** no GitHub (ex: `ebook-agenda-ia`)

2. **Faça upload dos 3 arquivos** para o repositório:
   - `index.html`
   - `style.css`
   - `script.js`

3. **Ative GitHub Pages**:
   - Vá em **Settings → Pages**
   - Em "Source", selecione **main** (ou **master**)
   - Clique em **Save**
   - GitHub vai gerar um link tipo `https://seu-usuario.github.io/ebook-agenda-ia`

4. **Pronto!** Sua página estará no ar

## ⚙️ Customização

### Mudar Preço
No `index.html`, procure por:
```html
<div class="old">De R$ 47,00</div>
<div class="val">R$ 19<span>,90</span></div>
```

### Mudar Link do Botão
Procure por:
```html
<a class="cta block" href="#">Organizar minha agenda agora</a>
```
E substitua o `#` pelo seu link de checkout da Kiwify

### Cores
No `style.css`, procure por `:root{}` para mudar as variáveis de cor:
```css
--accent:#ff4d2e;  /* cor principal (laranja) */
--good:#3ecf8e;    /* cor de sucesso (verde) */
--bg:#050505;      /* fundo */
--ink:#f5f5f5;     /* texto principal */
```

### Fonts
As fontes são carregadas do Google Fonts. Se quiser mudar, edite o `<link>` no `<head>` do HTML

## 📱 Responsividade

A página já é totalmente responsiva e se adapta para:
- Desktop
- Tablet
- Mobile

Testado em Chrome, Firefox, Safari e Edge

## ♿ Acessibilidade

- Respeita preferência de `prefers-reduced-motion` (desliga animações para quem tem sensibilidade a movimento)
- Scroll behavior suave (respeitando a preferência do sistema)
- Contrast adequado WCAG AA

## 🎯 Performance

- Sem JavaScript pesado
- CSS otimizado
- Fonts carregadas do Google Fonts (padrão da web)
- Imagens otimizadas (mockup de celular é apenas CSS/SVG)

## 🔗 Integração com Checkout

Substitua o link do botão CTA por:
- **Kiwify**: seu link de checkout
- **Hotmart**: seu link de afiliado/produtor
- **Eduzz**: seu link do produto
- Qualquer outra plataforma

## ❓ Dúvidas

Se algo não funcionar:
1. Certifique-se de que os 3 arquivos estão na mesma pasta
2. Confirme que o navegador não está bloqueando scripts
3. Limpe o cache do navegador (Ctrl+Shift+R ou Cmd+Shift+R)

---

**Bom lançamento!** 🚀
