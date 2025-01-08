# Trivia-
Today 1/8/25 Daily code
#Kenny 1/8/25
#ask a user about a trivia, The trivia ends if they say a secret answer.
#solo
#17 mins

num = 0 #starting point
while num<51: #go one above 50 so it prints
    print(num, end = " ")
    num += 5 #counting by 5
    
#while loop to print trivia until the user types "roosters dont lay eggs"
TriviaInput = "something"
while TriviaInput != "Roosters dont lay eggs":
    TriviaInput = input("A Rooster has lay an egg atop of the barn, which way did it go")
