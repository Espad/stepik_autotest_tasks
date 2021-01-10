# stepik_autotest_tasks
Repo for source code based on stepik testing automation cource

software version and env:
win10x64
python 3.6.8
pytest 6.2.1

# запуск теста
доступные параметры:
language, язык (en, ru, fr, sp), по дефолту es.
browser_name, тип браузера (хром, firefox), по дефолту - хром.


пример запуска, если запуск идет Pytest происходит в напрямую из директории с тестом:
pytest --language=fr

или pytest -s --language=fr, если требуется добавить в output вывод принтов из кода

или напрямую с указанием имени файла
pytest --language=es test_items.py

Также по умолчанию установлен в конце теста sleep в 30 секунд.
