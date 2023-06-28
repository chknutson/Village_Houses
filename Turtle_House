# House
# Chris Knutson

import turtle
import random

turtle.shape("turtle")
turtle.speed(0)
turtle.pensize(2)

COLORS = ["#00FFFF", "#00FF00", "#98F5FF", "#7FFF00", "#FFFF00", "#FF1493", "#B22222", "#FFE1FF", "#FF0000", "#00FF7F", "#0000FF", "#00F5FF", "#FF3E96", "#BF3EFF"]

def fwd(len):
  turtle.forward(len)
  
def move(len):
  turtle.penup()
  turtle.forward(len)
  turtle.pendown()

def left(len):
  turtle.left(len)
  
def polygon(len,sides):
  for i in range(sides):
    fwd(len)
    left(360 / sides)

def rect (width,height):
  for i in range(2):
    fwd(width)
    left(90)
    fwd(height)
    left(90)
    
def square (len):
    for i in range(4):
        turtle.color(random.choice(COLORS))
        turtle.forward(len)
        turtle.right(90)

def triangle (len):
    for i in range(3):
        turtle.color(random.choice(COLORS))
        turtle.forward(len)
        turtle.left(120)

def house (len):
    square(len)
    triangle(len)

def main():
    move(-100)
    house(20)
    move(25)
    house(40)
    move(45)
    house(60)
    move(65)
    house(40)
    move(45)
    house(20)
   
main()
# moves the turtle to below the houses
move(-80)
left(90)
move(-150)

turtle.Screen().exitonclick()
