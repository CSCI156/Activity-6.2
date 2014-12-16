##### FOIL
Write a function called foil() which takes a parameter n and prints out the foiled version of (x+y)n as a string. For 
exponents use the ^ symbol, so that you would print x2 as x^2. The coefficients are nchoose(n,k). For example, 
```
nchoose(3,0)=1
nchoose(3,1)=3
nchoose(3,2)=3
nchoose(3,3)=1
```
and (x+y)^3 = 1*x^3 + 3*x^2*y + 3*x*y^2 + y^3. 

Notice how the exponent on the x goes down by one each term, while the exponent on the y goes up by one. You may also 
notice that the exponents on the x and y add up to 3 in each term, which is the same thing. As I said above, the 
coefficients 1,3,3,1 come from nchoose(n,k).

You will use a for loop to iterate through each term of foiled out version.


Code Outline:
```
def fact(m)
    <stuff>

def choose(n,k)
     <stuff>


def foil(n)
```
