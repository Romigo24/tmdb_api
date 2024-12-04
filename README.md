## hello_api_TMDB
При запуске по кнопке `Run` скрипт использует вспомогательный файл `TDMB_helpers.py`, а точнее, функции которые в нем написаны,
этот файл вы можете взять в этом репозитории.
Скрипт выведет в терминал просьбу ввести ваш API-ключ с сайта [www.themoviedb.org](https://www.themoviedb.org/settings/api),
а на его основе составит личную ссылку. 

![Снимок экрана 2024-12-04 в 19 00 49](https://github.com/user-attachments/assets/80398a6c-9a2f-4619-a4a4-7fae3583cfea)

## search_in_db
Скрипт запускается по кнопке `Run`, и он просит ввести путь к базе данных. После он покажет все имеющиеся фильмы.
Для запуска скрипта требуется вспомогательный файл `tmdb_helpers.py`.
Необходимый файл с кодом вы можете взять в этом репозитории.

![Снимок экрана 2024-12-04 в 19 02 39](https://github.com/user-attachments/assets/ece4936b-fb64-4b70-aa29-693f937e5e14)

## make_own_db
Скрипт запускается по кнопке `Run` и предложит пользователю создать свою базу данных с фильмами.
Для этого потребуется вспомогательный файл `own_db_helpers.py`, который вы найдёте в этом репозитории,
и API-ключ который описан абзацем выше.

## find_similar
Скрипт порекомендует похожие фильмы на основе вашего запроса исходя из 4 параметров: относится ли фильм к какой-то коллекции фильмов,
оригинальный язык, бюджет фильма и жанра. Скрипт будет перебирать каждый параметр фильмов в базе данных по вашему запросу и выдаст рекомендованный фильм по рейтингу.