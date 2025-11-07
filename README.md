# #  from tkinter import Label
# #
# # from tkinter import *
# #
# # root = Tk()
# # root.title('Окно регистрации')
# # root.geometry('1280x820')
# # root.resizable(width=False, height=False)
# # root.iconbitmap('icon.ico')
# #
# # root.config(bg='white')
# # root['bg'] = 'white'
# #
# # def click():
# #     print('привет')
# #
# # btn = Button(root,
# #               text = 'Кнопка',
# #               command = click,
# #               font = 'Arial 20',
# #               width = 10,
# #               height = 10
# #               font = ("Comic Sans MS", 20, 'bold'),
# #               bg = 'lime',
# #               activebackground = 'red',
# #               activeforeground = 'white',
# #               fg = 'brown',
# # )
# #
# # label = Label(root,
# #         text= 'Текст',
# #         font = ("Comic Sans MS", 20, 'bold'),
# #         bg = 'lime',
# #         fg = 'red',
# #         )
# # label.pack()
# #
# #
# #
# # img = PhotoImage(file='Logo.png')
# # l_logo = Label(root, image=img)
# # l_logo.pack()
# #
# #
# # btn.pack()
# # root.mainloop()
# #
# # from tkinter import *
# # from random import *
# #
# # root = Tk()
# # root.title("Камень ножницы бумага")
# # root.geometry('600x400')
# # root.resizable(width=False, height=False)
# # root['bg'] = 'black'
# #
# # def Whyknb():
# #     knb = ['Камень', 'Ножницы', 'Бумага']
# #     value = choice(knb)
# #     labelText.configure(text=value)
# #
# # labelText = Label(root, text = '', fg = 'white', font = ('arial', 20, 'bold'),  bg = 'black')
# # labelText.place(x = 200, y = 200)
# #
# # stone = Button(root,
# #                text = 'Камень',
# #                font = ('arial', 20, 'bold'),
# #                bg = 'white',
# #                command= Whyknb
# #                )
# #
# # stone.place(x = 50, y = 300)
# #
# # scissors = Button(root,
# #                text = 'Ножницы',
# #                font = ('arial', 20, 'bold'),
# #                bg = 'white',
# #                command= Whyknb
# #                )
# #
# # scissors.place(x = 220, y = 300)
# #
# # paper = Button(root,
# #                text = 'Бумага',
# #                font = ('arial', 20, 'bold'),
# #                bg = 'white',
# #                command= Whyknb
# #                )
# #
# # paper.place(x = 420, y = 300)
# #
# #
# # root.mainloop()
#
#
# # from tkinter import *
# #
# # root = Tk()
# # root.title("Текстовое поле")
# # root.geometry("1280x720")
# # root.resizable(width=0, height=0)
# #
# # root['bg'] = 'black'
# #
# # en = Entry(root)
# # en.pack()
# #
# # root.mainloop()
#
#
#
# def printData():
#     print(dataList1)
#     print(dataList2)
#
# def saveData():
#     data1 = entry1.get()
#     dataList1.appened(data)
#     entry1.delete(0, END)
#     data2 = entry2.get()
#     dataList2.appened(data2)
#     entry2.delete(0, END)
#
# labelR = Label(root, text="Регистрация", font=("Arial", 20), bg="white",)
# labelR.place(x=535, y=75)
#
# label1 = Label(root, text="Имя", font=("Arial"), bg="white")
# label1.place(x=425, y=125)
#
# entry1 = Entry(root, width=40)
# # entry1.insert(0, "Login")
# entry1.place(x=500, y=130)
#
# label2 = Label(root, text="Фамилия", font=("Arial"), bg="white")
# label2.place(x=385, y=150)
#
# entry2 = Entry(root, width=40)
# # entry2.insert(0, "Password")
# entry2.place(x=500, y=350)
#
#
# # butt1 = Button(root, text="Войти", font=("Arial"), background="white", command=saveData)
# # butt1.place(x=585, y=400)
#
# # butt2 = Button(root, text="Показать всех кто зарегистрированных", font=("Arial"), background="white")
# # butt2.place(x=430, y=600)
#
#
# root.mainloop()1





# from tkinter import *
#
# root = Tk()
# root.title("Окно регистрации")
# root.geometry("1400x700")
# root.resizable(width=0, height=0)
#
# # Создаем Canvas для линии
# canvas = Canvas(root, width=1400, height=700)
# canvas.place(x=0, y=0)
#
# # Рисуем вертикальную линию посередине
# canvas.create_line(700, 0, 700, 700, fill="black", width=2)
#
# # Функция Регистрации
#
#
#
# # Регистрация
# labelRegistration = Label(root, text="Регистрация", font="Arial")
# labelRegistration.place(x=200, y=110)
#
# # Поле ввода имени
# labelName = Label(root, text="Имя", font="Arial")
# labelName.place(x=100, y=150)
#
# entryName = Entry(root)
# entryName.place(x=150, y=156, width=220)
#
# # Поле ввода фамилии
# labelSurname = Label(root, text="Фамилия", font="Arial")
# labelSurname.place(x=57, y=175)
#
# entrySurname = Entry(root)
# entrySurname.place(x=150, y=181, width=220)
#
# # Поле ввода логина/почты
# labelLogin = Label(root, text="Логин/Почта", font="Arial")
# labelLogin.place(x=25, y=200)
#
# entryLogin = Entry(root)
# entryLogin.place(x=150, y=206, width=220)
#
# # Поле ввода пароля
# labelPassword = Label(root, text="Пароль", font="Arial")
# labelPassword.place(x=70, y=225)
#
# entryPassword = Entry(root, show="*")
# entryPassword.place(x=150, y=231, width=220)
#
# # Кнопка "Зарегистрироваться"
# ButtonRegister = Button(root, text="Зарегистрироваться", font="Arial")
# ButtonRegister.place(x=157, y=265)
#
# RegistretionDict = {
#     "Name": entryName.get(),
#     "Surname": entrySurname.get(),
#     "Login": entryLogin.get(),
#     "Password": entryPassword.get(),
#
# }
# print(RegistretionDict)
#
#
#
#
# root.mainloop()


# from tkinter import *
# from tkinter import ttk
#
# root = Tk()
# root.title("Окно регистрации")
# root.geometry("1400x700")
# root.resizable(width=0, height=0)
#
# # Canvas для линии
# canvas = Canvas(root, width=1400, height=700)
# canvas.place(x=0, y=0)
# canvas.create_line(700, 0, 700, 700, fill="black", width=2)
#
# # ----- Функция регистрации -----
# def register_user():
#     name = entryName.get()
#     surname = entrySurname.get()
#     login = entryLogin.get()
#     password = entryPassword.get()
#
#     tree.insert("", "end", values=(name, surname, login, password))
#
#     entryName.delete(0, END)
#     entrySurname.delete(0, END)
#     entryLogin.delete(0, END)
#     entryPassword.delete(0, END)
#
# #              "Регистрация"
# labelRegistration = Label(root, text="Регистрация", font="Arial 16 bold")
# labelRegistration.place(x=200, y=110)
# #               Ввод имени
# Label(root, text="Имя", font="Arial").place(x=100, y=150)
# entryName = Entry(root)
# entryName.place(x=150, y=156, width=220)
# #              Ввод Фамилии
# Label(root, text="Фамилия", font="Arial").place(x=57, y=175)
# entrySurname = Entry(root)
# entrySurname.place(x=150, y=181, width=220)
# #          Ввод почты или логина
# Label(root, text="Логин/Почта", font="Arial").place(x=25, y=200)
# entryLogin = Entry(root)
# entryLogin.place(x=150, y=206, width=220)
# #          Ввод Пароля (С шифровацией)
# Label(root, text="Пароль", font="Arial").place(x=70, y=225)
# entryPassword = Entry(root)#, show="*")
# entryPassword.place(x=150, y=231, width=220)
#
# Button(root, text="Зарегистрироваться", font="Arial", command=register_user).place(x=157, y=265)
#
# #        Таблица с данными пользователя
# labelUsers = Label(root, text="Зарегистрированные пользователи", font="Arial 16 bold")
# labelUsers.place(x=850, y=80)
#
# columns = ("Имя", "Фамилия", "Логин", "Пароль")
# tree = ttk.Treeview(root, columns=columns, show="headings", height=20)
# for col in columns:
#     tree.heading(col, text=col)
#     tree.column(col, width=150, anchor="center")
# tree.place(x=750, y=120)
#
# root.mainloop()



# from tkinter import *
# from openpyxl import Workbook, load_workbook
# import os
#
# # Создание/загрузка Excel файла
# filename = "данные.xlsx"
# if os.path.exists(filename):
#     wb = load_workbook(filename)
#     ws = wb.active
# else:
#     wb = Workbook()
#     ws = wb.active
#     ws.append(["Имя", "Фамилия", "Логин", "Пароль"])  # заголовки
#
# def save_to_excel():
#     name = entryName.get()
#     surname = entrySurname.get()
#     login = entryLogin.get()
#     password = entryPassword.get()
#
#     ws.append([name, surname, login, password])
#     wb.save(filename)
#
#     entryName.delete(0, END)
#     entrySurname.delete(0, END)
#     entryLogin.delete(0, END)
#     entryPassword.delete(0, END)
#
# root = Tk()
# root.title("Регистрация")
# root.geometry("400x300")
#
# Label(root, text="Имя").pack()
# entryName = Entry(root)
# entryName.pack()
#
# Label(root, text="Фамилия").pack()
# entrySurname = Entry(root)
# entrySurname.pack()
#
# Label(root, text="Логин").pack()
# entryLogin = Entry(root)
# entryLogin.pack()
#
# Label(root, text="Пароль").pack()
# entryPassword = Entry(root, show="*")
# entryPassword.pack()
#
# Button(root, text="Сохранить", command=save_to_excel).pack(pady=10)
#
# root.mainloop()


from tkinter import *
from tkinter import ttk
import csv
import os

root = Tk()
root.title("Окно регистрации")
root.geometry("1400x700")
root.resizable(width=0, height=0)

canvas = Canvas(root, width=1400, height=700)
canvas.place(x=0, y=0)
canvas.create_line(700, 0, 700, 700, fill="black", width=2)

# ---- Функция регистрации ----
def register_user():
    name = entryName.get()
    surname = entrySurname.get()
    login = entryLogin.get()
    password = entryPassword.get()

    if not (name and surname and login and password):
        return  # если что-то не введено, не сохраняем

    # Добавляем в таблицу
    tree.insert("", "end", values=(name, surname, login, password))

    # ---- Сохранение в CSV-файл ----
    file_exists = os.path.isfile("users.csv")
    with open("users.csv", "a", newline="", encoding="utf-8") as file:
        writer = csv.writer(file)
        if not file_exists:  # создаем заголовок, если файла нет
            writer.writerow(["Имя", "Фамилия", "Логин", "Пароль"])
        writer.writerow([name, surname, login, password])

    # очищаем поля
    entryName.delete(0, END)
    entrySurname.delete(0, END)
    entryLogin.delete(0, END)
    entryPassword.delete(0, END)

# ---- Интерфейс ----
Label(root, text="Регистрация", font="Arial 16 bold").place(x=200, y=110)
Label(root, text="Имя", font="Arial").place(x=100, y=150)
entryName = Entry(root)
entryName.place(x=150, y=156, width=220)

Label(root, text="Фамилия", font="Arial").place(x=57, y=175)
entrySurname = Entry(root)
entrySurname.place(x=150, y=181, width=220)

Label(root, text="Логин/Почта", font="Arial").place(x=25, y=200)
entryLogin = Entry(root)
entryLogin.place(x=150, y=206, width=220)

Label(root, text="Пароль", font="Arial").place(x=70, y=225)
entryPassword = Entry(root, show="*")
entryPassword.place(x=150, y=231, width=220)

Button(root, text="Зарегистрироваться", font="Arial", command=register_user).place(x=157, y=265)

Label(root, text="Зарегистрированные пользователи", font="Arial 16 bold").place(x=850, y=80)

columns = ("Имя", "Фамилия", "Логин", "Пароль")
tree = ttk.Treeview(root, columns=columns, show="headings", height=20)
for col in columns:
    tree.heading(col, text=col)
    tree.column(col, width=150, anchor="center")
tree.place(x=750, y=120)

# ----- Загрузка уже сохранённых данных ----
if os.path.isfile("users.csv"):
    with open("users.csv", "r", encoding="utf-8") as file:
        reader = csv.reader(file)
        next(reader, None)  # пропускаем заголовок
        for row in reader:
            tree.insert("", "end", values=row)
            
root.mainloop()
