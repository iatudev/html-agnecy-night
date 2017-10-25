Работа в Git Bush c Windows <br><br><br>



1. Скачать Git Bush версии например 1.9.2 <br>
ссылка --> https://groups.google.com/forum/#!topic/msysgit/MsbWIJhmOsI<br>

 1.1. Далее выбираем в установке флажок "Advanced contex menu" (он есть в версии 1.9.2)<br>
2. Создаем папку на диске D, назовем например - "test"
3. Заходим в эту папку. Нажимаем в пустом месте этой папки правую кнопку мыши.<br>
    Там находим : "Git Init Here". Нажимаем на него.<br>
    также нажимаем - "Git Bash". Должна открыться консолька<br>
4. Набираем в консоли : "git pull origin master"<br>
5. Далее пишем : "git remote add origin https://github.com/iatudev/html-agnecy-night.git"<br>
6. и снова пишем: "git pull origin master". В папку должны скопироваться файлы с главной ветки Mастер в папку text<br>
7. Теперь нам нужно переключиться на собственную ветку.<br>
     "git checkout -b ИмяВашейВетки" <br>
8. Заменяем файлы в папке test на нужные.<br>
9. набираем в консоли например: git add index.php<br>
 Чтобы добавить в ветку все файлы пишем и (обязательно поставить точку!): "git add ."     <br>
10. Далее пишем коммит. <br>
	git commit -m 'ТутВашКомментарийВтакихКавычках'<br>
11.Отправим файлы на сервер: <br>
  git push origin ИмяВашейВетки<br>
12. Проверяем изменения в git hab<br>
13. Чтобы удалить ненужный файл пишем:<br>
	git rm --cached file.txt<br>
	git commit 'удаление файла'<br>
	git push origin ИмяВашейВетки<br>