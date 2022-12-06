# Armstrong
n=int(input('Enter any number:'))
s=0
t=n
while(n!=0):
    r=n%10
    s=s+(r*r*r)
    n=n//10
if(t==s):
    print('It is an Armstrong number.')
else:
    print('It is not an Armstrong number.')
