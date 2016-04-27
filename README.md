# chatter-bot

A simple telegram-bot wtitten in LUA 

# commands
`/ban`

 حظر عضو من ارسال رساله بالرد على رسالته

`/unban`

فتح الحظر عن عضو عن طريق الرد على رسالته

`/users` 

معرفه عدد الاعضاء المشتركين

`/broadcast`

ارسل هذا الامر وكل رساله كانت بعده سترسل لجميع المشتركين

`/unbroadcast`

لكي تتوقف ارسال الرسائل وتفعيل الاوامر البقيه

`/start`

لأظهار رساله ترحيب للاعضاٱء

`/id` 

بالرد على رساله موجهه يضهر لك المعلومات

# التنصيب


انسخ الامر التالي

```
git clone https://github.com/micodev/chatter.git && cd chatter && chmod +x ./lua.sh && ./lua.sh run && ./lua.sh

```
خلي التوكين للبوت بين "" في bot_api_bot
وايدي حسابك الخاصه ب you

```lua

local bot_api_key = "" -- token
local BASE_URL = "https://api.telegram.org/bot"..bot_api_key
you = --ايدي هنا فقط رقم
local BASE_FOLDER = "" -- do not set this

```
اذا تحب تساعدني او عدك استفسار احب اسمع منك
@malvoo
او 
@lua_lua

لمعرفه جديد عن البوت �
 [@mahdib9](https://telegram.me/mahdib9)
