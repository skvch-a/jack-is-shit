# Игра "Змейка" 
"Змейка" - игра, в которой нужно управлять змейкой, направлять её
в сторону еды - яблок и кормить, тем самым увеличивать её длину.

Для запуска игры необходимо в VMEmulator загрузить директорию vm 
и нажать "No animation". 

При запуске игры на экране отображены правила. Также на начальном экране
игры нужно ввести число от 1 до 99: оно определяет работу кода.
После этого заспавнится еда и змейка. 
Управление ведется с помощью клавиш-стрелок.
При проигрыше рестарт производится автоматически через 3 секунды.


# Код
В директории src - код на языке Jack;
В директории vm - код для виртуальной машины.

В файле "Block" происходит отрисовка единичных блоков (блок тела змейки, еда - яблоко);
В "Rand" находится рандомайзер на основе введенного пользователем числа;
В "Snake" - код движения, изменения положения змейки и длины;
В "View" - код начальной страницы, выяснения победы/поражения;
В "Main" - запуск всех классов выше.


# jack-is-shit
5 базовых правил:

Мама учила не ругаться матом, но жизнь научила не ругаться матом при маме.

Если тебе где-то не рады в рваных носках, то и в целых туда идти не стоит.

Работа не волк. Никто не волк. Только волк — волк.

Если закрыть глаза, становится темно.

Жи-ши пиши от души.


### для запуска
`.\JackCompiler.bat C:\programming\fiit\2sem\n2t\jack-is-shit`


# Создатели:
Волков Андрей, Еценков Данил, Соколова Татьяна