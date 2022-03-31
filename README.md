# quadratic-roots
a,b,c=map(int,input().split())
d=(b*b)-(4*a*c)
deno=2*a
if d>0:
   r1=(-b+d**0.5)/deno
   r2=(-b-d**0.5)/deno
   print("roots are real:",r1,r2)
elif d==0:
   r1=r2=(-b)/(2*deno)
   print("roots are equal:",r1,r2)
else:
   r1=r2=0
   print("roots are imaginary")
 
