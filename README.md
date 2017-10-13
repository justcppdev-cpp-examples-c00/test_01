# test_01

### 0.0.1
Дана строка, содержащая не больше 80 символов, нужно написать программу которая заменяет все пробелы на последовательность из трех символов `%20`. При этом программа должна работать без динамическего выделения памяти.
### Входные данные
Строка, возможно содержащая пробелы.

### Выходные данные
Преобразованная строка

### Примеры
#### входные данные
```
https://github.com/my nick name
```
### Входные данные
```
https://github.com/my%20nick%20name
```

### 0.0.2
Дана неубывающая посследовательность чисел, нужно найти 2 числа этой последовательности, сумма которых равна определенному числу.
### Входные данные
Во входных данных заданы 2 строки. Первая строка содержит 10 чисел разделенных пробелами. Вторая строка сожержит число.

### Выходные данные
Пара чисел последовательности сумма которых равна заданному числу или строка, сведетельствующая о возникновении ошибки ввода или отсутсвии такой пары.

### Примеры
#### входные данные
```
1 2 3 4 5 6 7 8 9 10
10
```
#### выходные данные
```
1 9
```
### Примеры
#### входные данные
```
1 2 3 4 5 6 7 8 9 10
100
```
#### выходные данные
```
There is no such pair of numbers.
```
#### входные данные
```
42 4 8 15 16 23
```
#### выходные данные
```
The input sequence must be non-decreasing.
```
#### входные данные
```
4 5 6 7 8
```
#### выходные данные
```
An error has occurred while reading the input sequence
```

### 0.0.3
Реализовать функцию слияния двух отсортированных массивов.
### Входные данные
Во входных данных заданы 2 неубывающие последовательности целых чисел из 10 элементов.

### Выходные данные
Полученную путем слияния последовательность целых чисел из 20 элементов или строка, сведетельствующая о возникновении ошибки ввода.

### Примеры
#### входные данные
```
1 3 5 7 9 11 13 15 17 19
0 2 4 6 8 10 12 14 16 18
```
#### выходные данные
```
0 1 2 3 4 5 6 7 8 9 10 11 12 13 14 15 16 17 18 19
```
#### входные данные
```
1 3 5 7 9 11 13 15 17 15
0 2 4 6 8 10 12 14 16 18
```
#### выходные данные
```
The input sequence must be non-decreasing.
```
#### входные данные
```
1 3 5 7 9 11 13 15 17
0 2 4 6 8 10 12 14 16 18
```
#### выходные данные
```
An error has occurred while reading the input sequence
```
### 0.0.4
Реализовать программу нахождения обратной матрицы размерами **2*****2**, используя метод Гаусса.
### Входные данные
Во входных данных заданы строки, следующего формата:
```
<число> <число> <число>
<число> <число> <число>
<число> <число> <число>
```
### Выходные данные
Обратная матрица или строка, сведетельствующая о возникновении ошибки ввода или об отсутсвии обратной матрицы.

### Примеры
#### входные данные
```
1 2 2
0 4 4
0 4 0
```
#### выходные данные
```
1 -0.5  0
0 0 0.25
0 0.25 -0.25
```
#### входные данные
```
1 2 2
0 4 0
0 4 0
```
#### выходные данные
```
There is no inverse matrix.
```
#### входные данные
```
1
0 4 0
0 4 0
```
#### выходные данные
```
An error has occured while reading input data.
```
