# character_input01
Practice Python - Character Input 01

def char_input():  
	name = input(str("What is your name? "))  
	print("Hello %s" % name)  
	age = input("How old are you {0} ".format(name))  
	oldAge = 100 - int(age)  
	returnMessage = "You will turn 100 in {0} years \n".format(oldAge)  
	print(returnMessage)  

	userInput = input("Enter another number ")  
	print(returnMessage * int(userInput))  
if __name__ == '__main__':  
	char_input()  
