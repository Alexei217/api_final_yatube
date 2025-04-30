# api_final
## Описание проекта
### Это платформа для общения, где пользователи могут:

- Через личный профиль публиковать свои записи (посты).

- Обсуждать публикации, оставляя комментарии под постами других участников.

- Подписываться на интересных авторов, чтобы следить за ними.

Проект построен по принципу социальной сети с упором на текстовое взаимодействие между пользователями.
### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/Alexei217/api_final_yatube.git
```

```
cd api_final_yatube
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv env
```

```
source env/bin/activate
```

Установить зависимости из файла requirements.txt:

```
python3 -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python3 manage.py migrate
```

Запустить проект:

```
python3 manage.py runserver
```

### Далее приведены примеры использования API:
- ### **Публикации:**
![1](images/post/1.jpg)
![2](images/post/2.jpg)
![3](images/post/3.jpg)
![4](images/post/4.jpg)
![5](images/post/5.jpg)
![6](images/post/6.jpg)

- ### **Комментрарии:**
![1](images/comment/1.jpg)
![2](images/comment/2.jpg)
![3](images/comment/3.jpg)
![4](images/comment/4.jpg)
![5](images/comment/5.jpg)
![6](images/comment/6.jpg)
  
- ### **Сообщества:**
![1](images/group/1.jpg)

- ### **Подписки:**
![1](images/follow/1.jpg)

- ### **JWT-токены:**
![1](images/jwt/1.jpg)
![2](images/jwt/1.jpg)
![3](images/jwt/1.jpg)
