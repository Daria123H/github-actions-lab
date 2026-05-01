# github-actions-lab

Було створено репозиторій на платформі GitHub:

        Назва: github-actions-lab
  
        Репозиторій є публічним
  
        У ньому зберігається весь вихідний код проєкту та конфігурації GitHub Actions

Після створення репозиторій був клонований на локальний комп’ютер за допомогою команди:

      git clone https://github.com/Daria123H/github-actions-lab.git

Було створено простий Python-файл app.py, який містить базові функції для тестування:

      додавання чисел
  
        множення чисел

Було реалізовано автоматичне тестування за допомогою pytest.

Файл workflow:

  .github/workflows/pytest.yml

Функціонал:

  запуск тестів при push та pull request
  
  автоматична перевірка коректності коду
Для перевірки стилю коду використано flake8.

Файл workflow:

  .github/workflows/lint.yml

Функціонал:

  перевірка відповідності PEP8
  
  виявлення помилок стилю

Реалізовано тестування коду на різних версіях Python.

 Файл workflow:

  .github/workflows/multi.yml

Використані версії:

  Python 3.8
  Python 3.9
  Python 3.10
  Python 3.11

Функціонал:

  перевірка сумісності коду з різними версіями Python

Реалізовано автоматичну збірку Docker-образу.

Файл:

  .github/workflows/docker.yml

Dockerfile містить:

  базовий образ Python 3.10
  
  встановлення залежностей
  
  запуск програми

Реалізовано автоматичну генерацію HTML-звіту тестування.

Файл workflow:

  .github/workflows/report.yml

Функціонал:

  запуск тестів із генерацією HTML-звіту
  
  завантаження звіту як artifact у GitHub Actions

# ![Результат](https://github.com/Daria123H/github-actions-lab/blob/cae18179687d69d2abc0dccc3c71fabb8075e31b/5.png))
