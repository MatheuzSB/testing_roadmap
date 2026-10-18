# Roadmap OS (app instalável)

Arquivos: index.html, manifest.webmanifest, sw.js, icon-192.png, icon-512.png.

## Opção A: GitHub Pages (funciona no PC e no celular)
1. Crie um repositório chamado roadmap-os no GitHub.
2. Na pasta destes arquivos:
   git init
   git add .
   git commit -m "Roadmap OS"
   git branch -M main
   git remote add origin https://github.com/SEU_USUARIO/roadmap-os.git
   git push -u origin main
3. No repositório: Settings > Pages > Deploy from a branch > main > / (root).
4. Abra https://SEU_USUARIO.github.io/roadmap-os/ no Chrome ou Edge e use "Instalar app" (PC) ou "Adicionar à tela inicial" (celular).
Atenção: em repositório público a página também é pública. Seu progresso NÃO vai junto: fica só no seu navegador.

## Opção B: no Linux, sem internet
   cd pasta-do-roadmap
   python3 -m http.server 8080
Abra http://localhost:8080 no Chromium, Chrome ou Edge e instale pelo ícone na barra de endereço.
O Firefox no Linux não instala sites como app.

## Opção C: só abrir
Dê dois cliques no index.html. Funciona offline, sem instalar.

## Seus dados
O progresso fica no navegador e é separado por endereço (localhost, github.io, arquivo local). Para mover de um lugar para outro: aba Conta > exportar, e no destino importar.
O gerador de questões só funciona no link publicado dentro do Claude.
