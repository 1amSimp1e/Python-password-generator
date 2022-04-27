# My Python-password-manager
- Here's mine using Python to make password manager: 
~~~python
import random as r 

lower_case = ['a','b','c','d','e','f','g','h','i','j','k','l','m','n','o','p','q','r','s','t','u','v','w','x','y','z']
upper_case = ['A','B','C','D','E','F','G','H','I','J','K','L','M','N','O','P','Q','R','S','T','U','V','W','X','Y','Z']
digits = ['0','1','2','3','4','5','6','7','8','9']
symbol = ['!','@','#','$','%','^','&','*','(',')']

ans = lower_case + upper_case + digits + symbol

length = int(input("Enter the length of the password: "))
password = "".join(r.sample(ans,length))
print("Generated Password is:",password)

~~~
