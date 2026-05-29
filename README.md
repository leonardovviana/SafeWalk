# 🛡️ SafeWalk — Segurança Feminina

Protótipo (PWA) de um app de segurança urbana feito para mulheres: **botão SOS**, **rota segura por IA**, **guardiões de confiança** e **monitoramento em tempo real**. Visual neon rosa, glassmorphism e Modo Apresentação (pitch deck) para o desktop.

> ⚠️ Projeto de apresentação — **dados fictícios**.

## 📲 Como instalar no celular

O app é um **PWA**: instala direto pelo navegador, sem loja de apps.

**Android (Chrome/Edge):**
1. Abra o link do app
2. Toque no banner **“Instalar SafeWalk”** (ou menu ⋮ → *Instalar app*)
3. O ícone aparece na tela inicial 🎉

**iPhone (Safari):**
1. Abra o link no **Safari**
2. Toque em **Compartilhar** (quadrado com seta ↑)
3. Escolha **“Adicionar à Tela de Início”**

Depois de instalado, abre em tela cheia e **funciona offline**.

## 🖥️ Modo Apresentação

No **desktop**, clique em **“Modo Apresentação”** (canto superior direito): vira um pitch deck com tour guiado no celular.
- `←` / `→` navegam · `Espaço` play/pause · `Esc` sai

## 🚀 Publicar online (GitHub Pages)

Para a turma acessar pelo celular, hospede de graça:
1. No repositório → **Settings → Pages**
2. Em *Source*: branch **main**, pasta **/ (root)** → **Save**
3. Em ~1 min fica disponível em:
   `https://leonardovviana.github.io/SafeWalk/`

> O PWA precisa de **HTTPS** (que o GitHub Pages fornece) para instalar e funcionar offline.

## 🎨 Ícones PNG (para iPhone)

Os ícones são SVG (perfeitos no Android). Para o iPhone usar o ícone personalizado, gere os PNGs:
1. Abra **`gerar-icones.html`** no navegador
2. Clique em **“Baixar todos os ícones”**
3. Mova os PNGs baixados para esta pasta e faça commit

O `manifest` e o `<head>` já apontam para esses PNGs.

## 📁 Arquivos

| Arquivo | Função |
|---|---|
| `index.html` | App completo (HTML/CSS/JS) |
| `manifest.webmanifest` | Configuração do PWA |
| `sw.js` | Service worker (cache offline) |
| `icon.svg` / `icon-maskable.svg` | Ícones do app |
