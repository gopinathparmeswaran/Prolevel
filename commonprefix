def comm(str1,str2):
	result=""
	n1=len(str1)
	n2=len(str2)
	i=0
	j=0
	while i<=n1-1 and j<=n2-1:
		if(str1[i]!=str2[j]):
			break
		result+=str1[i]
		i+=1
		j+=1
	return(result)
def commpre(arr,n):
	prefix=arr[0]
	for i in range(1,n):
		prefix=comm(prefix,arr[i])
	return(prefix)
if __name__=="__main__":
	n=input()
	n=int(n)
	arr=list()
	for i in range(n):
		a=input()
		arr.append(str(a))
	ans=commpre(arr,n)
	print (ans)
