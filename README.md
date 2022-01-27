'''- 👋 Hi, I’m @zohaibjalal
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
zohaibjalal/zohaibjalal is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->'''
from tkinter import*
m=Tk()
L1=Label(m,text="Name",bg="Blue",fg="yellow",width=9,height=3).grid(row=0,column=0)
L2=Label(m,text="Class",bg="Blue",fg="yellow",width=9,height=3).grid(row=1,column=0)
L23=Label(m,text="Roll number",bg="Blue",fg="yellow",width=9,height=3).grid(row=2,column=0)
L4=Label(m,text="Department",bg="Blue",fg="yellow",width=9,height=3).grid(row=3,column=0)
L5=Label(m,text="Nationality",bg="Blue",fg="yellow",width=9,height=3).grid(row=4,column=0)
L6=Label(m,text="Address",bg="Blue",fg="yellow",width=9,height=3).grid(row=5,column=0)
L7=Label(m,text="Phone",bg="Blue",fg="yellow",width=9,height=3).grid(row=6,column=0)
L8=Label(m,text="School",bg="Blue",fg="yellow",width=9,height=3).grid(row=7,column=0)
e1=Entry(m,width=8)
e1.grid(row=0,column=2)
e2=Entry(m,width=8)
e2.grid(row=1,column=2)
e3=Entry(m,width=8)
e3.grid(row=2,column=2)
e4=Entry(m,width=8)
e4.grid(row=3,column=2)
e5=Entry(m,width=8)
e5.grid(row=4,column=2)
e6=Entry(m,width=8)
e6.grid(row=5,column=2)
e7=Entry(m,width=8)
e7.grid(row=6,column=2)
e8=Entry(m,width=8)
e8.grid(row=7,column=2)
b1=Button(m,text="breakup",command="click",bg="Green",width=13,height=4).grid(row=12,column=5)
m.mainloop()
