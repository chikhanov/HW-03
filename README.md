per_cent = {'ТКБ': 5.6, 'СКБ': 5.9, 'ВТБ': 4.28, 'СБЕР': 4.0}
money = input('Введите сумму:')
dip1 = per_cent['ТКБ']  * int(money) / 100
dip2 = per_cent['СКБ']  * int(money) / 100
dip3 = per_cent['ВТБ']  * int(money) / 100
dip4 = per_cent['СБЕР']  * int(money) / 100
print(dip1 , dip2 , dip3 , dip4)
