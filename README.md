import sys
import time

txt = 'Привет! Меня зовут МарКусь. Я создан начинающим разработчиком.\nДавай познакомимся!\n'
for i in txt:  # этот цикл будет брать по 1 буковке из тхт
    time.sleep(0.01)
    print(i, end='', flush=True)
time.sleep(1)
name = input('Как тебя зовут? Имя-')
txt = f'Очень приятно {name}.\nЯ тебе задам вопросы а ты постарайся на них ответить. В каждой теме будет по пять вопросов. Если ты ответишь хоть на один вопрос не правильно то тебе придется делать всё заново. Хорошо?\n'
for i in txt:  # этот цикл будет брать по 1 буковке из тхт
    time.sleep(0.01)
    print(i, end='', flush=True)
y_n = int(input('1-Да 2-Нет Число-'))
if y_n == 1:
    print('Приступаем!')
elif y_n == 2:
    print('Увидимся!'), sys.exit()
txt = 'Хорошо, а теперь давай выберем тему для вопросов\n'
for i in txt:  # этот цикл будет брать по 1 буковке из тхт
    time.sleep(0.01)
    print(i, end='', flush=True)
theme = int(input('1-Игры 2-Еда 3-Путешествия Число-'))
if theme == 1:
    txt = 'Хорошо. Игры так игры как хочешь.\nИтак первый вопрос.\nКто создал GTA 5'
    for i in txt:  # этот цикл будет брать по 1 буковке из тхт
        time.sleep(0.01)
        print(i, end='', flush=True)
    ans_games_1 = int(input('1-Mojang 2-Microsoft 3-Rockstar'))
    if ans_games_1 == 1:
        print('Неправильно'), sys.exit()
    elif ans_games_1 == 2:
        print('Неправильно!'), sys.exit()
    elif ans_games_1 == 3:
        print('Правильно')
    txt = '\nМолодец.\nВторой вопрос.\nКто создал GTA 5'
    for i in txt:  # этот цикл будет брать по 1 буковке из тхт
        time.sleep(0.01)
        print(i, end='', flush=True)

NOT WORKING!!!!!!!!!!

