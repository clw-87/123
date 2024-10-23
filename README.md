# b=int(input('輸入數字:'))
# print(nbr,"的平方為:",nbr**2)
# b=(b+1)*b/2
# print('1加到100為',b)
# print(f'1加到100為:{b:.0f}')
# c,d=10,5
# print('c=',c,'d=',d)
# c,d=d,c 
# print('c=',c,'d=',d)
# a=input('請輸入你的名字:')
# b=int(input('輸入金額:'))
# c=float(input('輸入利率:'))
# d=int(input('輸入年數:'))
# tenyears=b*((1+c)**d)
# print(a[0],'先生/女士您好')
# print('10年後金額:',tenyears)
# a=int(input('enter your score:'))
# a=a+10
# if a>=60:
#     print('pass')
# else:
#     print('unpass')
# d= int(input("請輸入第一個數字: "))
# e= int(input("請輸入第二個數字: "))
# max = max(d,e)
# print("最大數:", max)


# a= int(input("請輸入第一個數字: "))
# b= int(input("請輸入第二個數字: "))
# c= int(input("請輸入第三個數字: "))
# max = max(a, b, c)
# print("最大數:", max)

# a= int(input("請輸入第一個數字: "))
# b= int(input("請輸入第二個數字: "))
# c= int(input("請輸入第三個數字: "))
# x=a
# if b>x:
#     x=b
# if c>x:
#     x=c
# print('最大數',x)
# if (a>=b and a>=c) :
#     print('最大值',a)
# if (b>=a and b>=c) :
#     print('最大值',b)
# if (c>=a and c>=b) :
#     print('最大值',c)
# dollar=300
# a= int(input("輸入年齡:"))
# if a<5 or a>=65:
#     a=int(dollar/2)
#     print('價格為',dollar)
# age= int(input("請輸入年齡: "))
# rating='普遍級'
# if   age>=18:
#     rating='限制級'
# elif age>=12:
#     rating='輔導級'
# elif age>=6:
#     rating='保護級'
# else :
#     rating='普遍級'
# print(f'年齡{age}歲最高可看{rating}電影')
# a = int(input("輸入體重(kg): "))
# b = int(input("輸入身高(cm): "))
# bmi = a / (b / 100) ** 2  # 修正計算 BMI 的公式

# if bmi < 18.5:
#     bmi_category = '過輕'
# elif 18.5 <= bmi < 24:
#     bmi_category = '正常'
# elif 24 <= bmi < 27:
#     bmi_category = '過重'
# elif 27 <= bmi < 30:
#     bmi_category = '輕度肥胖'
# elif 30 <= bmi < 35:
#     bmi_category = '中度肥胖'
# else:  # BMI >= 35
#     bmi_category = '重度肥胖'

# print('你的體態:', bmi_category)
# a = int(input("輸入一個數: "))
# sum = 0
# for i in range(1,a+1):
#     sum=sum+i
#     print(sum)
# a = int(input("輸入一個數: "))
# sum = 0
# for i in range(1,a+1):
#     sum=sum+(i**2)
#     print(sum)
# a = int(input("輸入一個數: "))
# sum=0
# i=1
# while i<=a:
#     sum=sum+i
#     i=i+1
# print(sum)
# for i in range(10):
#     if i==5:
#         continue
#     print(i)

# for i in range(10):
#     if i==5:
#         break
#     print(i)
# s=0
# i=1
# while s<=10:
#     s=s+i
#     i=i+1
# print(i-1)
# a= input("輸入一個數: ")
# for ch in a:
#     if(ch > '9' or ch < '0'):
#         continue
#     print(ch, end='')
# print()
# a= input("輸入一個數: ")
# for ch in a:
#     if(ch > '9' or ch < '0'):
#         continue
# print(ch, end='')
# print()
# s = input('請輸入一串字串:')
# for ch in s:
#     if s == 'fuck':
#         break
#     print('肏你媽')
# else:
#     print('有禮貌')
# a='geggoo'
# i = 5
# while i >0:
#     a = input('輸入帳號:')
#     i=i-1
#     if a == 'geggoo':
#         print('帳號正確')
#         break
import random
b=random.randint(range(1,100),6)
while True:
    a= input(int("輸入一個數: "))
    if a<b:
        print('在大一點')
    elif a>b:
        print('在小一點')     
    else:
         print('恭喜猜對')
         break
