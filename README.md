```python
class Rei:
    @staticmethod
    def life() -> tuple:
        age = 17
        nationality = 'albanian'
        languages   = {
            'known'    : ['albanian', 'english'],
            'learning' : ['german']
        }
        return age, nationality, languages

    @staticmethod
    def coding() -> tuple:
        langs = {
            1: 'python',
            2: 'golang', # learning
        }
        skills = ['automation', 'web scraping']
        return langs, skills

    @staticmethod
    def contact() -> str:
        telegram = 't.me/reiix11'
        return telegram
```
