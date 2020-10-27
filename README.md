# car game
this is a documentation of the application car

"""Code by leykunberhan
Date  Wensday, July 8 2020
Discription of code: Learning Python
"""

i = 1                    
get_help = """
startcar - start the car
stopcar - stop the car
quit - quit the program
"""
while i < 5:
    enterd_string=input(">")
    if enterd_string == "quit":
        break
    if enterd_string == "startcar":
        print("Car engine has started!")
    elif enterd_string == "stopcar":
        print("Car engine has stoped!")
    elif enterd_string == "help":
        print(get_help)
    else:
        print("Please enter the correct value.Form Help Use'help'")

