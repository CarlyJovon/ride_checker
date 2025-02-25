# Create a program that determines which rides a visitor can access at an amusement park based on their age and height

visitor_name = input("What is your name?")
age = int( input("What is your age?"))
height = int( input("What is your height (in inches)?"))



#If the visitor is over 13 and over 60 inches, they can ride all rides
if age >= 13 and height >= 60: 
     print(f'''
     Hi {visitor_name}! You can ride all of the rides at Adventure Park! 
     Here are all of the rides you can enjoy: 

     Kids Rides 
    - Carousel
    - Mini Train
    - Tea Cups 
    
    Family Rides 
    - Ferris Wheel 
    - Log Flume 
    - Bumper Cards

    Thrill Rides
    - Roller Coaster
    - Drop Tower
    - Loop Coaster
     ''')


#If the visitor is between 8 and 12 and at least 48 inches tall, they can ride kids rides and family rides
elif age >= 8 and height >= 48: 
     print(f'''
     Hi {visitor_name}! You can ride all of the rides at Adventure Park! 
     Here are all of the rides you can enjoy: 

     Kids Rides 
    - Carousel
    - Mini Train
    - Tea Cups 
    
    Family Rides 
    - Ferris Wheel 
    - Log Flume 
    - Bumper Cards
     ''')

#Ride for visitors age 8 and up AND height of 48 inches and up
else:
    print(f'''
    Hi {visitor_name}! Here are the rides you can enjoy at Adventure Park!
     
    Kids Rides 
    - Carousel
    - Mini Train
    - Tea Cups 
   
    Sorry, you're not yet elibigle to ride the Family Rides or Thrill Rides yet.
    You need to be at least 8 years old and 48 inches tall for the Family Rides and 13 years old and 60 inches tall for the Thrill Rides.
    ''')



