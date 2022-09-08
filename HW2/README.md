1. Выбрать ген  и добавить его в таблицу по ссылке выше. 
(Можно ориентироваться на Table 1 из https://www.ncbi.nlm.nih.gov/pmc/articles/PMC430263/ , гены субъединиц атфазы, полимераз, рибосомальных белков)
Минимальное число видов, необходимых для включения в дерево – 10. Большее число видов  15-20 приветствуется (интереснее смотреть)
Найти аминокислотные последовательности генов для нижеперечисленных видов и составить fasta-файл с последовательностями. Поставьте в начало названия гена строку с названием организма, чтобы организм отображался на листьях дерева. Например.
">Bacterium  AHI16583.1 ATP synthase alpha [Lactobacillus sp. HRROT3]"

Хорошо бы иметь представленность следующих видов - 

- Человек - human
- Обезьяна - primates
- Грызуны – mouse, rat
- копытное -   bovine
- сумчатое - marsupials
- пресмыкающиеся – snakes, lizards, turtles  
- птица 
- рыба 
- растение 
- fungi (Saccharomyces cerevisiae) – пекарские дрожжи (продаются сухими в пакетиках)
- архея - archaea
- бактерия –bacteria

Поиск гена производится на сайте NCBI в базе данных “protein”. Набиваете название гена в скобках. (ribosomal protein L1) + используйте кнопку Advanced для лучшего поиска. 

2. Произвести множественное выравнивание последовательностей алгоритмами ClustalW и Muscle  из пакета Mega. Сохранить два выравнивания в отдельные файлы. Написать, есть ли разница в выравнивании. 

3. В программе Mega построить филогенетическое дерево для аминокислотных последовательностей с бутсрэп-анализом для двух выравниваний – и методом ClustalW, и Muscle.  
- методом расстояний (UPGMA)
- методом расстояний (NJ)
- методом максимального правдоподобия 

В качестве отчетности представить
  файл в формате fasta c аминокислотными последовательностями
  файлы с двумя выравниваниями – clustalw и muscle
  отчет, оформленный в виде pdf или ptt:
  скриншот выравнивания для метода ClustalW и Muscle
  скриншоты деревьев, построенных (1) методом расстояний (UPGMA), (2) методом расстояний (NJ), методами максимального правдоподобия, на которых будут видны бутстрэп-значения, а также хорошо читаемые названия организмов.
  Выводы
Какой алгоритм выравнивания лучше сработал -  ClustalW или Muscle?
Одинаковая ли получилась топология деревьев при построении разными методами?
Одинаковые ли получились бутстрэп-значения?
Совпадают ли деревья, построенные по одному гену с принятыми деревьями видов?