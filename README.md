# CODING-1
SYSTEM LOGIN

print("Welcome To BlackPink Page")
print("BlackPink For LIFE")

a = ("Blackpink")
b = ("Ronald")

user = input("Please enter your username:")
password = input("Please enter your password:")

if user == a and password == b:
    print("You Are Certified BlackPink Member")
elif user != a and password == b:
    print("Sorry BlackPink, username incorrect")
elif user == a and password != b:
         print("Sorry BlackPink, password incorrect")
else:
          print("Sorry BlackPink, username and password incorrect")
