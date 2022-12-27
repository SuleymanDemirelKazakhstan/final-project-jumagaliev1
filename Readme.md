## :sparkles: Describe your project

Project SymSpell based Web Application. You can upload kazakh speaken history chat with JSON format and you can see correction to corresponding tables.

**Stack**: [django](https://www.djangoproject.com), [symspell](https://github.com/wolfgarbe/SymSpell)

Data set taken from [here](https://github.com/hermitdave/FrequencyWords) approximately ~5000 words.
### Format 
Frequency lists are on the `{word}{space}{numer_of_occurences_in_corpus}`:
```
мен 364
ол 222
жоқ 165
...
```
## :rocket: Installation
This project requires Python 3.7+.
1. Clone the repository
```sh
   $ git clone https://github.com/jumagaliev1/kazakh-lang-corrector.git
```

2. Install django
```sh
  $ pip install django
```

3. Run the live server
```sh
  $ python manage.py runserver
```
## :page_facing_up: Links

https://github.com/jumagaliev1/kazakh-lang-corrector

Dataset: https://github.com/hermitdave/FrequencyWords
