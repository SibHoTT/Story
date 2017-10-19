Розеттский камень -- http://math.ucr.edu/home/baez/rosetta.pdf

Понятия <<система типизации>> и <<теория типов>>.
Какая теория типов на самом деле лежит <<под капотом>> Coq.
(Сильная) нормализация и допустимые правила рерайтинга  
http://www4.di.uminho.pt/~mjf/pub/SFV-CIC-2up.pdf

Симплициальная модель ТТ элементарными конструкциями, Coquand:  
http://www.cse.chalmers.se/~coquand/decuniv.pdf

## Pentagons
https://en.m.wikipedia.org/wiki/Pentagonal_tiling

Исходная ссылка на популярный портал: https://www.quantamagazine.org/pentagon-tiling-proof-solves-century-old-math-problem-20170711/  
Найденная мной статья Рао: https://perso.ens-lyon.fr/michael.rao/publi/penta.pdf

# People
> Переход от правды ко лжи в этих системах зачастую непросто заметить. У человека формируется инстинктивное доверие к формирующемуся мыслепотоку, потом он начинает верить в его продолжение которое уже ложно, а потом ему трудно признаться себе в том что он поверил в ерунду и он начинает уже сам обманывать себя чтобы только не почувствовать себя в дураках» — интервью Владимира Воеводского: http://baaltii1.livejournal.com/198675.html

(кстати, интервьюёр https://youtu.be/hQLxmSgL0yI?t=26m33s — тоже весьма незаурядная личность).

> В результате все кончилось тем, что я придумал некоторую новую формализацию для марковских процессов, основанную на понятии системы путей. Статья получилась довольно длинная и техническая, и сейчас лежит недописанная. Я думаю к ней вернуться и дописать уже с помощью удобного компьютерного proof assistant.

>Сейчас есть целая область математике называемая теорией псевдо-случайных последовательностей. Это такие последовательности, которые на первый взгляд выглядят случайно, а на самом деле в высшей степени предсказуемы. У нас тут ими целая группа занимается. 🤔

# Coq

Судя по всему, крупнейший сборник успешных Coq-формализаций на GitHub. https://github.com/coq-contribs  
Среди прочего, сделаны:
* алгоритм Бухбергера
* кодирование Хаффмана
* критерий Поклингтона
* RSA
* сертифицированный решатель судоку
* теория категорий на базе ZFC
* CoC и разные другие системы типизации лямбда-исчисления
* MiniC и т.д.

Определение и анализ в Coq произвольных формальных языков и недетерминированных конечных автоматов, 2017: https://www.ps.uni-saarland.de/extras/RLR-Coq/index.php
На основной странице много и других разработок — http://www.ps.uni-saarland.de/Publications/list/all.html

Wave Equation Numerical Resolution: a
Comprehensive Mechanized Proof of a C Program — https://arxiv.org/pdf/1112.1795.pdf

Чешская магистерская работа по созданию адд-она Coq для IDE общего назначения MonoDevelop с реализацией автодополнения кода: https://dspace.cuni.cz/bitstream/handle/20.500.11956/39838/DPTX_2009_2__0_268455_0_90253.pdf?sequence=1

# Dependency Graphs
Automatic and Transparent Transfer of Theorems along Isomorphisms in the Coq Proof Assistant
отчасти заменяет унивалентность
https://arxiv.org/pdf/1505.05028.pdf  
Dependency Graphs & Machine Learning https://www.researchgate.net/publication/260716118_HoTT_formalisation_in_Coq_Dependency_Graphs_ML4PG

incredible.pm — крайне занятный открытый визуализатор и чекер доказательств в различных формальных системах, домашняя страница которого выполнена в виде интерактивной головоломки. Поддерживаются исчисление высказываний, предикатов и нестандартные логики, включая IPL и лямбда-исчисление с типами; пользователь может добавлять свои системы вывода, описывая их на специальном внутреннем языке. Основная публикация: https://www.joachim-breitner.de/publications/Incredible_ITP2016_preprint.pdf

# Verification

Вторая по мировому обороту криптовалюта и платформа распределённого исполнения интерактивных контрактов Ethereum, разработанная 21-летним российским программистом Виталиком Бутериным, объявила о начале поддержки формальной верификации кода контрактов в обширном ассортименте proof assistants, включая Coq: http://forum.ethereum.org/discussion/3779/formal-verification-for-solidity-contracts
Популярные источники про формализованный американский дрон: https://www.quantamagazine.org/formal-verification-creates-hacker-proof-code-20160920/

# CT

Ещё одно введение в категории с немалым вниманием к нюансам: http://www.logicmatters.net/resources/pdfs/GentleIntro.pdf
