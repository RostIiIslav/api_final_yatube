# <h2 align="center">
API_YaTube_FINAL
</h2>

<h2><i>Проект api_yatube - это API социальной сети yatube.</h2></i> 

<i><b>Функционал</i></b><br>
<p align="left">
☑ API реализован для моделей приложения posts: User, Post, Group, Comment, Follow; <br>
☑ Аутентификация пользователей по методу JWT-Authentication через Djoser; <br>
☑ UnSafe  методы доступны  для авторов постов/комментариев, а также для подписчиков на авторов;  <br>
☑ Safe методы доступны  для всех пользователей эндпоинтов posts, groups, comments. <br> 
☑ Доступ к эндпоинту follow предоставляется только аутентифицированным пользователям. <br> 
</p>
<br>

<i><b>Технологии</i></b><br>
<p align="left">
☑ Python 3.9.10 <br> 
☑ Django REST framework
</p>
<br>

<i><b>Запуск проекта в dev-режиме:</i></b><br>
<p align="left">
☑ Клонируйте проект с GitHub:</li>
</p>

      https://github.com/RostIiIslav/api_final_yatube.git
<p align="left">
☑ Создайте и активируйте виртуальное окружение:</li>
</p>

      python -m venv venv<br> 
      source venv/Scripts/activate 

<p align="left">
☑ Установите зависимости из файла requirements.txt<br> 
☑ Обновите pip!</li>
</p>

      pip install -r requirements.txt
      python -m pip install --upgrade pip

<p align="left">
☑ Применяем миграции:</li>
</p>

      python yatube_api/manage.py makemigrations
      python yatube_api/manage.py migrate 


<b>Автор:</b> Рыманов Ростислав