# Landing Page - Consultoria Planejamento Financeiro Personalizado

Site estático puro, sem dependências, pronto para abrir localmente ou publicar no GitHub Pages.

## 📁 Estrutura de Arquivos

```
landing-page-static/
├── index.html      # Página principal (19 KB)
├── style.css       # Estilos (15 KB)
├── script.js       # Interatividade (3.9 KB)
└── README.md       # Este arquivo
```

## 🚀 Como Usar

### Opção 1: Abrir Localmente
1. Baixe os arquivos
2. Abra `index.html` com duplo clique no navegador
3. Pronto! Funciona 100% offline

### Opção 2: Publicar no GitHub Pages
1. Crie um repositório no GitHub
2. Coloque os arquivos na raiz do repositório
3. Vá em Settings → Pages → Source: main branch
4. Seu site estará em: `https://seu-usuario.github.io/seu-repositorio`

### Opção 3: Publicar em Qualquer Servidor Web
- Copie os 3 arquivos para seu servidor
- Nenhuma configuração necessária
- Funciona em qualquer servidor (Apache, Nginx, etc)

## ⚙️ Configuração Importante

**Antes de usar, atualize o número de WhatsApp:**

1. Abra `index.html` em um editor de texto
2. Procure por `55SEUNUMERO`
3. Substitua por seu número (ex: `5511999999999`)
4. Salve o arquivo

Exemplo:
```html
<!-- Antes -->
href="https://wa.me/55SEUNUMERO?text=..."

<!-- Depois -->
href="https://wa.me/5511999999999?text=..."
```

## 🎨 Personalizações

### Cores
Edite `style.css` e procure por `:root`:
```css
:root {
    --accent-primary: #0066ff;      /* Azul principal */
    --bg-primary: #0a0e27;          /* Fundo escuro */
    --text-primary: #ffffff;        /* Texto branco */
}
```

### Conteúdo
Edite `index.html` para mudar textos, seções, etc.

### Fontes
Atualmente usa fontes do sistema. Para adicionar Google Fonts:
1. Abra `index.html`
2. Adicione no `<head>`:
```html
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&display=swap" rel="stylesheet">
```
3. Atualize `style.css`:
```css
--font-display: 'Playfair Display', serif;
```

## ✅ Validação

- ✓ Abre com duplo clique (sem servidor)
- ✓ Funciona 100% offline
- ✓ Responsivo (mobile, tablet, desktop)
- ✓ Pronto para GitHub Pages
- ✓ Sem frameworks ou dependências
- ✓ Sem build necessário
- ✓ Todos os caminhos são relativos
- ✓ Performance otimizada

## 📱 Compatibilidade

- Chrome/Edge (últimas versões)
- Firefox (últimas versões)
- Safari (últimas versões)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🔧 Funcionalidades

- Header com efeito de scroll
- Smooth scroll para links
- Animações ao scroll
- Botão WhatsApp flutuante
- Design responsivo
- Modo escuro sofisticado

## 📝 Licença

Livre para usar e modificar.

## 💬 Suporte

Se tiver dúvidas, verifique:
1. Se atualizou o número de WhatsApp
2. Se os arquivos estão na mesma pasta
3. Se está usando um navegador moderno
4. Se não há erros no console (F12)

---

**Versão:** 1.0  
**Última atualização:** Abril 2026
