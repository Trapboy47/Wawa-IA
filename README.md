# Illuminati Boy SignalFx 🚀

Dashboard de sinais SMC em tempo real para XAU/USD e US100.

## Arquivos

- **index.html** → Landing page (apresentação)
- **auth.html** → Página de login/signup
- **dashboard.html** → Dashboard com sinais SMC ao vivo

## Como usar

### 1️⃣ Obter chave Twelve Data API

1. Acesse [twelvedata.com](https://twelvedata.com)
2. Crie uma conta grátis
3. Vá para Dashboard → API Keys
4. Copie sua chave

### 2️⃣ Usar localmente

1. Baixa os arquivos
2. Abre `index.html` no navegador
3. Clica em "Começar"
4. Cola sua chave Twelve Data no campo
5. Clica em "Conectar"

## 🚀 Deploy no GitHub Pages

### Opção 1: Via GitHub Web (mais fácil)

1. Cria um novo repositório em [github.com/new](https://github.com/new)
   - Nome: `seu-username.github.io` (substitui `seu-username` pelo seu user)
   - Deixa pública

2. No repositório, clica em "Add file" → "Upload files"

3. Arrasta os 3 arquivos:
   - `index.html`
   - `auth.html`
   - `dashboard.html`

4. Clica em "Commit changes"

5. Seu site fica em: `https://seu-username.github.io`

### Opção 2: Via Git Command Line

```bash
# Cria pasta do projeto
mkdir illuminati-signalfix
cd illuminati-signalfix

# Inicia git
git init

# Copia os 3 arquivos pra essa pasta
# (index.html, auth.html, dashboard.html)

# Adiciona ao git
git add .
git commit -m "Initial commit - SignalFx Dashboard"

# Adiciona repositório remoto
git remote add origin https://github.com/seu-username/seu-username.github.io.git

# Faz push
git branch -M main
git push -u origin main
```

## ⚙️ Como funciona

1. **Landing Page** → Apresentação do serviço
2. **Auth** → Login/Signup (visual apenas)
3. **Dashboard** → 
   - Cole sua chave Twelve Data
   - Clica "Conectar"
   - Recebe sinais ao vivo de XAU/USD e US100
   - Mostra Entry, SL, TP, Risk/Reward
   - Exibe estrutura SMC (BOS, CHoCH, etc)

## 🔐 Segurança da chave

A chave fica armazenada localmente no seu navegador (localStorage). Não é enviada pra nenhum servidor nosso. 

⚠️ **Importante**: Não compartilhe seu repositório com a chave visível!

## 📊 Sinais SMC

O dashboard analisa:
- **BOS** (Break of Structure) → Rompimento de estrutura
- **CHoCH** (Change of Character) → Mudança de caráter
- **OB** (Order Block) → Bloco de ordens
- **FVG** (Fair Value Gap) → Gap de valor justo

## 💡 Próximas melhorias

- [ ] Mais timeframes (M15, M30, 1H, D)
- [ ] Notificações de sinais em tempo real
- [ ] Histórico de sinais
- [ ] Integração com Telegram
- [ ] Gráficos interativos

## 📧 Suporte

Qualquer dúvida, abre uma issue no repositório.

---

**Made with ❤️ for traders**