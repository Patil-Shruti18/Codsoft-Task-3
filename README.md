# Codsoft-Task-3
# Password Generator

import random
import string
length=int(input("Enter length of your password:"))
setup=string.ascii_letters+string.punctuation+string.digits
if (length>0):
    pwd="".join(random.choice(setup) for i in range(length))
    print("Your generated Password is:",pwd)
else:
    print("Please enter a valid length...(")
    
