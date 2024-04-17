Ссылка на [google disc](https://drive.google.com/drive/folders/12mtE2xNf3esCXRAVt7jmth4dUMhCmP_f)

Ссылка на [основной репозиторий](https://github.com/kwazart/mlops-demo/tree/master)

Все правки выполнялись из директории [**scripts**](https://github.com/kwazart/lab4/tree/master/scripts)

Последовательность команд:

1. ```git clone```  - клонирование репозитория
2. ```pip install pandas numpy catboost``` - установка зависимостей
3. ```cd scripts``` - переход в директорию с python-скриптами
4. ```python|python3 get_data.py``` - модификация данных #0 - получение данных датасета *titanic*
5. ```python|python3 delete_data.py``` - если данные нужно удалить *(опционально)*
6. ```python|python3 modificator_1.py``` - модификация данных #1 - заполнение колонки **Age** средним значением
7. ```python|python3 modificator_2.py``` - модификация данных #2 - применение *one-hot-encoding* для колонки **Sex**
8. ```dvc push``` - после каждой модификации данных - отправка на google disk через *dvc*

Пример файлов в хранилище google disk:
![image](https://github.com/kwazart/lab4/assets/46990077/cc84b369-d8a0-43ca-903d-97d131a1d391)
