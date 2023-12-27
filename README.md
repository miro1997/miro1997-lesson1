from turtle import *
#სახლის კედლები
width(5)
color("black")
forward(150)
left(90)
forward(130)
left(90)
forward(150)
left(90)
forward(130)

#კარები
penup()
goto(65, 50)
pendown()

color("orange")
begin_fill()
forward(50)
left(90)
forward(20)
left(90)
forward(50)
left(90)
forward(20)
end_fill()
#მარცხენა ფანჯარა
penup()
goto(40, 90)
pendown()

color("orange")
begin_fill()
forward(15)
left(90)
forward(20)
left(90)
forward(15)
left(90)
forward(20)
end_fill()

#მარჯვენა ფანჯარა
penup()
goto(110, 70)
pendown()
#როდესაც ჩავწერე ფენდაუნ კურსორი არ შეიცვალა, შესაბამისად დავიწყე -20 დან!
forward(20)
begin_fill()
right(90)
forward(15)
right(90)
forward(20)
right(90)
forward(15)
end_fill()

#სახურავი
penup()
goto(150, 130)
pendown()

color("red")
begin_fill()
right(45)
forward(107)
left(90)
forward(107)
end_fill()

penup()
goto(7,170)
pendown()

#საკვამური
color("black")
begin_fill()
left(45)
forward(27)
left(130)
forward(15)
left(50)
forward(17)
left(90)
forward(10)
end_fill()

#ერთადერთი კითხვა - pendown() - არ იცვლება კურსორის მგომარეობე
#ვფიქრობ ალბათ გამოიყენება ერთჯერადად
#ძალიან დიდი მადლობა






































exitonclick()
