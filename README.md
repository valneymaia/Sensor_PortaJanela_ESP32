
-> Use @myidbot ([IdBot](https://telegram.me/myidbot)) para saber qual o seu ID

Iniciar chat com IDBot -> /start  -- iniciar o Bot -> /getid   -- Pegar seu ID
```
#define CHAT_ID "0101010101"   //ID do seu Telegram
```
-> Para gerar seu novo Bot, você precisa de um Access Token. Fale com o [BotFather](https://telegram.me/botfather) e siga alguns passos simples descritos aqui .

Inclua o UniversalTelegramBot no seu projeto:
```
#include <UniversalTelegramBot.h>
```
-> Passe um token de bot e um cliente SSL:
```
// Telegram BOT Token (Get from Botfather)
#define BOT_TOKEN "XXXXXXXXX:XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX"
WiFiClientSecure secured_client;
UniversalTelegramBot bot(BOT_TOKEN, secured_client);
```
