# Курс "Функциональное программирование" на КТ

## Полезные ссылки

* [Страница с материалами курса](https://github.com/jagajaga/FP-Course-ITMO).
* [Табличка с баллами](https://docs.google.com/spreadsheets/d/1JywzmeE8XpcS4EoL0kuyiG2AKPWs-uEqcIhL0H-E8A4/edit#gid=0).
* [Style-guide](code-style.md).
* [Рекомендуемая конфигурация stylish-haskell](.stylish-haskell.yaml).
* [Рекомендации по настройке рабочего окружения](environment-setup.md).

## Домашние задания

* [ДЗ1](./hw1.md)
* [ДЗ2](./hw2.md)
* [ДЗ3](./hw3.md)
* [ДЗ4](./hw4.md)

## Как происходит обучение
В течение семестра раз в неделю Вам будут читаться лекции о языке Haskell. Посещение лекций не влияет на возможность получения зачета.

По прошествии нескольких тем Вам будут выдаваться домашние задания на эти темы. Обычно новое домашнее задание выдается после 3-4х лекций и содержит задачи на темы лекций. На решение каждого домашнего задания отводится 2-3 недели (сроки каждого конкретного выполнения ДЗ будут уточняться с объявлением заданий) с момента его выдачи.

## Коллоквиумы
В течение курса будет проведено 2-3 коллоквиума, на которых будет спрашиваться теоретический материал по всем пройденым с прошлого коллоквиума темам.

## Домашние задания

### Требования к выполнению
* Домашние задания необходимо выполнять **самостоятельно**. Под *самостоятельно* подразумевается, что студент написал код *сам*, без помощи в написании другим студентом, без копирования кода из Интернета и других источников, которые не были разрешены явно.
* Если окажется, что два или более студента списали друг у друга код, баллы за списанную задачу у них будут аннулированы вне зависимости от того, кто списал, а кто дал списать.
* Имейте в виду, что Ваше решение будет трактоваться как списанное, если Вы и другой студент независимо друг от друга скопировали код из некоторого публичного источника в Интернете (например, туториала и/или публичного github репозитория), и этот источник не был оговорен в задании как разрешенный.
* Если есть подозрения, что Вы списали решение задачи, преподаватель вправе попросить Вас объяснить код. В этом случае для зачета задачи необходимо полностью понимать и уметь объяснять его.

Решения задач, которые будут признаны как списанные, будут помечаться красным в таблице и аннулироваться.

Решения задач, которые подозреваются как списанные, будут помечаться желтым в таблице и аннулироваться до тех пор, пока студент не докажет, что он полностью понимает код.

### Формат сдачи

Для каждого домашнего задания будет создана assignment в github-classroom, для сдачи домашнего задания необходимо
запушить ваше решение *до* дедлайна.

### Проверка домашних заданий
#### Онлайн проверка
После того как дедлайн по домашнему заданию прошел, преподаватели в первую очередь проверяют Ваши решения на предмет списывания.
Те решения, которые окажутся списанными или подозреваются как списанные, аннулируются в таблице с особой пометкой.
Остальные же решения просматриваются преподавателями.

Прежде всего, чтобы Ваше решение было оценено, необходимо чтобы оно собиралось `stack build`.

Баллы за задачу могут снижаться за:
* невыполнение [style-guide](https://github.com/serokell/serokell-core/blob/master/serokell-style.md) - 0.5 балла за каждый тип стилистической ошибки;
* непроходящий тест - 0.5 балла за каждый тест;
* lts в stack.yaml отличающийся от требуемого - 0.5 балла;
* за "некрасивый код", написание велосипедов - 0.5-1 балл;
* за логические ошибки (например, за невыполнение законов тайпклассов для инстансов, и т.д.) - 0.5-1 балл;
* за невыполнения всех требований задачи (например, требуемой асимптотики, использования требуемых функций и т.д.) - от 0.5 до стоимости задачи баллов.

Имейте в виду, что Вы можете получить отрицательное количество баллов за задачу.

Баллы за задачу могут повышаться за:
* "красивый" код: обобщенные типы функций, грамотно спроектированная архитектура, использование функциональности языка, которая не разбиралась на лекциях и т.д.
* перевыполнение требований задачи: задача реализована с лучшей асимптотикой, чем требовалось, написаны тесты и т.д.

По умолчанию будет происходить **только** онлайн-проверка.

#### Офлайн-проверка
Если желающих сдавать домашние задания будет немного, то преподаватели вправе проводить офлайн-проверку: очную сдачу, при которой студент должен будет продемонстрировать код и ответить на возникающие по ходу проверки вопросы. Об офлайн-проверке задания будет сообщено заранее.

Офлайн-проверка предполагает все те же самые требования (решение выполнено самостоятельно, студент полностью понимает и может объяснить код и т.д.) и условия на снижения и повышения баллов.

## Дополнительные возможности заработать баллы

TBD

## Как получить зачет?

### Способ 1 (автомат).
Чтобы автоматом получить зачет, необходимо сдать все коллоквиумы и все _advanced_ версии домашних заданий.

### Способ 2 (устный экзамен).
Чтобы получить зачет данным способом, необходимо выполнить следующие условия:
* набрать не менее 60 баллов в течение семестра;
* сдать устный экзамен.


#### Устный экзамен
Да, предмет зачетный, но устный экзамен все равно придется сдать, чтобы получить зачет.

~Ребят, зря вы сюда поступили... Оно вас сожрет. Бегите отсюда...~

На экзамене Вы тянете билет, номер которого соответствует расказанной Вам лекции [отсюда](https://github.com/jagajaga/FP-Course-ITMO), у Вас есть 10-15 минут,
чтобы воспользоваться своими записями или ноутбуком, после этого Вы можете еще некоторое время готовиться, но уже без каких либо материалов.
