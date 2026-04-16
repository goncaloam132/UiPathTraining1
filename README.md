# UiPath Email Automation

## Descrição
Automação que lê emails, guarda as faturas anexadas numa pasta e posteriormente altera as células no excel, adicionando valor de desconto e assinatura.

## Tecnologias
- UiPath Studio
- Gmail Activities 
- Use Application/Browser 
- Excel Scope - Read and Write

## Funcionalidades
- Ler emails da Inbox
- Criar pasta "Invoices" 
- Processar emails automaticamente
- Ler células para guardar código de cliente
- Abrir browser e escrever código cliente para obter valor de desconto
- Adicionar o valor de desconto à fatura.
- Assinar fatura
- 
## Como executar
1. Abrir no UiPath Studio
2. Configurar ligação ao Gmail
3. Executar Main.xaml

## Resultados

Podem ser obtidas as faturas originais no site https://acme-test.uipath.com/first-automation, basta inserir o email dentro do Notify Me.
Neste repositório já se encontram as faturas depois da automação, com valores de desconto e assinatura.
Também está inserido uma pasta de screenshots com as imagens de todo o workflow criado e os clicks capturados pelo Application/Browser Scope.

## DEV

GONÇALO AMORIM
goncaloamorim132@gmail.com
https://www.linkedin.com/in/goncaloamorimm/
