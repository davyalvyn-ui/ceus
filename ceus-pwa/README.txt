CEU'S como app (PWA)

CONTEÚDO
  index.html            o app inteiro (fonte e leitor de Excel já embutidos)
  manifest.webmanifest  nome, cores e ícones do app
  sw.js                 deixa o app abrir sem internet
  icons/                ícones

COMO COLOCAR NO AR (grátis, uns 2 minutos)
  Opção A, Netlify: entre em app.netlify.com/drop e arraste esta pasta inteira.
  Opção B, Cloudflare Pages: Workers e Pages > Criar > Pages > Upload de ativos > envie a pasta.
  Opção C, GitHub Pages: crie um repositório, envie estes arquivos e ative Pages em Settings.
  O endereço precisa ser https (as três opções já são).

COMO INSTALAR
  Android (Chrome): abra o endereço, menu de três pontos > "Instalar app" ou "Adicionar à tela inicial".
  iPhone (Safari): botão Compartilhar > "Adicionar à Tela de Início".
  PC (Chrome ou Edge): ícone de instalar na barra de endereço.

ATUALIZAR
  Troque o index.html na hospedagem e mude VERSAO no sw.js (ex.: ceus-v29-1).
  O app pega a versão nova na próxima vez que abrir com internet.

OBSERVAÇÃO
  Os dados ficam salvos no navegador de cada aparelho e não sincronizam entre PC e celular.
  Limpar os dados do navegador apaga os conjuntos salvos. Exporte o que for importante.
