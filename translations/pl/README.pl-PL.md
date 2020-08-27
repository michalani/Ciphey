<p align="center">
Tłumaczenia <br>
<a href=https://github.com/Ciphey/Ciphey/tree/master/translations/id/README.md>🇮🇩 ID</a>
 <br><br>
➡️ 
<a href="https://docs.ciphey.online">Dokumentacja</a> |
<a href="https://discord.ciphey.online">Niezgoda</a> |
 <a href="https://docs.ciphey.online/en/latest/install.html">Instrukcja instalacji </a>
 ⬅️

<br>
  <img src="../..Pictures_for_README/binoculars.png" alt="Ciphey">
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
W pełni zautomatyzowane narzędzie deszyfrujące wykorzystujące przetwarzanie języka naturalnego i sztuczną inteligencję, wraz z pewnym zdrowym rozsądkiem.
</p>
<hr>

## [Instrukcja instalacji](https://docs.ciphey.online/en/latest/install.html)

| <p align="center"><a href="https://pypi.org/project/ciphey">🐍 Python (Universal) </a></p> |
| ----------------------------------------------------------------------------------------- |
| <p align="center"><img src="Pictures_for_README/python.png"/></p> | |
| `python3 -m pip install ciphey --upgrade` | 

| Linux | Mac OS | Windows |

| ![Przepływu pracy GitHub](https://img.shields.io/github/workflow/status/ciphey/ciphey/Python%20application?label=Linux) |![Status przepływu pracy GitHub](https://img.shields.io/github/workflow/status/ciphey/ciphey/Python%20application?label=Mac%20OS) | ![Status przepływu pracy GitHub](https://img.shields.io/github/workflow/status/ciphey/ciphey/Python%20application?label=Windows) |
  

<hr>

# 🤔 Co to jest?
Ciphey jest automatycznym narzędziem rozszyfrowującym. Wprowadzić zaszyfrowany tekst, odzyskać zaszyfrowany tekst.
&gt; "Jaki rodzaj szyfrowania?"

O to chodzi. Nikt nie wie, po prostu wiesz że to jest zaszyfrowane. Ciphey rozgryzie to dla ciebie.

Ciphey może rozwiązać większość rzeczy w 3 sekundy lub mniej.

<p align="center" href="https://asciinema.org/a/336257">
  <img src="Pictures_for_README/index.gif" alt="Ciphey demo">
</p>

**Część techniczna.** Szyfr wykorzystuje niestandardowo zbudowany moduł sztucznej inteligencji (_AuSearch_) z _Cipher Detection Interface_ w celu przybliżenia tego, co jest szyfrowane. A następnie wbudowany niestandardowy, konfigurowalny moduł przetwarzania języka naturalnego _Language Checker Interface_, który może wykryć, kiedy dany tekst staje się zwykłym tekstem.

A to tylko wierzchołek góry lodowej. Aby uzyskać pełne wyjaśnienie techniczne, sprawdź naszą [dokumentację](https://docs.ciphey.online/en/latest).

# ✨ Cechy

- **20 obsługiwane szyfry** takie jak kodowanie (binarne, bazowe64) i normalne szyfry takie jak szyfr Cezara, Transpozycja i inne. **[Pełna lista znajduje się tutaj](https://docs.ciphey.online/en/latest/ciphers.html)**
- **Custom Built Artificjalna Inteligencja z rozszerzym wyszukiwaniem (AuSearch) ci odpowie "jakiej encrypcji uzyto?" **Wynika z tego, że rozszyfrowanie trwa mniej niż 3 sekundy 
- **Posiada moduł przetwarzania języka naturalnego** Szyfr może określić, czy coś jest prostym tekstem, czy nie. Ma niewiarygodnie wysoką dokładność, a także jest szybki.
- **Obsługa wielu języków**, obecnie tylko niemiecki i angielski (z wariantami AU, UK, CAN, USA).
- **Wspiera szyfry** Których alternatywy, takie jak CyberChef Magic, nie siegaja.
- **[Zbudowane uzywajac C++](https://github.com/Ciphey/CipheyCore)** Błyskotliwie szybkie analizy!

# 🔭 Ciphey vs CyberChef

## 🔁 Baza64 Zakodowana 42 razy

<table>
  <tr>
  <th>Nazwy</th>
    <th>⚡ Ciphey ⚡ </th>
    <th>🐢 CyberChef 🐢</th>
  </tr>
  <tr>
  <th>Gif</th>
    <td><img src="Pictures_for_README/ciphey_gooder_cyberchef.gif" alt="The guy she tells you not to worry about"></td>
    <td><img src="Pictures_for_README/not_dying.gif" alt="You"></td>
  </tr>
  <tr>
  <th>Czas</th>
    <td>2 sekundy</td>
    <td>6 sekund</td>
  </tr>
    <tr>
  <th>Ustawienia</th>
    <td><ul><li>Uruchom cyphey w pliku</li></ul></td>
    <td><ul><li>Ustaw regex param na "{"</li><li>Musisz wiedzieć ile razy powtórzyć</li><li>Musisz wiedzieć, że to Baza64 aż do końca</li><li>Ty trzeba załadować CyberChef (jest to nadmuchana aplikacja JS)</li><li>Wiedzieć wystarczająco dużo o CyberChef, aby utworzyć ten potok</li><li>Odwróć dopasowanie</li></ul></td>
  </tr>
</table>


<sub><b>Uwaga</b> gif może się ładować w różnym czasie, więc jeden może się pojawić znacznie szybciej niż inny.</sub><br>
<sub><b>Uwaga na temat magii </b>Najbardziej podobną cechą CyberChefa do Cipheya jest Magia. Magia zawiedzie natychmiast na tym wejściu i zawiedzie się. Jedynym sposobem na zmuszenie CyberChefa do rywalizacji było ręczne zdefiniowanie jej.</sub>


Przetestowaliśmy również CyberChef i Ciphey za pomocą pliku **6gb**. Ciphey złamał go w ciągu **5 minut i 54 sekund**. CyberChef rozbił się zanim jeszcze się zaczął.



## 📊 Ciphey vs Katana vs CyberChef Magic



| **Name**                                   | ⚡ Ciphey ⚡ | 🤡 Katana 🤡 | 🐢 CyberChef Magic 🐢 |
| ------------------------------------------ | ---------- | ---------- | ------------------- |
| Zaawansowany Sprawdzacz Języków              | ✅          | ❌          | ✅            |
| Dziala z enkrypcja                           | ✅          | ✅          | ❌            |
| Publikacje nazwane po tematach Dystopian 🌃 | ✅          | ❌          | ❌            |
| Dziala z hashami                             | ✅          | ✅          | ❌            |
| Latwe do ustawienia                          | ✅          | ❌          | ✅            |
| Jest w stanie zgadnac co jest zaszyfrowane   | ✅          | ❌          | ❌            |
| Stworzone dla hakerów przez hakerów          | ✅          | ✅          | ❌            |


# 🎬 Jak Zaczac

Jeśli masz problemy z instalacją Ciphey, [przeczytaj to.](https://docs.ciphey.online/en/latest/install.html)

## ‼️ Ważne odnośniki (Dokumenty, instrukcja instalacji, pomoc techniczna dotycząca dysordów)

| Instrukcja instalacji | Dokumentacja | Niezgoda |
| ------------------ | ------------- | ------- |
| 📖 [Przewodnik instalacji](https://docs.ciphey.online/en/latest/install.html) | https://discord.ciphey.online [Dokumentacja](https://docs.ciphey.online) | 🦜 [Niezgoda](📚)

## 🏃♀Wlaczanie Ciphey
Są 3 sposoby, aby uruchomić Ciphey.
1. Uzyc na pliku `ciphey - encrypted.txt`
2. Niekwalifikowane wejście ``ciphey -- "Encrypted input"`
3. Normalny sposób `ciphey -t "Encrypted input"`

[Gif pokazujący 3 sposoby na uruchomienie Ciphey](Pictures_for_README/3ways.gif)

Aby pozbyć się pasków postępu, tabeli prawdopodobieństwa i całego hałasu użyj trybu cichego.

```ciphey -t "encrypted text here" -q```

Aby uzyskać pełną listę argumentów, uruchom `ciphey --help`.

### ⚗️ Importowanie szyfrów
Możesz zaimportować główny Ciphey i użyć go w swoich własnych programach i kodzie. Z Ciphey.__główny import główny`

# 🎪 Współtwórcy
Ciphey został wynaleziony przez [Brandona Skerritta](https://github.com/brandonskerritt) w 2008 roku, a ożywiony w 2019 roku. Ciphey nie byłby tam, gdzie jest dziś, gdyby nie [Cyclic3](https://github.com/Cyclic3) - prezes UoL's Cyber Security Society.

Ciphey został ożywiony i odtworzony przez [Cyber Security Society](https://www.cybersoc.cf/) do wykorzystania w CTF-ach. Jeśli kiedykolwiek byłeś w Liverpoolu, rozważ przeprowadzenie rozmowy lub sponsorowanie naszych wydarzeń. Wyślij nam e-mail na adres `cybersecurity@society.liverpoolguild.org` aby dowiedzieć się więcej 🤠

**Major Credit** do George'a H'a za wypracowanie odpowiednich algorytmów przyspieszających proces wyszukiwania.
**Specjalne podziękowania** dla [varghalladesign](https://www.facebook.com/varghalladesign) za zaprojektowanie logo. Sprawdź ich inne prace projektowe!

## 🐕🦺 [Contributing](CONTRIBUTING.md)
Nie bójcie się przyczyniać! Mamy wiele, wiele rzeczy, które możesz zrobić, aby pomóc. Każda z nich jest opatrzona etykietą i łatwo wyjaśniona przykładami. Jeśli próbujesz wnieść swój wkład, ale utknąłeś, oznacz @brandonskerritt w wydaniu GitHub ✨

Alternatywnie, dołącz do grupy Discord i wyślij tam wiadomość (link w pliku [contrib file](CONTRIBUTING.md)) lub na górze tego CZYTNIKA jako identyfikator.

Prosimy o zapoznanie się z [plik zawierający wkład] (CONTRIBUTING.md) w celu uzyskania dokładnych informacji na temat sposobu przekazywania wkładu ✨
## 💰 Financial Contributors
Składki zostaną przeznaczone nie tylko na finansowanie przyszłości Ciphey i jego autorów, ale także Cyber Security Society na Uniwersytecie w Liverpoolu.

GitHub nie wspiera "sponsoruj ten projekt, a my będziemy równomiernie rozdzielać pieniądze", więc wybierz link, a my zajmiemy się tym na końcu 🥰

## ✨ Współtwórcy

Dziękuję tym wspaniałym ludziom ([klucz emoji](https://allcontributors.org/docs/en/emoji-key)):

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

Ten projekt jest zgodny ze specyfikacją [wszyscy współpracownicy] (https://github.com/all-contributors/all-contributors). Każdy wkład jest mile widziany!
