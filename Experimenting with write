import os

def write_two_values ():
	try:
		print("Input Value A")
		a = float(input())
		print("Input Value B")
		b = float(input())
	except:
		print("Please only enter a number")
	a = str(a)
	b = str(b)
	with open("checkedposts.txt", "a") as f:
		f.write("\nValue A: " + a + ", Value B: " + b)
	with open("checkedposts.txt", "r") as f:
		print(("\n***" * 2) + "\nBeginning of File\n" + ("_" * 30))
		print(f.read())
		print(("_" * 30) + ("\nEnd of File") + ("\n***" * 2))

print("Press 1 to add values\nPress 2 add new text\nPress anything else to read the file")

choice = input()
if choice == "1" or choice == "2":
	if choice == "1":
		write_two_values()
	elif choice == "2":
		print("Enter text now")
		textEntered = str(input())
		with open("checkedposts.txt", "a") as f:
			f.write("\n\n\n" + textEntered + "\n")

else:
	with open("checkedposts.txt", "r") as f:
		print(("\n***" * 2) + "\nBeginning of File\n" + ("_" * 30))
		print(f.read())
		print(("_" * 30) + ("\nEnd of File") + ("\n***" * 2))
