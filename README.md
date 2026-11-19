# Fazenda Manjedoura

Aplicativo web progressivo (PWA) de manejo de pecuária e cria com funcionamento offline (`localStorage` + Service Worker).

## Como publicar no GitHub e transformar em app / APK

1. Crie um novo repositório público no **GitHub** (ex.: `fazenda-manjedoura`).
2. Envie todos os arquivos desta pasta para a raiz do repositório:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
3. Vá em **Settings > Pages** no repositório, selecione a branch `main` e a pasta `/ (root)`, e salve para ativar o **GitHub Pages** (`https://seu-usuario.github.io/fazenda-manjedoura/`).
4. **Instalar no celular (Android / iPhone):** abra o link do GitHub Pages no navegador e escolha **Instalar aplicativo** ou **Adicionar à tela de início**.
5. **Gerar `.apk` no PWABuilder:** acesse `https://www.pwabuilder.com`, cole a URL do seu GitHub Pages e gere o pacote **Android**.
