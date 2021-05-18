lst = []
def java(n):
	for i in range(n):
		l = int(input())
		lst.append(l)

n = int(input())
java(n)
sum = 0
y = len(lst) - 1
for i in lst:
	sum += i 
length = sum - y 
print(length)
