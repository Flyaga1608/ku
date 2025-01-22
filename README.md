# ku print('hello world')
import pandas as pd
x = int(input("введите строчку"))
y = int(input("введите столбец"))
df_exel = pd. read_excel('Data.xlsx')
print (df_exel.iloc[x,y])
