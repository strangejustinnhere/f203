# f203
lol
from tkinter import *


class Main(Frame):
    def __init__(self, root):
        super(Main, self).__init__(root)
        self.build()

    def build(self):
        pass
 
    def logicalc(self, operation):
        pass

    def update():
       pass


if __name__ == '__main__':
    root = Tk()
    root["bg"] = "#000"
    root.geometry("488x554+210+200")
    root.title("calculator")
    root.resizable(true, False)
    app = Main(root)
    app.pack()
    root.mainloop()
