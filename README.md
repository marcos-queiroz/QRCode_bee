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

## Browser

Para testar o Leitor no Browser, digite no prompt:
    
    $ cordova run browser

O browser abrirá um imput de resposta do plugin QRCode, nesse caso digite o que seria o conteudo do QRCode:
        
    exemplo: uma url, número ou um texto qualquer.

## Emulação

O Emulador abrirá um imput, que seria a resposta do plugin QRCode, use o JSON para cada formato suportado pelo plugin:

### QR_Code

{"text":"Teste QRCode","format":"QR_CODE","cancelled":false}

### CODE_128

{"text":"0123456789","format":"CODE_128","cancelled":false}

Para mais formatos, consulte a documentação do plugin: https://github.com/phonegap/phonegap-plugin-barcodescanner

## Devise

Para gerar o APK para Android use o comando:
        
    $ cordova buil android

Para gerar o QRCode para testes no aparelho use esse site: http://br.qr-code-generator.com/
