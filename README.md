# test_task
Глубокая отработка тонкостей языка Python







def openOrSenior(data):
    data=[data]
    char_list=[] # Переменная для хранения значений мастерства
    for i in range(-2,27): # Вилка мастерства игрока
        char_list.append(i)
        
    z=0
    i=(len(data)-z)
    write=[]
    while i<=len(data):
        if ((i[z][0]<=55) and (i[z][1]<=7)) and (char_list.count(i[z][1])>0):
            write.append('Молодой')
            z+=1
        else:
            write.append('Старик')
            z+=1
