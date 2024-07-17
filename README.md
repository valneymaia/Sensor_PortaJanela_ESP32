
[BotFather]((https://telegram.me/myidbot))


Para gerar seu novo Bot, você precisa de um Access Token. Fale com o [BotFather](https://telegram.me/botfather) e siga alguns passos simples descritos aqui .

Inclua o UniversalTelegramBot no seu projeto:

#include <UniversalTelegramBot.h>

e passe um token de bot e um cliente SSL:

// Telegram BOT Token (Get from Botfather)
#define BOT_TOKEN "XXXXXXXXX:XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX"
WiFiClientSecure secured_client;
UniversalTelegramBot bot(BOT_TOKEN, secured_client);
