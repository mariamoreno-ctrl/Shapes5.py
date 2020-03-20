# Shapes5.py
Creates a red square

import turtle 
drawing_area = turtle.Screen()
drawing_area.setup(width= 640, height= 540)
shape1 = turtle.Turtle()

def diamond():
  shape1.penup()
  shape1.sety(80)
  shape1.setx(50)
  shape1.pendown()
  shape1.begin_fill()
  shape1.left(45)
  shape1.backward(100)
  shape1.left(80)
  shape1.backward(100)
  shape1.left(100)
  shape1.backward(100)
  shape1.left(80)
  shape1.backward(100)
  shape1.color('blue')
  shape1.end_fill()

diamond()

def circle():
  
  shape1.right(100)
  shape1.sety(100)
  shape1.setx(-190)
  shape1.sety(-140)
  shape1.color('yellow')
  shape1.begin_fill()
  shape1.circle(50)
  shape1.end_fill()

circle()

def square():
  shape1.begin_fill()
  shape1.right(205)
  shape1.forward(390)
  shape1.right(90)
  shape1.forward(100)
  shape1.left(90)
  shape1.forward(100)
  shape1.left(90)
  shape1.forward(100)
  shape1.left(90)
  shape1.forward(100)
  shape1.color('red')
  shape1.end_fill()

square()
