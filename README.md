# QRCode_bee

Um Simples APP Cordova para leitura de QRCode.

## Plugins

Listar os plugins instalados, digite no prompt: 
    $ cordova plugins ls

cordova-plugin-compat 1.1.0 "Compat"
cordova-plugin-device 1.1.4 "Device"
cordova-plugin-dialogs 1.3.1 "Notification"
cordova-plugin-splashscreen 4.0.1 "Splashscreen"
cordova-plugin-whitelist 1.3.1 "Whitelist"
phonegap-plugin-barcodescanner 6.0.5 "BarcodeScanner"


## Emulação

Para testar o Leitor no Emulador ou no Browser, digite no prompt:
    $ cordova run browser

O browser abrirá um imput com o comando de resposta do plugin QRCode, use o JSON para cada formato suportado pelo plugin:

### QR_Code

{
  "text": "Teste do leitor QRCode bee", 
  "format": "QR_CODE", 
  "cancelled": "false"
}

### CODE_128

{
  "text": "1234567890", 
  "format": "CODE_128", 
  "cancelled": "false"
}

Para mais formatos, consulte a documentação do plugin: https://www.npmjs.com/package/phonegap-plugin-barcodescanner
