# Shapes5.py
creates a new graphics window draws a different shape with a different color in each corner of the window draws a blue diamond perfectly centered in the middle of the window

import turtle 
drawing_area = turtle.Screen()
drawing_area.setup(width= 640, height= 540)
shape1 = turtle.Turtle()

def diamond():
  shape1.penup()
  shape1.sety(70)
  shape1.setx(70)
  shape1.pendown()
  shape1.begin_fill()
  shape1.left(45)
  shape1.backward(200)
  shape1.left(80)
  shape1.backward(200)
  shape1.left(100)
  shape1.backward(200)
  shape1.left(80)
  shape1.backward(200)
  shape1.color('blue')
  shape1.end_fill()

diamond()
