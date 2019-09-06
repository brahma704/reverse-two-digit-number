# reverse-two-digit-number
x=int(input())
if x>10 and x<100:
	i=x%10
	rev_num =i*10+x//10
	print(rev_num)
