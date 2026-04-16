# Pose Store — Assistente PWA

App de assistente de moda e inteligência de mercado para a Pose Store.

## Como publicar gratuitamente no GitHub Pages

### 1. Crie uma conta no GitHub
Acesse https://github.com e crie uma conta gratuita.

### 2. Crie um repositório novo
- Clique em "New repository"
- Nome sugerido: `pose-store-app`
- Marque como **Public**
- Clique em "Create repository"

### 3. Faça upload dos arquivos
Na página do repositório criado, clique em "uploading an existing file" e envie:
- `index.html`
- `manifest.json`
- `sw.js`

### 4. Ative o GitHub Pages
- Vá em **Settings** → **Pages**
- Em "Source", selecione: **Deploy from a branch**
- Branch: **main** | Pasta: **/ (root)**
- Clique em **Save**

### 5. Acesse o app
Em alguns minutos o app estará disponível em:
`https://SEU_USUARIO.github.io/pose-store-app/`

---

## Como instalar no Android (PWA)

1. Abra o link acima no **Chrome** do Android
2. Toque no menu (⋮) no canto superior direito
3. Selecione **"Adicionar à tela inicial"**
4. Confirme — o ícone aparece na home do celular
5. Abra pelo ícone: funciona como app, sem barra do navegador

---

## Arquivos incluídos

| Arquivo | Descrição |
|---|---|
| `index.html` | App completo (HTML + CSS + JS) |
| `manifest.json` | Configuração PWA (nome, ícone, cor) |
| `sw.js` | Service Worker para funcionamento offline |

---

## Ícones (opcional)

Para adicionar ícone personalizado da Pose Store:
- Crie imagens `icon-192.png` (192×192px) e `icon-512.png` (512×512px)
- Faça upload junto com os outros arquivos

---

## Funcionalidades

- Analisador de coleção (Melissa, Hering, DLZ, Visual Jeans, Rala Bela)
- Radar Melissa com busca web em tempo real
- Histórico de análises salvo localmente
- Funciona offline (conteúdo do app)
- Instalável como app no Android
