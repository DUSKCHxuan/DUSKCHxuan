class Ex01:

def_init_(self,month):

self.month = month

def get_season(self):

if self.month < 1 oг self.month>12:

return '错误: 输入的月份不正确，请输入1-12之间的数字。'
elif self.month in [3,4,5]:

return '春季'

elif self.month in [6,7,8]:

return '夏季'

elif self .month in [9,10,11]:

return '秋季'

else:

return '冬季'

mounth number a int(input('input(1-12) : '))

season_get = Ex01(mounth_number)

season = season_get.get_season()
print(f'{mounth_number}月是{season}')
