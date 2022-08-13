
# **ИНСТРУКЦИЯ ПО РАБОТЕ С GIT**
____________________________________________________________________________________________________

> ## После установки необходимо представиться ситеме контроля версий. Это нужно выполнить только один раз, и GIT запомнит Вас. Для этого нужно ввести в терминале 2 команды: 

*   # git config --global user.name "Твоё имя латинскими буквами"
*   # git config --global user.name "your@email.com"
<br/><br/>

## КОМАНДЫ
* # `git --version` - указывает актуальную версию GIT
<a href="https://imgbb.com/"><img src="https://i.ibb.co/RQFhd5m/version.jpg" alt="version" border="0"></a>
<br/><br/>

* # `git init`      - указываем папку в которой необходимо отследить изменения (Создаётся скрытая папка .git)
<a href="https://ibb.co/8cfGtmp"><img src="https://i.ibb.co/3zjVQTq/init.jpg" alt="init" border="0"></a>
<br/><br/>

* # `git add` - добавляет содержимое для последующего commit
>Клавиша TAB - позволяет быстро переходить из разных директорий. Пример: gitt add .\hello_world.md
<a href="https://ibb.co/4F6hdQ6"><img src="https://i.ibb.co/wd95sv9/add.jpg" alt="add" border="0"></a>
<br/><br/>

* # `git commit` - команда фиксирует и сохраняет данные в индексе с помощью git add
>Пример: git commit -m "YOUR COMMENT"
 (Комментарий необходим для того, чтобы все коллеги участвующие в проекте могли иметь маркер деятельности)
 <a href="https://ibb.co/Bj93NGf"><img src="https://i.ibb.co/WFL5t0H/commit.jpg" alt="commit" border="0"></a>
  <br/><br/>

* # `git log` - показывает журнал изменений
>Укажет все версии файла, позволяет увидеть сколько было изменений и комментарии к сохранениям.

<a href="https://ibb.co/4VdrsKx"><img src="https://i.ibb.co/z4Jv8Qw/log.jpg" alt="log" border="0"></a><br /><a target='_blank' href='https://imgbb.com/'></a><br />
<br/><br/>

* # `git checkout` - команда позволяет переключаться меджу версиями
> Для работы необходиомо указать интересующий коммит, и выбрать тот, в котром желаем остаться. При момощи команды git checkout master
<br/><br/>

<a href="https://imgbb.com/"><img src="https://i.ibb.co/2SM2Dc0/checkout.jpg" alt="checkout" border="0"></a><br /><a target='_blank' href='https://imgbb.com/'></a><br />

<br/><br/>
* # `git diff` - показ разницы между текущим файлом и сохраненным
>  Перед переключением версии файла в GIT используй команду git log, чтобы увидеть все сохранения

<a href="https://imgbb.com/"><img src="https://i.ibb.co/fCVqtX1/diff.jpg" alt="diff" border="0"></a>
<br/><br/>

* # `git branch` - команда выводит все ветки репозитория
<a href="https://ibb.co/Sfs37Z9"><img src="https://i.ibb.co/tLmJP1W/branch.jpg" alt="branch" border="0"></a>
<br/><br/>

* # `git branch (new branch name)` - команда создаёт новую ветку с именем 
<a href="https://ibb.co/GWTFvdD"><img src="https://i.ibb.co/Cb2W5wy/git-branch-name.jpg" alt="git-branch-name" border="0"></a>
<br/><br/>

* # `git branch -d (branch name)` - команда удаляет ненужную ветку
<a href="https://ibb.co/gzNkHRP"><img src="https://i.ibb.co/72Ps81R/git-branch-d.jpg" alt="git-branch-d" border="0"></a>
 <br/><br/>
 
* # `git log --graph` - команда выводит список commit в виде древа
<a href="https://ibb.co/Dfd7YWZ"><img src="https://i.ibb.co/k2ZhJBt/git-log-graph.jpg" alt="git-log-graph" border="0"></a>
 <br/><br/>

 * # `git merge (branch name)` - слияние ветки с текущей веткой (нужно вызывать оттуда, куда хотите подгрузить информацию) 
 <a href="https://ibb.co/3BqvtyZ"><img src="https://i.ibb.co/J54qXRJ/git-merge-branch-name.jpg" alt="git-merge-branch-name" border="0"></a>

 * # `.gitignore` - команда для игнорирования файлов и информации (создается в отдельной директории в папке)
 <br/><br/>

 * # `git clone` - команда позволяет создать клон внещнего репозитория на ПК
 <a href="https://ibb.co/QKMnCKr"><img src="https://i.ibb.co/d5D6L5G/git-clone.jpg" alt="git-clone" border="0"></a>
 <br/><br/>

 * # `git pull` - команда позволяет скачать всё из текущего репозитория и автоматически сделать merge с нашей версией
 <a href="https://ibb.co/HnWV3rR"><img src="https://i.ibb.co/MMYsQRK/git-pull.jpg" alt="git-pull" border="0"></a>  <br/><br/>

 * # `git push` - команда позволяет отправить нашу весрию репозитория (требуется авторизация на внешнем репозитории)
 <a href="https://ibb.co/BsZ7b4Y"><img src="https://i.ibb.co/NYjk51G/git-push.jpg" alt="git-push" border="0"></a>
  <br/><br/>

 * # `git commit --amend` -комнда для корректировки commit(в случае если допустили опечатку или ошибку)
 <br/><br/>

 ## КАК ВЫПОЛНИТЬ PULL REQUEST?

# `1. Делаем форк репозитория`
# `2. Делаем clone своей версии репозитория`
# `3. Создаём новую ветку и в нее вносим свои изменения`
# `4. Фиксируем изменения (делаем commit)`
# `5. Отправляем свою версию на свой GitHub`
# `6. На сайте GitHub нажимаем кнопку pull reuest`
 <br/><br/>
 
### ВСПОМОГАТЕЛЬНЫЕ КОМАНДЫ ТЕРМИНАЛА

* # `q` - выход
* # `CTRL + S` - сохраннение информации перед git unit
* # `CTRL + Z` - отмена предыдущего ввода
* # `clear` - отчистить командную строку

# **ИНТЕРЕСНЫЕ ССЫЛКИ И СТАТЬИ ПО НАСТРОЙКЕ GIT**

[GitHub: настройка и первая публикация проекта](#https://gb.ru/posts/github-nastrojka-i-pervaya-publikaciya-proekta)

[Как устроен и работает GitHub](#https://gb.ru/posts/kak-ustroen-i-rabotaet-github)

[GitHub: работа с ветками и коммитами](#https://gb.ru/posts/github-rabota-s-vetkami-i-kommitami)

[Установщик](#https://githowto.com/ru)

[Сcылка на бесплатный базовый курс GIT](#https://gb.ru/chapters/7831)

