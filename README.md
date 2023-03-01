# hse_hw2_chip


Колаб: 
https://colab.research.google.com/drive/17GpRv62oer1UHD_D-PjlRrGWwsjsrvKP?usp=sharing

Выбрал клеточную линию DND-41, гистоновую клетку H4K20me1.

Чтения достаточно качественные, в целом можно было и не подрезать, но всё-таки решил сверить - дропнулись до 5%. 

#### Первая реплика - ENCFF000ARF, до и после подрезания:
<img width="400" alt="image" src="report_ARF_1.png"> <img width="400" alt="image" src="report_ARF_trimmed_1.png">

<img width="400" alt="image" src="report_ARF_2.png"> <img width="400" alt="image" src="report_ARF_trimmed_2.png">


#### Вторая реплика - ENCFF000ARE, до и после подрезания:
<img width="400" alt="image" src="report_ARE_1.png"> <img width="400" alt="image" src="report_ARE_trimmed_1.png">

<img width="400" alt="image" src="report_ARE_2.png"> <img width="400" alt="image" src="report_ARE_trimmed_2.png">



#### Контроль - ENCFF000AOF, до и после подрезания:
<img width="400" alt="image" src="report_AOF_1.png"> <img width="400" alt="image" src="report_AOF_trimmed_1.png">

<img width="400" alt="image" src="report_AOF_2.png"> <img width="400" alt="image" src="report_AOF_trimmed_2.png">



### Статистика по выравниванию на 21-ю хромосому:
<img width="800" alt="image" src="firefox_nVfKuEuZ6e.png">

Процент выравниваний низкий, так как выравнивались только на одну хромосому человека.


### Диаграммы Эйлера-Венна

Пересечения первой реплики и ENCODE:

<img width="400" alt="image" src="venn_ARF_YAA.png"> <img width="400" alt="image" src="venn_YAA_ARF.png">

Пересечение второй реплики и ENCODE:

<img width="400" alt="image" src="venn_ARE_YAA.png"> <img width="400" alt="image" src="venn_YAA_ARE.png">

Пересечений достаточно мало, так как, опять-таки, выравнивались на одну хромосому - в ENCODE составлялись пики для всех.

У файлов может быть разное количество участков, поэтому в зависимости от порядка пересечение будет меньше или больше.

Сорри, что все файлы в корень репозитория, нет времени загружать с компа, на сайте не нашёл :(
