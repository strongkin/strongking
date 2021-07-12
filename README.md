# strongking
共同学习
a = 'abcd'
#方法一 使用while逆向遍历
# 获取字符串最大的下标
index = len(a)-1
while index >= 0:
    print(a[index],end='')
    #下标递减
    index -= 1
# 方法二使用切片
a = 'abcd'
b = a[::-1]
print(b)
for i in a[::-1]:
    print(i,end='')
