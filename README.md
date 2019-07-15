# -
这是最初的，记录我的学习
# while True:
#     cole=input("输入一个变量")
#     if cole=="red":
#         print("结束这个话题吧，我们谈谈今天吃什么")
#         break
#     else:
#         print("你可以继续输入变量")
#
#
# while True:
#     cai = input("今天吃什么菜？")
#     if cai=="怕哈":
#          print("I dom't like there")
#          continue
#     else:
#         print("I like "+cai)
#     print("thank you!")
# a="11"
# i=int(a,base=2)
# print(i)
# age=3
# zaiti=age.bit_length()
# print(zaiti)


# .center()方法
# i="小"
# tese=i.center(10,"0")#设置总宽度并且将“小”居中，两边用0来填充
# print(tese)
# .ljust()  .rjust这两个方法能将字符串左或者右对齐并设置宽度以及填充物

#
# casefold方法:所有变小写
# Aliez="Zeyed"
# i=Aliez.casefold()
# print(i)
# capitalize方法：首字母大写
# .swapcase大小写转换
#
# count方法：去字符串中寻找子序列的出现次数
# i="11111111"
# print(i.count("1"，3，5))
# 输出的便是字符串在第4到第6个元素中包含子序列的次数
#
# endswith(）方法能检测是否以什么结尾
# startswith()方法能检测是否以什么开头

# find从开始往后找，找到第一个获得他的位置,可以规定区间
# a="fawhiojogjegj"
# print(a.find("j",7,))

# format方法：将一个字符串中的占位符替换为指定的值
# zifuchuan="i am {1},age{0}"这是用位置来确定替换
# zaiti=zifuchuan.format(19,"yangg")
# print(zaiti)
# 也可以通过贴标签来替换，
#
# isalnum()方法能判断字符串是否只包含字母和数字
# isalpha（）方法判断是否只包含字母
# isdecimal（）和isdigit（）方法判断数字，后者比较厉害可以判断很多种表示的数字，第一个更常用
# isprintable（）是否存在不被打印出来的字符，有则F无责T
# isspace（）判断是否全部是空格
# istitle（）判断是否是英语作文标题款式  title方法变成标题
# .islower()判断是否是小写
# .isuper()大写判断
# .starwith() .endwith（）判断是否是某某东西开头  结尾


# expandtabs(x)前x个字符中有\t则把\t变成空格与之前的内容加起来的总长度为x
# str="I love\tpython"
# print(str)
# print(str.expandtabs())
# print(str.expandtabs(5))
# print(str.expandtabs(2))
# print(str.expandtabs(8))
# print(str.expandtabs(9))
# print(str.expandtabs(10))


# .join将字符串中的每一个元素按照指定分隔符进行拼接     *****

# .lstrip（）  .rstrip（）   .strip（）去除左右空格和\t\n  也可以指定去除***

# str.maketrans()把两个字符串放进去用逗号隔开，能创立对应关系
# .translate()把拥有对应关系的两个字符串的互相对应的元素一一替换
# zaiti=str.maketrans("aeiou","为了理想战")
# zaiti0="abcdefghijklmnopqrstuvwxyz"
# new_zaiti0=zaiti0.translate(zaiti)
# print(new_zaiti0)

# 分割
# .partition()效果如下   .split()效果如下    .splitlines()只根据换行符进行分割，且括号内为T则显示\n，F则相反
a="testtest"
#  print(a.partition("es"))
# >>>('t', 'es', 'test')分成3份
# print(a.split("es"))
# >>>['t', 'tt', 't']分成多份

