# bhaskar
python quiz game code

print ("Welcome to my computer quiz!")
playing = input("Do you want to play? ")

if playing.lowe() != "yes":
  quit()
  
print ("Okay! Let's play :) ")
score = 0

answer = input("what's for amalapuram famous for? ")
if answer.lowe() == "amp famous for coconuts":
  print('Correct!')
  score += 1
else:
  print("Incorrect!")
  
  answer = input("what is your favorite place? ")
if answer.lowe() == "my favorite place is goa":
  print('Correct!')
  score += 1
else:
  print("Incorrect!")
  
answer = input("Name the national flower of India? ")
if answer.lowe() == "Lotus":
  print('Correct!')
  score += 1
else:
  print("Incorrect!")
   
answer = input("Name the longest river on the Earth?? ")
if answer.lowe() == "Nile":
  print('Correct!')
  score += 1
else:
  print("Incorrect!")
  
print ("you got " + str(score) + " questions correct!")
 print ("you got " + str((score / 4) * 100) + "%.")
