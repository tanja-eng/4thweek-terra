[python.py](https://github.com/user-attachments/files/34942828/python.py)

Hello welkomme to week 4 of my programms
this weeks programms are as listed 
firstly a disding programms that helps indicisive people diside named python
secondly a tictactoe game this time with a screen unfurtunally it donest work really well you can press the boutens but sometimes insted of a red o a red x appears and I am still not sure wether it belongs to the red os or the 
xes and the winner aint clear too sometimes someone winns without even have filled 3 squers 
so good luck there also wehre some others but I bearly started those so Iam going to add them to next weeks collection


in short
It is a tictactoe game with screen but the recogniton of who has won dosent work.
Secondly there is a generator wich tells you wther to something or not do something this helps with disiding 
And lasty I started a hangman game wich is just at his starting phase This and the uncompete tictactoe game are going to be completet in the next week
import random
print("You probaby also never want to learn or do something" \
" so you procrastionated this games will randomly selected " \
"wether you should learn or leave it but dont you dare pretend " \
"that because the second time said not to do it so I will make sure you cant do that ")
doornottodo=["You shuld learn, or do what ever you were planing to do","You can rest for now"]
random_index=random.randint (0,len(doornottodo)-1)
random_fragen=doornottodo [random_index]
print(random_fragen)
input("\nPress Enter to exit...")
