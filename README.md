# pandas-challenge-1
##python workplaxce , 

-gpt chat for questions , google for researches , youtube
-NOTES:
PROGRAMING REVIEW VIDEO 
LIST 
TUPLES
HOW TO MANIPULATE LIST 
HOW TO MOVE IONTO STATEMENTS 
LOOPS


DATA STRUCTURES : a collection of multiple variables 
List : can contain variables , strings , and also another list ..
If we have a list we can find an index (so the first element in the list ) the indexes that finds the order in a list . The first element is 0 and the last is -1 ecc.
Append is gone put a value at the end ; we can remove a value with pop at the end and also “remove” ; len is gone say how many values we have and then we have min , max, sum thats gone do a math .
 
How I see the list info_list = [ ] inside can be strings “” , can contain integers , everything between ”  , “. 
So info_list = [ “samar”, 25, “Kira” , 20] 
Index is the position of where things are : if I want to print the first element 
print(info_list[0]) this is if I want to print the first element 
Print (info_list[-1]) if I want the last element/value  I put -1 . If you know that you have a value and you want to know where is that value you do :
print(info_list.index(“kyra”)).
Taling about slices , if I want the first two elements or the last two element or a part of it . The important thing about slices is that the last value is not there :
print(info_list[1;3]) or print(info_list[;3])  print(info_list[1;]) ; here we’ll have all the values from 1 to 3 exiled 3 :samar ,25, Kira  , 20 is the third value but we don’t write it .

If we want to append :
info_list.append(“Kamau”) 
print(info_list) after this in our list if gone appear Kamau at the end . 
If I want to remove info_list.pop(0) and print(info_list)
For max min and sum : score = [92 , 87, 68, 75, 96]
print(f’Max score {max(scores)}’) HAS TO BE A MAX WIT M BIG and the  m small ;  if I want the minimum value print(f’Min score {min(scores)}’)
If I want to see how many values I have on the list print(f”lenght of score is : {len(scores)}”)
Let’s create the average of the score
  average_score = sum(scores)/len(scores)
Print(f’Average score : {avarage_score}”) and the answer is gone be  Average score : 83.6
Can I also do print(f” Average print sum : {(scores)/len(scores)}”).

TUPLES IS A CONTAINER OF MULTIPLE Values , like the list but the difference is that the tuples cannot be changed . 
HOW WE CREATE THEM : instead of [ ] we’ll gone use parenthesis ( ) ; 
info_tuple = (“Melanie” , ‘Jacinta’ , ‘ Yindi’ , ‘Li’) 
print(names_tuple). Tuple is like Monday , Monday is Monday can’t be changed or December , December can be just December .

Ok so menu_section = (”snacks , “meals” , “drinks” , “dessert” ) is a tuple so I’ll print it by doing print(menu_section) ; then to create a list of items for one of the menu section we do 
dessert = [ “black Forest Cake “, “”Pavlova” , “Lemon Meringue Pie” , “ Cherry Tart” ]

Then I will create a list o prices for each item in the previous list by doing    dessert_prices = [ 4.99 , 6.99, 4.25, 3.50] 
I can also put append and input together ion this case is because I want to input a new item and append it to the relevant list . So I take the list DESSERT AND ->
Dessert.append(input(“What dessert would you like to add ?”)
Ask the user to input the price of the new item , referenced using list indecinx and append it to the relevant list (means that is gone go in the same order between the two lists) 
dessert_prices.append(float(input(f’”How much does {dessert[-1]} cost?”)))

  That is gone mean how much the last dessert it cost ? Because -1 thats the element in the list is the cherry tart and we go to get it in the dessert where we find all the tarts !

CONDITIONALS : it says what you have to to , there is a traffic line you have to follow it . Everything we are coding is a conditional that have an order to follow what to do next . 
If if-else .. for comparing we need to learn about comparing operators : >< .. == when we compare something ; this mean that one equal is a sign in a value != is not equal 
INDENTETION  is very important in Python 
If x == 1 :
print(“x is equal to 1”)
 Or y != 1:
	print(“x is not equal to 1”) and is true , is gone print : x Is not equal to 1 
When we want to validate that something is a number we put isdigit :
If user_input.isdigit():

	number = int(user_digit)
	print(f “input’{number}’ is a number!”)
Else
	print(f “{user_input} is not a number”)

“And” “or”
With and all conditionals have to be true lie we have two variables x=1 and y = 10 , 
Id x==1 and y==10 
	print(“ both values returned true”) —>What is gone print is : Both value returned true 
Wirth or is IF X<45 OR Y<5 
	PRINT(“ONE OR MORE SATEMENTS WERE TRUE “)
IF WE WORK IN A LIST : 
Name = “Amidah”
group_one = [“Jorje”, “Joon”, “Susan”]
So to see if a country is in a list we put first the list 
Countries = [ …] 
Country = Kenya 
And then to see if Kenia is inside I just do 
If country in countries 
	print(f”{country} is in the list) —> is gone print Kenia is in the list .
When you do if elif and else , you have to complete the sentence which is else .

LOOPS are used when we need to repeat multiple time 
To 0 to 4 we have a kind of loop 
for x in range (5) : 
	print(x) is gone go 0 1 2 3 4 and stop
If I loop words , word= “peace” is gone loop letter by letter 
Going back to range 5 ion I print (“-“ * 40)  is gone go in 5 
0
1
2
3
4
—————————-and here 40 dashes  
If I have y =2 
For _in range (5)         this Line_ means that I don’t need to store 
#add 2 to the value of y 
Y += 2 
print(y)
print(“-“ *40) is gone come out 
4
6
8
10
12
——————-40times 


3 CLASS OF AI PROGRAMMING 

Going back to Loop , with the _ with don’t track it , we loop until we finish our elements without counting them until something is interrupting like in the previews example .
So when we have len , are like 4 values and we get [I] is gone be the previews number from the list plus 1 , that for every I from the list meaning from any number of the list.
So numbers = [9,6,4,9] 
For I  in range (len(numbers)): 
Add 1 to the list item 
Numbers[I] += 1
print(numbers[I])
print(“-“ * 40) what is gone come out is every number in the first list  +1 so 
10
7
5
10
WHILE conditional is gone keep going until the infinity if we don’t change the variable 
While run.lower() == “y” 
Print (“HI”)
Run = input (“to run again . Enter ‘y’:”) 
 IMPORT  RANDOM
ROCK PAPER SEASSORS 
IF WE NEED TO LOOP UNTIL SOMEONE WINS WE NEED THE WHILE LOOP
While true : 
user_choice = input (“make your choice : (r)rock, (p)aper, (s)scissors?”     This is a condition and we are checking if is gone be found in options .
We need to check if condition is in the options so we do 
    If user_choice in options :            options = [“r”, “p”, “s”]
The computer selection is gone be computer_choice = random.choice(optional)
 Random.choice is gone randomly choice from the option list. Then is asking to create a variable called user_full_choice to hold the text of the full world for user’s choice by using a conditional 
  If user_choice = =“r” two equals because we are comparing 
user_full_choice = “rock” now is one = because we assigning the value to user_full_choice
 
Elif user_choice ==“p” 
user_full_choice = “paper”
Else 
use_full_choice = “scissors”
   After the elif and all the options we do print(“would you like to play again?)
play_again = input(Type (Y) to continue or anything else to exit ) so we begun with WHILE SO WAS A LOOP SO AFTER WE ASK IF THEY WANT TO PLAY AGAIN 
If play_again.lower()  !=  ‘y ‘:
	break     this is saying that if the answer is not (!=) y we break it  
When we have a very long list of conditionals cases we have MATCH  
OBJECTIVES
DICTIONARIES INSIDE DICTIONARIES 
SO  we are creating a menu and we need to do place_order = True then we need a loop of while , to show the pie selection 
For order base in the index I choose the pie I want . First of all by doing the first loop wit “for” and “in” we are telling to give to any pie in the list a number by going down so 
1 pecan 
2 apple
Ecc.. also we put pie_number += 1 cause we start from 1 and plus  .
So we know that with index is start at 0 so if we want to print 

(((Menu is storing the names as snacks cookie banana first level  keys .
Keys snack meals drinks coffee first level , then we have second level key that are cookie banana etc 
With while the loop is broken by who is using it , by the costumer .
If it says check , means that you have to to a conditional so “if”. Under the hashtag has to be the ion . 
The key is a number . 
https://pythontutor.com/render.html#mode=display tool 
Python Exercises, Practice, Challenges – PYnative
Python Tutor code visualizer: Visualize code in Python, JavaScript, C, C++, and Java)))) tutor session ended 

 When I use match  : match keep_ordering.lower() :
If costumer choose yes we say 
Case ‘y’
So to check the input of the customer we do the loop with while  
To reduce the code of elif in case they want to order or not we just use match and put the cases 
DICTIONARY : EACH VALUE IS GONE HAVE A KEY AND A VALUE . The key is immutable and is gone be between “” , the value after the : can be a list another dictionary or string or anything , variable ecc.
The definition of the key is gone be the value . Keys cannot change , the values can , can be a boolean a string an everything . They are going to be declaered in {} or actors = dict()
If I do actors = { “name” : “tom cruise”} I have the key that’s the name and the value of the name thats Tom cruise , so if I do actors[“name”] = “Denzel Washington” this is also gone bring us the value  .
If I want to print actors = {“name” :”Tom Cruise”}
print(actors[‘name’]) or
print(f’”Name : {actors[“name]}”)
Also print(f”{actors[name]}”) but is gone came out still just the name of the actor so Tom Cruise . With f’ is better is you want to put a phrase in it like The name of the actor is Ila Ila{actor[name]}
To create a dictionary that contain another dictionary 

Film = {
      “Title” : “interstellar”
      “Rvenue” : {
	“united states “: 360,                       so here I have a dictionary in another dictionary 
	“China”: 250, 
	“United k:73
         }
}
If I want to print the value of us  film[“revenues][“united states]

print(f’{} made {} million in the us )
Let’s say I have a big dictionary with more dictoionaries inside , and I have more values of print(Film.keys{}) to know what the first keys then print(film.keys()) ; print(film.value()) , print(film.item ())  that for specific information . 
If I loop by saying 
For key in film.key():
    print(key) this is gone to print each element , we can do the same with values 
Film.values():
 print(key).
Going to the activity 5 when I get to print My first hobby is {my_info[“hobby”][0]}’) I do this because I have a list there so I put the key that contain the list in [ ] and also the number of the hobby  in [ ]. 
Comprenhensions list : let’s say we have a basket of fruits mixed , and we want to create another basket that creates just oranges . So I go trough my list and if they have the condition that I want I keep it .
For i in range(5)
    Square [I] =I*i
   Vs 
Square = [I*i for I …

Example fish = “halibut” , then we are creating a new list thats empty letters =[] 
For letter in fish : 
   Letters.append(letter)
print(letters)    the list is gone be printed like [ “h”, “a”, “l”,..].

When I put capita_letters.append(letter.upper())  , I have an operation which is letter.upper()) so is gone print all capital letters of halibut in a list .

FUNCTIONS  - PROGRAMMING AI
<DRY> don’t repeat yourself , in software engineering is important to not repeat yourself .
FUNCTIONS are coding in a block , and provide a better organization.
And therefore, if we have to make a change. We don't need to deal with the whole piece of code. We can just target like this specific part without being worry about breaking up something else.And therefore, if we have to make a change. We don't need to deal with the whole piece of code. We can just target like this specific part without being worry about breaking up something else.
Functions written in python len() , max(), min(), sum()..append() pop() and remove()
We are starting the function by writing def meaning definition . So 
Def hello() in the (is going the max or min)
   print(“Hello”)
hello()

if __name__ == "__main__":
    # Call the function to run the code in the function.
    process_payment()

prevent everything, for from running at once, this is going to do

It’s gone run just what I need to run at once . That is gone say keep it in memory but don’t use it until I call it. 
Global variable are the once that travel in the code not only in the function .
# Define a function that will add two numbers.
def add():
    """This function takes two numbers and adds them and then returns the total."""
    first_number = 1 # This is a local scope of the function.
    second_number = 2 # This is a local scope of the function.
    total = first_number + second_number
    print(f"Your total is: {total}")


if __name__ == "__main__":
    add()
    print(first_number)

First_number is a variable inside the function so is a local variable , that one cannot be put after if __name__…as a print(first_number) because is a local and is not gone work . Is gone work just inside the function.
So if I have to ask to print after the function and let’s say I have numbers as keywords , to define them has to be in order or specify , like is I ask to do a+b+c when I print I specify a=2,b=3,c=4 ; we can also do 2,b=3,c=4 ; but we can’t do b=3,c=4, 2 ; they are not in order anymore and the code doesn’t gets it anymore.  
# 3. Keyword and positional arguments
def pos_key_args(a, b, c):
    """This function takes one positional argument
    and two keyword arguments, adds them, and prints the total"""
    total = a + b + c
    print(f"The total is: {total}")

if __name__ == "__main__":
    pos_key_args(42, b=-10, c=5)
    # pos_key_args(b=-10, c=5, 42) uncomment this line and run again.
 
Variable = [42,-10,5]
 If I want to incorporate a variable after how do I do it? Under the variable I do 
pos_keyargs(variable[0],variable[1],variable[2]) I put the positions of the variable I want to bring in it. But we can also do iterable(*tuple_values) with the asterisk we can pass all the values inside the list or tuple ; how it is gone know which are the values inside ? Is positional so ig gone go in order with the first argument , the second etc.
We can also have a dictionary and in there can also pass something that’s not in order because we already have the key in there saying what is what.
# 5. Dictionary unpacking arguments.
def dictionary(a, b, c):
    """This function takes an iterable (list of tuple)
    and adds the values in the iterable, and prints the total"""
    total = a + b + c
    print(f"The total is: {total}")

if __name__ == "__main__":
    dict_values = {'b': -4, 'c': 100, 'a':-42 }
    dictionary(*dict_values) # returns the keys
    dictionary(**dict_values) # returns the values

If we have one asterisk is gone think that we have to do an operation with the keys . If we have two ** is gone bring the value . First total is = bca and the other with ** is 54

The 2f is taking the two decimals from the flow.
The list 
 def average_numbers(numbers):
    """ Calculates the average of an array of numbers"""
    average = sum(numbers) / len(numbers)
    print("The average is: ", average)

if __name__ == "__main__":
    average_numbers([1, 2, 3])
Here if how we call the function and says what the function does .
We can also past a list to the function . Means that we need to navigate inside . 
If I have a return is because is sending me something and I need to contain it and is variables ; we want to store it in a variable . So if we want to return something the keyword is RETURN. 
We have to compute the average and then return it . If I do return average is like , ok I did the avarage (return) now I send it to you. 
list_comprehension = [divide_by_seven(number) for number in [24,654,3,961,21]] 
This follow [x for x in list] x is the variable 
Map is similar to list_ comprenhation 

We learned this in a previous class .
Then we learning map. 
map_function= map(devide_by_seven,(24,654,3,961,21)) this is going to do the same but is not converting it to a list . If we want the list we can cast is as a list by doing 
map_function= map(devide_by_seven,(24,654,3,961,21))
print(list(map_function))
To make an anonymous  function , that is a function that defines everything in once we need the keyword lambda , so instead of that devide_by_seven I put lambda and then I define the variable I use in the function which is x then we put the body of the function which is round(x/7,3).
map_function_v2 = map(lambda x :round(x/7,3),(24,654,3,961,21))
Map is not converting into a list so I need to cast it 
print(list(map_function_v2))
If I want to filter values of a list based on a condition . Python can build function and use the code filter 
# 5. Use the filter and lambda functions to get only the numbers divided by 3.
numbers = [12, 7, 9, 18, 25, 36, 42, 55, 63]
divisible_by_3 = list(filter(lambda x: x % 3 == 0, numbers))
print(divisible_by_3)
LAMBDA DOES WHAT RETURN DOES BUT IS NOT SAVING IT , IS USEFUL WHEN WE NEED IT FOR AN ARGUMENT ,TO DEFINE AN ARGUMENT WITHOUT SAVING
Let’s say I want all the numbers that can be divided by 3 .
 So we learned 2 functions MAP FILTER LAMBDA .
MAP  is gone receive a function and iterable and what is gone do is gone loop and show the function.
The lambda do not have a definition , do not have a name , are called anonymous functions , they can be use in map , comprehension list .. the structure f = lambda a:a*a , keyword is lambda , a is an argument and then one line expression of the corp  a*a .
FILTER  is filtering out values , we need a conditional to see what we want or not and is gone be coding in the function . Then we are going to see if is following the condition or not .

AI 2 MODULES 
SO FROM A MODULE WE IMPORT TO A FUNCTION
 LIBRARY THAT CONTAIN HOUNDRED OF FUNCTIONS AND WE DON’T NEED TO ALL OF THEM BUT M AYBE JUST REMEMBER WHAT WE NEED AND ALSO CAN FIND THE OTHER .
Very popular modules , to generate random numbers , the. Module is called random and to import we say randint , choice how we use this 
random_number = randint(1,10) () means between 1 and 10
print(random_number) it came out 5 thats just a random number between 1and10.
Now we talk about choice , I have a list with fruits and my_list=[ apple, banana…] and I do 
Random_element = choice(my_list0
print(random_element)
We ha a module called “datetime”  
From date time import date time, date
Current_datetime =datetime.now()
current_datetime 
print(current_datetime.strftime(“%h:%m:%s”)) this is gone come out with the time now 19:28:30sec , this could be useful to know in how long you would finish a game , is gone come out the time of when you run Current_datetime =datetime.now()
WHAT IS REFACTGORING  : we have something that works ,we don’t need to fix it ,it has the functionality we desire ,but now we want to optimize the code , make it faster and more efficient .this is what refactoring is . Refactoring is not about fixing . Make sure to refactor code that is working .
Let’s say I have a list that I want to loop 
Number = [1,2,3,4,5]
squared_numbers=[]
For num in numbers:
   Squared_numbers.append(num**2) I’m gone square square_numbers in each number 
Print (square_numbers)
BY REFACTORING THIS CODE , we bring the list again 
Number = [1,2,3,4,5]
squaered_numbers= [x for x in list] I can replace NUMBERS  with list
squaered_numbers= [x for x in numbers], first x is gone be **2 and second num 
squaered_numbers= [**2 for num in numbers]
print(square_numbers)
Now is gone come out same result but more abbreviate 
For i in range .
# Code that uses the range() function.
numbers = [10, 20, 30, 40, 50]
for i in range(len(numbers)):
    print(f"Index: {i}, Value: {numbers[i]}")

There is a function called enumerate and work with sequences , is going to return the enumeration .
# Refactored the code to use enumerate()
numbers = [10, 20, 30, 40, 50]
for i, num in enumerate(numbers):
    print(f"Index: {i}, Value: {num}")

Enumerate is going to return to values .
We can code a list again Wirth a function 
# Refactored code with a function
def calculate_average(numbers):
    """The function calculates the average of an array of numbers."""
    total = sum(numbers)
    count = len(numbers)
    average = total / count
    return average

numbers = [5, 10, 15, 20, 25]
average = calculate_average(numbers)
print(f"The average is: {average}")
 
So we want to sum every number in the list so we have the variable total = sum(numbers), to see how many numbers we have we do count= len(numbers) and the the average . 

AGILE METHODOLOGY 
  do not wait until this is perfect. Don't wait until everything is
fully complete and functional to deploy. You want to continually continually deploy, develop continually deploy.
So you can start getting feedback from the users.
You cannot fix something if you haven't done it first.
User stories 
Is a statment of how a user needs to interact in a future , you need to define a role of who needs the application and the goal of what you need and finally need to define the benefits .
Most of the time the costumers know what they want but not what they need . Learning how to benefit the customers. 
Business requirements 
A modular ATM Design  
I have more modules that has different functions , so the pin is staying safe . Under action which is a module I have make_deposit and another function make_withdrawal. 
 So when I need to import from a folder a file I do “ from actions(is the folder of vscode on the left and inside we find make_deposit so is gone be followed by a doc.) . make_deposit

AI OOP Phyton CLASSE III 

OBJECT ORIENTED PROGRAMMING : CLASSES ARREUBUTES INSTANCES METHODS..
Instead of just running functions we’ll put them in classes , then we’ll see how to manipulate classes. 
Object oriented p. Is the philosophy of organizing the code , se the relationships between codes and how they react to. let’s say we have a car and we have a blueprint and the attributs that can be the make of the car (Honda ,Toyota) then we can have another attribute that can be the color of the car.
We will have the car ,the actual car after blueprint and attributs and that is gone be the object . The car that drives is the function of the car , all the info of the car are going inside the blueprint . 
So the classes are going to be the blueprint and the object the car . In the slide we have 3 cars with same blueprint and then we are going to create individual objects with attributs like one is black Honda and one red Toyota ecc. 

We need to have words that have meaning for the object that we are creating .
In vs code we are going to create a class and to do that we start with the world “ class”.. so is gone look like class Car : (car with C grande) . Then we are going to use this constructor : ( is going to look like a function)                     def __init__(self)
   Pass
                          So when we are creating an object we need to add the attributes ,like we are making a care , so what car? So I need to add variables
def __init__(self)
make=make
model=model
   Pass
S when I’m gone make the car I’m gone bring those parameters close to self def __init__(self, make, model)
make=make
model=model
   Pass
So Car is the blueprint and we need to refer something to that and in this case is SELF so if we want to access to make and model we need to do self.make.. def __init__(self)
self.make=make
self.model=model
   Pass
So after we define the class (car ) we define all the attributs doing def __init__(self …) we will always have self cause with that we can access to the attributs 
Then in the terminal you are going to put def __init__(self)
make=make
model=model
   My_car = Car(“Toyota”, “Camry) 
Print (f”Make:{my_car.make}”)
Make:toyota 
Print(f”Model:{my_car.model}”)
Model: Camry 

So in the activity 2 was asking to add more attributes and that happens with self.make = make ..and self.model = model etc.
Then you put information with make = input(“..”) and then we create the car by printing : print(f”make: {car.make }”).
Instance Methods :are going to manipulate the attributes in the instance . We just want to have. Function that change the color let’s say .
Def get_make(self):
 Return self.make
There is also another method def set_make(self, new_make):
Sales.make = new_make 
“”” If you press shift + enter is gone run everything in the terminal but ofc you have to select what you want to run . 
There is another way too my_car = Car(“Toyota”)
initial_make =my_car.get_make()
print(f”Initial Make :{Initial_make}”)
Then to set a new make we do :
my_car.set_make(“Honda”) 
How it starts to change what I want to change :
my_car = Car(Toyota”,”Camry”)

Initial_make= my_car.get_make()
print(f”Initial Make :{initial_make}”)

my_car.set_make(“Honda”)


update_model= my_car.set_model(“Corolla”)
print(f”Update Make :{update_make}”)
 
my_car.set_model:{initial_model}”)

my_car.set_model = my_car.get_model()
print(F”Update model:{update_model}”)
 
   Storing classes as Modules , we have .py extension 

From file car Import that class which is Car , we do that to have a different file so we store everything in a more organized way . 
Import Car from Car , first car is the file \which I see also on top car.py and the second car is the name of the class . And now we instantiate the class 
Car = Car() lower case I know that is an object and Car I know that is the class and also is showing up green on vs code. How do I know which parameters we need for that initiation :
car = Car(“ Subaru”, “Crosstrek Limited”, “Suv”, “2.5L”, 2020, “Pearl Blue”)
When I do print then input and then I change with set , I have to give info anfter set in terminal and that is gone be th info I’m gone change make model etc then I go back and print (here are update info for car etc”).
Activity 6 Bank account 
We can see in the first file we have 3 functions one we create the balance then we can deposit , withdraw and just check 
From bank account import BankAccount (from file to class)
INHERITANCE 
IS TAKING THE WORLD LITTERALY , IS GOING TO INHERITE A CLASS , MEANING THAT I can take all the datas of an (lets say) child class and save it in a new one and make it bigger , so just kinda copy the attributes of a class and add more and make either different.

PANDA
The reason we use panda is because if we have big data is more appropriate , excel is heard as software to be used .
Conda dev 

