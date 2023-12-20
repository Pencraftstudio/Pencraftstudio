import turtle

# Set up the turtle screen
screen = turtle.Screen()
screen.bgcolor("white")

# Create a turtle object
pen = turtle.Turtle()
pen.speed(10)  # Adjust the speed of drawing as needed

# Set pen color and fill color to yellow
pen.color("yellow")
pen.fillcolor("yellow")

# Draw the rose flower
pen.begin_fill()
for _ in range(36):  # Draw 36 petals
    pen.forward(100)
    pen.right(45)
    pen.forward(100)
    pen.right(135)
    pen.forward(100)
    pen.right(45)
    pen.forward(100)
    pen.right(135)
pen.end_fill()

# Hide the turtle
pen.hideturtle()

# Exit on click
turtle.done()
