# Python-Program-to-Draw-a-Circle-of-Squares-Using-Turtle-Correct-Code
import turtle

t = turtle.Turtle()

def square():
    for i in range(4):
        t.forward(100)
        t.right(90)

for i in range(36):
    square()
    t.right(10)

turtle.done()

Output:
A circle made of overlapping squares is displayed
