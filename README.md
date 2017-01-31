# bf
Bot Facebook Chat
Credit. https://github.com/Larry850806/facebook-chat-bot
Install

git clone https://github.com/Larry850806/facebook-chat-bot.git
cd facebook-chat-bot
npm install
Usage

Start chat bot

step1: modify index.js and change userInfo to your own email and password.
var userInfo = {
    email: 'Your_Email@test.com',
    password: 'Your_Password'
}
step2: start chat bot
npm start
How to customize your bot

customize the response

modify the file database/respond.json.
The bot will find the "keyword" and make response.

{
    "hello": "Hello ~ I'm Pudding Dog",

    "ya": "YAAAAA~~",

    "apple": "apple is good"
}


customize the default message

modify the arr in database/question.json.

[
    "Hello",
    "Ya",
    "I love apple"
]


How to stop the chat bot

Just terminate the process or say "/stop" to the bot on facebook.


License

The MIT License (MIT)

Copyright (c) 2016 Larry Lu

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
