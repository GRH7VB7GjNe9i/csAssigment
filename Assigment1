import math as m

a=[1,3,5,5,6]
sum=0
sum1=0
b=[4,6,10,12,13]
bsum=0
bsum1=0

for i in range(0,5)
   
   sum=sum+a[i]
   sum1=sum1+a[i]**2
   bsum=bsum+b[i]
   bsum1=bsum1+b[i]**2
print(sum1)
print(bsum1)
mean=sum/len(a)
bmean=bsum/len(b)
print("mean of a is ",mean)
print("mena of b is : ",bmean)
sd=m.sqrt(sum1/len(a) -mean**2)
bsd=m.sqrt(bsum1/len(a) -bmean**2)

print("standerd deviation",sd)
print("standerd deviation",bsd)

print("variance",sd**2)
print("variance",bsd**2)

cov=[[sd**2,sd*bsd],[sd*bsd,bsd**2]]


for j in range (2):

   for k in range (2):
     
     print(cov[j][k],end="")
     
   print("")
r=(sum*bsum)-(sum*bsum)/len(a)
s=m.sqrt(sum1)-(sum**2)/len(a)
p=m.sqrt(bsum1)-(bsum**2)/len(b)
q=s*p;
print("corelation is : ",r/q)
