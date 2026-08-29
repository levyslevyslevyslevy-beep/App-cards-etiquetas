# Etiquetas — PWA de Gerenciamento de Entregas

Transforme sua ferramenta em um **app Android** que funciona offline e pode ser instalado em qualquer celular.

## 📁 Arquivos necessários

```
etiquetas.html         ← App principal
manifest.json          ← Configuração PWA (ícone, nome, cores)
service-worker.js      ← Funcionalidade offline
```

## 🚀 Como usar (3 passos)

### 1️⃣ **Hospede online**

Você precisa de um servidor web para hospedar os arquivos. Opções grátis:

#### **Opção A: Vercel (RECOMENDADO - Fácil)**
- Acesse https://vercel.com
- Clique em "New Project" → "Import Git Repository"
- Ou faça upload dos 3 arquivos diretamente
- Vercel gera um link tipo: `https://etiquetas-xyz.vercel.app`

#### **Opção B: GitHub Pages**
- Crie uma pasta `etiquetas` no seu repositório GitHub
- Coloque os 3 arquivos lá
- Ative "GitHub Pages" nas configurações
- Link: `https://seu-usuario.github.io/etiquetas/`

#### **Opção C: Netlify**
- Acesse https://app.netlify.com
- Faça drag-and-drop dos 3 arquivos
- Pronto! Link automático gerado

---

### 2️⃣ **Acesse pelo celular**

No seu **celular Android** ou **iPhone**:
1. Abra o navegador (Chrome, Firefox, Safari)
2. Digite o link hospedado (ex: `https://etiquetas-xyz.vercel.app`)
3. Aguarde carregar

---

### 3️⃣ **Instale como app**

**No Android (Chrome):**
- Toque em **⋮ (menu)** no topo direito
- Clique em **"Instalar app"** ou **"Adicionar à tela inicial"**
- Um ícone vai aparecer na sua tela inicial

**No iPhone (Safari):**
- Toque no ícone **Compartilhar** (↗)
- Clique em **"Adicionar à tela inicial"**
- Um ícone vai aparecer na sua tela inicial

---

## ✨ Funcionalidades PWA

✅ **Instala como app nativo**  
✅ **Funciona offline** (com dados já importados)  
✅ **Ícone e cor customizados**  
✅ **Sincroniza dados automaticamente**  
✅ **Notificações quando necessário**  
✅ **Acesso rápido por atalhos**  

---

## 📊 Como usar o app

### Importar planilha:
1. Toque em **"Importar Excel"**
2. Selecione seu arquivo `.xlsx`
3. Cards serão criados automaticamente

### Gerenciar cards:
- **Editar**: Clique no lápis ✎
- **Deletar**: Clique no X
- **Marcar concluído**: Clique no botão de status
- **Filtrar**: Use a busca e data
- **Novo card**: Toque em **+**

---

## 🔧 Personalização

Para customizar cores, ícone ou nome do app, edite o arquivo `manifest.json`:

```json
{
  "name": "Seu Nome Aqui",
  "theme_color": "#c1443c",
  "background_color": "#132030"
}
```

---

## 🌐 Recomendação de hospedagem

| Opção | Facilidade | Gratuito | Velocidade |
|-------|-----------|---------|-----------|
| **Vercel** | ⭐⭐⭐⭐⭐ | ✅ | ⚡⚡⚡ |
| **Netlify** | ⭐⭐⭐⭐ | ✅ | ⚡⚡⚡ |
| **GitHub Pages** | ⭐⭐⭐ | ✅ | ⚡⚡ |
| **Sua hospedagem** | ⭐⭐ | ❌ | Depende |

**Recomendo Vercel** — é a mais fácil e rápida.

---

## 📱 Depois de instalar

Depois que o app estiver instalado:
- Abre como um app normal (sem barra de endereço)
- Funciona offline com dados já importados
- Sincroniza quando voltar online
- Toca em "Importar Excel" para adicionar mais entregas

---

## ❓ Dúvidas

**P: Preciso pagar?**  
R: Não! Vercel e Netlify são grátis.

**P: Posso usar em diferentes celulares?**  
R: Sim! Todo mundo acessa o mesmo link.

**P: Funciona sem internet?**  
R: Sim! Depois de instalado, funciona offline com dados já importados.

**P: Posso colocar meu próprio domínio?**  
R: Sim, opções pagas de hospedagem permitem isso.

---

## 🚀 Próximas etapas

1. **Escolha uma opção de hospedagem** (recomendo Vercel)
2. **Faça upload dos 3 arquivos**
3. **Copie o link gerado**
4. **Abra no seu celular**
5. **Instale como app**
6. **Compartilhe o link com seu time**

Pronto! Seu app está no ar! 🎉
