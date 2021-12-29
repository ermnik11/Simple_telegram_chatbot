# Simple_telegram_chatbot
This repo is a part of my portfolio of data science projects completed by me for academic, self learning, and hobby purposes.
____
ƒанный репозиторий содержит всЄ необходимое дл€ создани€ чат-бота в Telegram.

* telegram_chatbot_creation_tutorial.ipynb - инструкци€ по созданию бота в telegram.
* ChatBot.ipynb - содержит всю серверную часть бота.

 лиентом выступает диалог в Telegram. Ѕот сделан на RuGPT-3 (https://developers.sber.ru/portal/tools/rugpt-3).
____
¬ итоге получилась проста€ болталка на GPT c ведением log файла. ѕроверить можно в телеграме по адресу созданного бота.
»змен€€ параметры, можно добитьс€ разной длины и "Ємкости" ответов бота. Ќапример, с

* max_length=size+128, 
* repetition_penalty=3.2, 
* temperature=1,
* num_beams=3,
* length_penalty=0.01

бот отвечает коротко, диалог с ним похож на диалог с живым человеком, но трудно добитьс€ генерации длинных развЄрнутых ответов.

— параметрами:

* max_length=size+128, 
* repetition_penalty=5.0, 
* temperature=1.1,
* num_beams=5,
* length_penalty=0.1

бот может ответить развЄрнуто. Ќо иногда отвечает невпопад.

”величива€ temperature и num_beams бот становитс€ способен генерировать увлекательные истории, но при этом ему становитс€ сложнее придерживатьс€ темы разговора.
