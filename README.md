# <h1 align="center"></h1>
<text xmlns="http://www.w3.org/2000/svg" x="585" y="140" transform="scale(.1)" fill="#fff" textLength="1070">API_YaTube_FINAL</text>
<h2 align="center">

<i>Проект api_yatube - это API социальной сети yatube.</i> 

<i><b>Функционал</i></b>
<blockquote>
☑ API реализован для моделей приложения posts: User, Post, Group, Comment, Follow; <br>
☑ Аутентификация пользователей по методу JWT-Authentication через Djoser; <br>
☑ UnSafe  методы доступны  для авторов постов/комментариев, а также для подписчиков на авторов;  <br>
☑ Safe методы доступны  для всех пользователей эндпоинтов posts, groups, comments. <br> 
☑ Доступ к эндпоинту follow предоставляется только аутентифицированным пользователям. <br> 
</blockquote>

<i><b>Технологии</i></b>
<blockquote>
☑ Python 3.9.10 <br> 
☑ Django REST framework
</blockquote>

<i><b>Запуск проекта в dev-режиме:</i></b><br> 
☑ Клонируйте проект с GitHub:</li>
    <blockquote>
      https://github.com/RostIiIslav/api_final_yatube.git
    </blockquote>  
☑ Создайте и активируйте виртуальное окружение:</li>
    <blockquote>
      python -m venv venv<br> 
      source venv/Scripts/activate 
    </blockquote>  
☑ Установите зависимости из файла requirements.txt
☑ Обновите pip!</li>
    <blockquote>
      pip install -r requirements.txt
      python -m pip install --upgrade pip
    </blockquote>
☑ Применяем миграции:</li>
    <blockquote>
      python yatube_api/manage.py makemigrations
      python yatube_api/manage.py migrate 
    </blockquote>


Автор: Рыманов Ростислав
<h2 id="your-badge" class="common__H2-sc-11baoah-1 fagqOB">I tried</h2>