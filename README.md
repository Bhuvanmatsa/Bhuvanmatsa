import tkinter 
from tkinter import *
root=tkinter.Tk()
root.title("CONTACT APP")
root.geometry("600x600")
'''Label=tkinter.Label(root,text="Contact Form and Contact List Page",font=("Times new Roman",15)).pack()

Label=tkinter.Label(root,text="Add contacts",font=("Times new Roman",11)).pack()'''



b=Button(root,text="ID number",background="white",foreground="black")
b.grid(column=1,row=20)



b1=Button(root,text="Ageof the student",background="white",foreground="black")
b1.grid(column=3,row=20)


b2=Button(root,text="Name of the student",background="white",foreground="black")
b2.grid(column=2,row=20)


r=Radiobutton(root,text="python",value=1)
r.grid(column=1,row=1)
    
r1=Radiobutton(root,text="java",value=2)
r1.grid(column=1,row=2)

r2=Radiobutton(root,text="c++",value=3)
r2.grid(column=1,row=3)

r3=Radiobutton(root,text="c",value=4)
r3.grid(column=1,row=4)
    
t=Entry(root,width=20)
t.grid(column=2,row=22)

t=Entry(root,width=20)
t.grid(column=2,row=24)

t=Entry(root,width=20)
t.grid(column=2,row=26)

t=Entry(root,width=20)
t.grid(column=2,row=22)

t=Entry(root,width=10)
t.grid(column=1,row=24)

t=Entry(root,width=10)
t.grid(column=1,row=26)

t=Entry(root,width=10)
t.grid(column=1,row=22)



t=Entry(root,width=10)
t.grid(column=1,row=24)


t=Entry(root,width=20)
t.grid(column=3,row=22)

t=Entry(root,width=20)
t.grid(column=3,row=24)

t=Entry(root,width=20)
t.grid(column=3,row=26)
root.mainloop()    
