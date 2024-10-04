1.1 Инкапсуляция - это когда мы прячем детали реализации и даем доступ к данным через специальные методы. Например:
class BankAccount:
 def __init__(self, balance = 0):
  self.balance = __balance

 def deposit(self, amount):
  if amount > 0:
   self.__balance += amount
 
 def get_balance(self):
  return self.__balance

1.2.Наследование - это когда один класс берет свойства и методы другого класса. Например:
class Animal:
 def speak(self):
  return "Animal speaks:

class Dog(Animal):
 def speak(self):
  return "WOOOF!!"
1.3.Полиморфизм - это возможность использовать один и тот же метод для разных обьектов
class Animal:
 def speak(self):
  return "Animal speaks:

class Dog(Animal):
 def speak(self):
  return "WOOOF!!"

class Cat(Animal):
 def speak(self):
  return "MEOW!!"

def animal_sound(animal):
 print(animal.speak())

2.1 Используя git checkout:
1) Найду нужный коммит с помощью git log
2) Использую git checkout (commit)
3) Использую git checkout main (Или любую другую ветку)

2.2 Используя git revert:
1)Найду нужный коммит с помощью git log
2) Выполню команду git revert(commit)

3.
def isPalindrome(str):
 str = str.lower().replace(" ", "")
 return s == s[::-1]

4. Его нет :D
