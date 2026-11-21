# Operação 365 · by NOVAXS

Contador de dias sem recaída com patentes de Recruta (dia 0) a Coronel (dia 365).
Funciona no celular, sem internet, e pode ser instalado como app.

## Publicar no GitHub Pages

1. Crie um repositório no GitHub (por exemplo `operacao-365`).
2. Envie todos os arquivos desta pasta para a raiz do repositório:
   `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`, `maskable-512.png`.
3. No repositório, abra **Settings > Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**, branch `main` e pasta `/ (root)`. Salve.
5. Espere cerca de 1 minuto. O endereço será `https://SEU-USUARIO.github.io/operacao-365/`.

## Instalar no celular (Android)

Abra o endereço no Chrome, toque nos três pontinhos e escolha **Instalar app**
(ou **Adicionar à tela inicial**). O ícone aparece na tela e o app abre em tela cheia.

## Gerar o APK

Com o endereço publicado, entre em https://www.pwabuilder.com, cole o endereço,
toque em **Package for stores** e escolha **Android**. O site gera o pacote com o APK.

## Tela de abertura

O app tem duas telas de abertura. Primeiro aparece a do Android, que mostra o ícone e o nome
**Operação 365 · by NOVAXS** (vem do `manifest.webmanifest`). Em seguida aparece a do próprio app,
com o nome, "by NOVAXS" e a barra de progresso. No PWABuilder, mantenha o nome sugerido.

## Importante

- Os dados ficam só no navegador de cada pessoa, neste celular. Se limpar os dados do Chrome ou
  desinstalar, a contagem some. Use **Backup dos dados**, no fim da aba Hoje, de vez em quando.
- O repositório público mostra o código do app, mas nunca a contagem de ninguém.
- Para mudar o app depois, troque o `index.html` e aumente o número da versão em `sw.js`
  (`op365-v2` para `op365-v3`, e assim por diante), senão o celular continua mostrando a versão antiga.
- O quadro de honra do grupo e o salvamento na conta só existem na versão publicada no Claude.
  Aqui o app fica sem eles.
- Na versão do GitHub a biometria pode funcionar, porque o endereço é seguro (https).
