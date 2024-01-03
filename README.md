```Python

# Vausdev Shasti AI Chat Bot
# say Radhe Radhe it's mandetory
print("\n\nRadhe Radhe😊\n\nI'm Vasudev Shastri and I'm a Bot\n")
Introduction = input()


if Introduction == "Radhe Radhe":
    print("\nNice to meet you😊\n")
else:
    print("Login Failed!!!")
    exit()

# User Authentication 
Name = input("Name: ")
Login_ID = input("Mail ID: ")
Password = input("Password: ")

if Name == "Vasudev Shastri" and Login_ID == "vasu@gmail.com" and Password == "vasu_16":
    Login = True
    print("Radhe Radhe😊\n\nLogin Successful!!!\n\nWelcome🤗\n")
elif Name == "Anjai" and Login_ID == "anjli@gmail.com" and Password == "anjai":
    Login = True
    print("Radhe Radhe😊\n\nLogin Successful!!!\n\nWelcome🤗\n")
elif Name == "Dharmpal" and Login_ID == "dharmpalgadhwal827@gmail.com" and Password == "dh82A@16":
    Login = True
    print("Radhe Radhe😊\n\nLogin Successful!!!\n\nWelcome🤗\n")       
else:
    Login = False
    print("\nRadhe Radhe😔\nLogin Failed!!!😔\n")
    if Login == "\nRadhe Radhe😔\nLogin Failed!!!😔\n":
       exit()

# Tell me now any thing
if Login == True:
    print(input("Tell me now any thing🤗..."))
```
