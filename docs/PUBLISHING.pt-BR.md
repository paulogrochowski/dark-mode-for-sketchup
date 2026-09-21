# Publicar o site

## Abrir no computador

Abra `index.html`. Mantenha a pasta `assets` ao lado dele. Não precisa instalar ferramentas ou compilar.

## Preencher os links

No fim de `index.html`, procure `SITE_CONFIG` e preencha os endereços HTTPS de checkout, GitHub, Issues e Extension Warehouse. Deixe Warehouse vazio enquanto não houver página aprovada. O preço é US$ 1, em compra única, sem assinatura. Configure esse valor também no provedor de pagamento. Até preencher o checkout, o botão informa que as vendas ainda não estão abertas.

## GitHub Pages

1. Crie o repositório `Dark-Mode-for-SketchUp`.
2. Envie o conteúdo da pasta do projeto; o `index.html` deve ficar na raiz.
3. Em **Settings → Pages**, selecione **Deploy from a branch → main → /(root)** e salve.
4. Aguarde e abra o endereço que o GitHub informar.

[Guia oficial do GitHub](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).

## Outra hospedagem estática

Envie `index.html` e `assets/` para a raiz pública da hospedagem, sem alterar a estrutura. Não é necessário comando de build.

## Suporte na Extension Warehouse

Depois de publicar o repositório, use:
`https://github.com/SEU-USUARIO/Dark-Mode-for-SketchUp/issues`

Você também pode usar a URL pública do site com `#support`. Não envie à Warehouse um endereço que ainda esteja como placeholder.

## O que está incluído

Site estático, ícone e artes fornecidos, documentação e modelos de Issues. Os instaladores e fontes originais ficam na pasta local separada `Private-Release`: não publique essa pasta, pois o produto será vendido. O ZIP do site contém apenas os arquivos públicos. O código da extensão não foi alterado. A compatibilidade foi extraída da documentação fornecida; a extensão não foi executada no SketchUp nesta sessão.


## Serial e entrega

O site estático não confirma pagamentos, não emite seriais e não libera arquivos pagos. O pacote separado Customer-Package inclui a versão 1.0.1 com validação offline de licença pessoal. O gerador privado em License-Manager-PRIVATE faz a emissão manual após sua confirmação de pagamento. Não há expiração nem bloqueio por computador. Teste o RBZ licenciado no SketchUp antes de iniciar as vendas.
