# BUANDropDown
Drop down menu used in Data Visualization

from tkinter import *

# This is for the button

root = Tk()
root.title('Pick a Stock')
root.geometry("400x400")

# Drop Down Boxes

def show():
	myLabel = Label(root, text = clicked.get()).pack()

clicked = StringVar()
clicked.set("Banking")

drop = OptionMenu(root, clicked, "Banking", "Healthcare", "Technology", "Food")
drop.pack()

#myButton = Button(root, text = "Show Selection", command = show).pack()

root.mainloop()
