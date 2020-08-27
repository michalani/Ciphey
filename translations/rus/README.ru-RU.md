<p align="center">
Переводы <br>
<a href=https://github.com/Ciphey/Ciphey/tree/master/translations/id/README.md>🇮🇩 ID</a>
 <br> <br>
➡️ 
<a href="https://docs.ciphey.online"> Документация </a> |
<a href="https://discord.ciphey.online"> Discord</a> |
 <a href="https://docs.ciphey.online/en/latest/install.html"> Руководство по установке </a>
 ⬅️

<br>
  <img src="Pictures_for_README/binoculars.png" alt="Ciphey">
</p>

<p align="center">
  <img alt="GitHub commit activity" src="https://img.shields.io/github/commit-activity/m/ciphey/ciphey">
<img src="https://pepy.tech/badge/ciphey">
 <img src="https://pepy.tech/badge/ciphey/month">
  <a href="https://discord.gg/wM3scnc"><img alt="Discord" src="https://img.shields.io/discord/728245678895136898"></a>
<a href="https://pypi.org/project/ciphey/"><img src="https://img.shields.io/pypi/v/ciphey.svg"></a>
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="Ciphey">
  
  <img src="https://github.com/brandonskerritt/Ciphey/workflows/Python%20application/badge.svg?branch=master" alt="Ciphey">
<br>
Полностью автоматизированный инструмент расшифровки с использованием естественного языка обработки и артефактного интеллекта, наряду с некоторым здравым смыслом.
</p>
<hr>

## [Руководство по установке] (https://docs.ciphey.online/en/latest/install.html)

| <p align="center"><a href="https://pypi.org/project/ciphey"> 🐍 Python (Universal) </a></p> |
| ----------------------------------------------------------------------------------------- |
| <p align="center"><img src="Pictures_for_README/python.png"/></p> | | |
| `питон3 -m pip install ciphey --upgrade` | 

| Linux | Mac OS | Windows |
| ----------- | ------ | ----------- |
| ![Статус рабочего процесса GitHub](https://img.shields.io/github/workflow/status/ciphey/ciphey/Python%20application?label=Linux) |![Статус рабочего процесса GitHub](https://img.shields.io/github/workflow/status/ciphey/ciphey/Python%20application?label=Mac%20OS) | ![Статус рабочего процесса GitHub](https://img.shields.io/github/workflow/status/ciphey/ciphey/Python%20application?label=Windows) |
  

<hr>

# 🤔 Что это?
Ciphey - автоматический инструмент для расшифровки. Введите зашифрованный текст, получите расшифрованный текст обратно.
> "Какой тип шифрования?"

В том-то и дело. Ты не знаешь, ты просто знаешь, что это возможно зашифровано. Шифрование поможет тебе разобраться.

Шифрование может решить большинство задач за 3 секунды или меньше.



**Техническая часть.** В Ciphey используется пользовательский модуль искусственного интеллекта (_AuSearch_) с _Cipher Detection Interface_ для приближения к тому, чем что-то зашифровано. А затем настраиваемый естественный язык обработки _Language Checker Interface_, который может определить, когда заданный текст становится простым текстом.

И это только верхушка айсберга. С полным техническим пояснением можно ознакомиться в нашей [документации](https://docs.ciphey.online/en/latest).

# ✨ Особенности

- **Поддерживаются** кодировки (двоичные, base64) и обычные кодировки, такие как шифр Цезаря, Транспозиция и др. **[Полный список можно посмотреть здесь](https://docs.ciphey.online/en/latest/ciphers.html)**
- **Привычный искусственный интеллект с расширенным поиском (AuSearch) для ответа на вопрос "Какое шифрование использовалось?" ** В результате расшифровка занимает менее 3 секунд 
- **Привычный встроенный модуль обработки естественного языка** Шифрование может определить, является ли что-то простым текстом или нет. Он обладает невероятно высокой точностью и быстротой.
- **Мульти-языковая поддержка** в настоящее время, только немецкий и английский (с вариантами AU, UK, CAN, USA).
- **Помощь шифрования** Которые альтернативы, такие как CyberChef Magic не делают 
- **[C core](https://github.com/Ciphey/CipheyCore)** Потрясающе быстро.



## 🔁 Base64 Зашифровано 42 раза

<table>
  <tr>
  <th> Имя </th>
    <th> ⚡ Ciphey ⚡ </th>
    <th> 🐢 CyberChef 🐢 </th>
  </tr>
  <tr>
  <th> Gif </th>
    <td><img src="Pictures_for_README/ciphey_gooder_cyberchef.gif" alt="The guy she tells you not to worry about"></td>
    <td><img src="Pictures_for_README/not_dying.gif" alt="You"></td>
  </tr>
  <tr>
  <th> Time </th>
    <td> 2 секунды </td>
    <td> 6 секунд </td>
  </tr>
    <tr>
  <th> Setup </th>
    <td><ul><li> Запустите шифр на файле </li></ul></td>
    <td><ul><li> Установите параметр регекса на "{"</li><li> Вы должны знать, сколько раз рекурсив</li><li> Вы должны знать, что это Base64 до конца </li><li> Вы должны знать необходимо загрузить CyberChef (это раздутое JS-приложение)</li><li>Достаточно знать о CyberChef, чтобы создать этот трубопровод</li><li>Invert the match</li></ul></td>



<sub><b> Примечание</b> gifs могут загружаться в разное время, поэтому один из них может появиться значительно быстрее другого.</sub><br>
<sub> <b> Заметка о магии </b> CyberChef наиболее похожа на Ciphey - это Magic. Магия на этом входе мгновенно заканчивается неудачей, и происходит сбой. Единственный способ заставить CyberChef участвовать в конкурсе - определить его вручную. </sub>


Мы также протестировали CyberChef и Ciphey с файлом **6gb**. Ciphey взломал его за **5 минут и 54 секунды**. CyberChef разбился еще до того, как он запустился.





| **Имя** | ⚡ Ciphey ⚡ | | 🤡 Katana 🤡 | 🐢 CyberChef Magic 🐢 | |
| ------------------------------------------ | ---------- | ---------- | ------------------- |
| Расширенное средство проверки языка | ✅ | ❌ | ✅ | | |
| Поддерживает шифрование | ✅ | ✅ | | ❌ |
| Релизы, названные в честь мрачных тем 🌃 | ✅ | ❌ | ❌ | ❌ |
| Поддерживает хэши | ✅ | ✅ | | ❌ |
| Легко настроить | ✅ | ❌ ❌ | ✅ | | |
| Можно угадать, что что-то зашифровано с помощью | ✅ | | ❌ | ❌ | |
| Создано для хакеров хакерами | ✅ | ✅ | | ❌ | |

# 🎬 Начало работы

Если у вас проблемы с установкой Ciphey, [читайте это.](https://docs.ciphey.online/en/latest/install.html)

## ‼️ Важные ссылки (Документы, Руководство по установке, Поддержка дискорда)

| Руководство по установке | Документация | Разногласия |
| ------------------ | ------------- | ------- |
| 📖 [Руководство по установке](https://docs.ciphey.online/en/latest/install.html) | https://discord.ciphey.online [Документация](https://docs.ciphey.online) | 🦜 [Разногласия](📚)

## 🏃♀️Running Ciphey
Есть три способа запустить Ciphey.
1. Ввод файла `ciphey - зашифрованный.txt`
2. Безоговорочный ввод `ciphey -- "Зашифрованный ввод" `
3. Обычный способ `ciphey -t "Зашифрованный ввод" `

Gif показывает 3 способа запуска Ciphey](Pictures_for_README/3ways.gif)

Чтобы избавиться от индикаторов прогресса, таблицы вероятностей и всего шума, используйте тихий режим.

``ciphey -t "encrypted text here" -q``

Чтобы получить полный список аргументов, запустите `ciphey --help`.

### ⚗️ Импорт шифрования
Вы можете импортировать главный Ciphey и использовать его в своих собственных программах и коде. `из Ciphey.__main__ main` импорта`

# 🎪 Соавторы
Шифры были изобретены [Brandon Skerritt](https://github.com/brandonskerritt) в 2008 году и возрождены в 2019 году. Ciphey не был бы там, где он был сегодня, без [Cyclic3](https://github.com/Cyclic3) - президента UoL's Cyber Security Society.

Шифр восстановлен и воссоздан [Cyber Security Society](https://www.cybersoc.cf/) для использования в CTF. Если вы когда-либо были в Ливерпуле, подумайте о том, чтобы выступить с докладом или спонсировать наши мероприятия. Напишите нам по адресу `cybersecurity@society.liverpoolguild.org`, чтобы узнать больше 🤠

**Мажорный кредит** Джорджу Х за то, что он придумал, как мы можем использовать правильные алгоритмы, чтобы ускорить процесс поиска.
**особая благодарность** [varghalladesign](https://www.facebook.com/varghalladesign) за разработку логотипа. Посмотрите на их другие работы по дизайну!

## 🐕🦺 [Contributing](CONTRIBUTING.md)
Не бойтесь внести свой вклад! У нас есть много, много вещей, которые вы можете сделать, чтобы помочь. Каждое из них обозначено и легко объяснено примерами. Если вы пытаетесь внести свой вклад, но застряли, пометьте @brandonskerritt в выпуске GitHub ✨

Или присоединитесь к группе Разногласия и отправьте туда сообщение (ссылка в [contrib file](CONTRIBUTING.md)) или в верхней части этого README в качестве значка.

Пожалуйста, ознакомьтесь с [ПОДДЕРЖКА](CONTRIBUTING.md) для получения подробной информации о том, как внести свой вклад ✨
## 💰 Финансовые доноры
Взносы будут использованы не только для финансирования будущего Ciphey и его авторов, но и Общества кибербезопасности Ливерпульского университета.

GitHub не поддерживает "спонсорство этого проекта и мы будем равномерно распределять деньги", так что выбери ссылку, и мы разберемся с этим на нашем сайте 🥰

## ✨ Соавторы

Спасибо этим замечательным людям ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/Cyclic3"><img src="https://avatars1.githubusercontent.com/u/15613874?v=4" width="100px;" alt=""/><br/><sub><b>cyclic3</b></sub></a><br/><a href="#design-cyclic3" title="Design">🎨</a> <a href="#maintenance-cyclic3" title="Maintenance">🚧</a> <a href="https://github.com/Ciphey/Ciphey/commits?author=cyclic3" title="Code">💻</a> <a href="#ideas-cyclic3" title="Ideas, Planning, &amp; Feedback">🤔</a></td>
    <td align="center"><a href="https://skerritt.blog"><img src="https://avatars3.githubusercontent.com/u/10378052?v=4" width="100px;" alt=""/><br/><sub><b>Brandon</b></sub></a><br/><a href="#design-brandonskerritt" title="Design">🎨</a> <a href="#maintenance-brandonskerritt" title="Maintenance">🚧</a> <a href="https://github.com/Ciphey/Ciphey/commits?author=brandonskerritt" title="Code">💻</a> <a href="#ideas-brandonskerritt" title="Ideas, Planning, &amp; Feedback">🤔</a></td>
    <td align="center"><a href="https://github.com/michalani"><img src="https://avatars0.githubusercontent.com/u/27767884?v=4" width="100px;" alt=""/><br/><sub><b>michalani</b></sub></a><br/><a href="https://github.com/Ciphey/Ciphey/commits?author=michalani" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/ashb07"><img src="https://avatars2.githubusercontent.com/u/24845568?v=4" width="100px;" alt=""/><br/><sub><b>ashb07</b></sub></a><br/><a href="https://github.com/Ciphey/Ciphey/commits?author=ashb07" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/TheAlcanian"><img src="https://avatars3.githubusercontent.com/u/22127191?v=4" width="100px;" alt=""/><br/><sub><b>Shardion</b></sub></a><br/><a href="https://github.com/Ciphey/Ciphey/issues?q=author%3ATheAlcanian" title="Bug reports">🐛</a></td>
    <td align="center"><a href="https://github.com/Bryzizzle"><img src="https://avatars0.githubusercontent.com/u/57810197?v=4" width="100px;" alt=""/><br/><sub><b>Bryan</b></sub></a><br/><a href="#translation-Bryzizzle" title="Translation">🌍</a> <a href="https://github.com/Ciphey/Ciphey/commits?author=Bryzizzle" title="Documentation">📖</a></td>
    <td align="center"><a href="https://lukasgabriel.net"><img src="https://avatars0.githubusercontent.com/u/52338810?v=4" width="100px;" alt=""/><br/><sub><b>Lukas Gabriel</b></sub></a><br/><a href="https://github.com/Ciphey/Ciphey/commits?author=lukasgabriel" title="Code">💻</a> <a href="https://github.com/Ciphey/Ciphey/issues?q=author%3Alukasgabriel" title="Bug reports">🐛</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/DarshanBhoi"><img src="https://avatars2.githubusercontent.com/u/70128281?v=4" width="100px;" alt=""/><br/><sub><b>Darshan</b></sub></a><br/><a href="https://github.com/Ciphey/Ciphey/issues?q=author%3ADarshanBhoi" title="Bug reports">🐛</a></td>
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

Этот проект соответствует спецификации [все доноры] (https://github.com/all-contributors/all-contributors). Приветствуется любой вклад!
