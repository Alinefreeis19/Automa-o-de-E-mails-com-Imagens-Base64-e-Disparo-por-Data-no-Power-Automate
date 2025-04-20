# Envio automatizado de e-mails com base em datas de planilha

Este projeto é um fluxo automatizado criado no Power Automate, com o objetivo de enviar e-mails personalizados em HTML, com imagens incorporadas via Base64, para uma lista de destinatários definidos em uma base Excel. O envio é condicionado à data atual, garantindo que o conteúdo só seja disparado na data correta.

## Recursos utilizados:
- Power Automate
- SharePoint (para armazenar as imagens)
- Excel Online (base de dados com e-mails, assuntos e datas)
- Outlook 365 (envio de e-mail)
- HTML responsivo com imagens embutidas

## Lógica de funcionamento:
1. Recorrência diária às 8h.
2. Busca de 3 imagens no SharePoint e conversão para Base64.
3. Verificação se a data atual está presente na planilha.
4. Se sim, monta e envia o e-mail em HTML com imagens e link.

## Exemplo visual:
(imagem do e-mail ou print do fluxo)

## Como adaptar para seu ambiente:
- Substitua os links do SharePoint pelas URLs das suas imagens.
- Altere os dados do Excel conforme a sua base.