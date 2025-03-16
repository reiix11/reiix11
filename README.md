<h2 align="center">About Me</h2>

<p align="center">
  <img height="25" src="https://api.visitorbadge.io/api/VisitorHit?user=reiix11&countColor=%234a12ba" alt="Profile Views"/>
  <img height="25" src="https://img.shields.io/github/followers/reiix11?color=4a12ba&style=for-the-badge&logo=github&label=Follow" alt="Followers"/>
  <img height="25" src="https://img.shields.io/github/stars/reiix11?color=4a12ba&style=for-the-badge&logo=github&label=Stars" alt="Stars"/>
</p>

<p align="center">
  <a href="https://t.me/reiix11" target="_blank">
    <img src="https://img.shields.io/badge/Telegram-Contact%20Me-4a12ba?style=for-the-badge&logo=telegram&logoColor=blue" alt="Telegram"/>
  </a>
</p>

```py
from typing import NamedTuple

class Contact(NamedTuple):
    telegram: str
    discord: str
    email: str

class Attributes:

    @staticmethod
    def contact() -> Contact:
        return Contact(telegram='@reiix11', discord=None, email=None)

    @staticmethod
    def life() -> tuple:
        name = 'Rei'
        age  = 16
        lang = ['Albanian', 'English']

        return name, age, lang

    @staticmethod
    def coding() -> tuple:
        languages    = ['Python', 'Golang']
        specialities = ['Automation', 'Web Scraping', 'Skidding']
        text_editor  = ['Visual Studio Code', 'PyCharm']

        return languages, specialities, text_editor
```

<h2 align="center">Stats</h2>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/?username=reiix11&title_color=674fc9&text_color=9f9f9f&show_icons=true&bg_color=00000000&hide_border=true&icon_color=674fc9&hide_title=false&count_private=false" />
</p>
