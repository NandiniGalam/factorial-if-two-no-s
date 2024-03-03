# factorial-if-two-no's
 #factorial of even no's between 2 no's
s1=0
s,e=map(int,input().split())
for i in range(s,e+1):
  if(i%2==0):
    r=1 
    for j in range(1,i+1):
      r =r*j 
    s1=s1+r  
print(s1)    
