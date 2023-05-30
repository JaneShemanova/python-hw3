# python-hw3

Задача 22:
n=(int(input("Введите число N элементов: ")))
num_list_1=[]
for i in range(n):
    num = int(input("Введите num "))
m=(int(input("Введите число M элементов: ")))
num_list_2 = []
for i in range(m):
    num = int(input("Введите num "))
   num_list3 = num_list_1+num_list_2
print(num_list3)
for i in num_list3:
    if num_list3.count(i) > 1:
      print i
      
 Задача 24:
 n = int(input())
arr = list()
for i in range(n):
    x = int(input())
arr_count = list()
for i in range (arr) - 1):
    arr_count.append(arr[i - 1] + arr[i] + arr[i + 1])
    arr_count.append(arr[-2] + arr[-1] + arr[0])
print(max(arr_count))
      
