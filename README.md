# Кейс. Анализ логов

<!-- 4 пары -->

<details> 
  <summary><h3>📚 Вводная информация</h3></summary>
  
  Перед началом выполнения кейса повторите следующий материал:

  * [Настройка изолированной среды проекта](https://github.com/pyshkovni/programming-technologies-1/blob/main/python_ide/README.md#%D0%BD%D0%B0%D1%81%D1%82%D1%80%D0%BE%D0%B9%D0%BA%D0%B0-%D1%81%D1%80%D0%B5%D0%B4%D1%8B-%D1%80%D0%B0%D0%B7%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BA%D0%B8-vs-code-git-%D0%B8-%D0%B8%D0%B7%D0%BE%D0%BB%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%BD%D0%B0%D1%8F-%D1%81%D1%80%D0%B5%D0%B4%D0%B0)
  * [Основы работы с Git и Github](https://disk.yandex.ru/d/D7r1TqNN3tzmHA)
  * Основы Python: типы данных, условный оператор, циклы
  * [Ветвление в Git. Pull request](https://www.youtube.com/watch?v=lCZrwR3JN8o&list=PLhJAIwZv9FEvdjGvi9FoM8NnXGTPItDet&index=3)
  * [Функции в Python](https://pyshkovni.github.io/python-base-course/part_1/functions/)
  * [Режимы открытия файлов](https://pyshkovni.github.io/python-base-course/part_2/open_csv_json/)

</details>

<details open> 
  <summary><h3>📝 Практика</h3></summary>
  
  * Имеется файл `logs/events.txt`, в котором записаны события и их время (ОK / NotOK).
  * Напишите программу, которая считывает файл и выводит число событий NotOK за каждую минуту.
  * Записывайте результаты в файл по мере работы скрипта, так как log-файлы обычно объемные и подсчитать всю статистику, а потом выгрузить ее в файл не получится!
  
</details>

<details open> 
  <summary><h3>❗ Задание</h3></summary>

  1. [Определите вариант проекта](https://docs.google.com/spreadsheets/d/1NA14YElz6Jfmcqx8Wv3Jef1nThxuUeKgljbuVWBeqfk/edit?usp=sharing)
  2. Изучить задание и выберите в папке `logs` файл с логами согласно вашему варианту:
     * `apache_log` – посчитать количество событий за каждый час
     * `nginx_log` – посчитать количество кодов 404 за каждую минуту
  3. Напишите скрипт для обработки данных согласно заданию. Для этого необходимо:
     * Сделать форк данного репозитория.
     * Написать функцию _(или несколько функций)_, которая будет выполнять поставленную задачу по анализу логов.
     * Функция должна принимать файл с данными и возвращать обработанный файл с выполненным заданием.
     * Данные необходимо взять из каталога `logs/`. Учитывайте это при указании пути до файла!
  4. Для того, чтобы сдать задание необходимо направить pull request на данный репозиторий в ветку `develop`

</details>
