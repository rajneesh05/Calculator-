from tkinter import*

class Calculator:
    global operator
    global text_input
    def btnClick(self,numbers):
        
        self.operator=self.operator+str(numbers)
        self.text_input.set(self.operator)

    def clear(self):
##        global operator
##        global text_input
        self.text_input.set("")
        self.operator =""    
    def equal(self):
##        global operator
##        global text_input
        self.sumup=str(eval(self.operator))
        self.text_input.set(self.sumup)
    def __init__(self,master):
        self.master=master
        self.operator = ""
        self.text_input=StringVar()

   
        
        txtdisplay=Entry(master,font=('arial',20,'bold'), textvariable=self.text_input, bd=20,insertwidth=4,bg="silver",fg="black",justify='right').grid(columnspan=4,pady=3)
        btn7=Button(master,padx=10,pady=8,bd=8,fg="white",bg="seashell4", font=('arial',20,'bold'), text="7",command= lambda : self.btnClick(7)).grid(row=1,column=0,pady=1,padx=1)
        btn8=Button(master,padx=10,pady=8,bd=8,fg="white",bg="seashell4", font=('arial',20,'bold'), text="8",command= lambda : self.btnClick(8)).grid(row=1,column=1,pady=1,padx=1)
        btn9=Button(master,padx=10,pady=8,bd=8,fg="white",bg="seashell4", font=('arial',20,'bold'), text="9",command= lambda : self.btnClick(9)).grid(row=1,column=2,pady=1,padx=1)
        btn4=Button(master,padx=10,pady=8,bd=8,fg="white",bg="seashell4", font=('arial',20,'bold'), text="4",command= lambda : self.btnClick(4)).grid(row=2,column=0,pady=3)
        btn5=Button(master,padx=10,pady=8,bd=8,fg="white",bg="seashell4", font=('arial',20,'bold'), text="5",command= lambda : self.btnClick(5)).grid(row=2,column=1,pady=3)
        btn6=Button(master,padx=10,pady=8,bd=8,fg="white",bg="seashell4", font=('arial',20,'bold'), text="6",command= lambda : self.btnClick(6)).grid(row=2,column=2,pady=3)
        btn3=Button(master,padx=10,pady=8,bd=8,fg="white",bg="seashell4", font=('arial',20,'bold'), text="1",command= lambda : self.btnClick(1)).grid(row=3,column=0,pady=3)
        btn2=Button(master,padx=10,pady=8,bd=8,fg="white",bg="seashell4", font=('arial',20,'bold'), text="2",command= lambda : self.btnClick(2)).grid(row=3,column=1,pady=3)
        btn1=Button(master,padx=10,pady=8,bd=8,fg="white",bg="seashell4", font=('arial',20,'bold'), text="3",command= lambda : self.btnClick(3)).grid(row=3,column=2,pady=3)
        btn0=Button(master,padx=10,pady=8,bd=8,fg="white",bg="seashell4", font=('arial',20,'bold'), text="0",command= lambda : self.btnClick(0)).grid(row=4,column=0,pady=3)
        btnsub=Button(master,padx=10,pady=8,bd=8,fg="white",bg="black", font=('arial',20,'bold'), text="−",command= lambda : self.btnClick("-")).grid(row=4,column=1,pady=3)
        btnadd=Button(master,padx=10,pady=8,bd=8,fg="white",bg="black", font=('arial',20,'bold'), text="+",command= lambda : self.btnClick("+")).grid(row=4,column=2,pady=3)
        btnclear=Button(master,padx=16,pady=8,bd=8,fg="white",bg="red", font=('arial',20,'bold'), text="c",command= self.clear).grid(row=1,column=3,pady=1,padx=1)
        btndiv=Button(master,padx=16,pady=8,bd=8,fg="white",bg="black", font=('arial',20,'bold'), text="÷",command= lambda : self.btnClick("/")).grid(row=2,column=3,pady=3)
        btnmul=Button(master,padx=16,pady=8,bd=8,fg="white",bg="black", font=('arial',20,'bold'), text="x",command= lambda : self.btnClick("*")).grid(row=3,column=3,pady=3)
        btnequal=Button(master,padx=16,pady=8,bd=8,fg="white",bg="orange", font=('arial',20,'bold'), text="=",command= self.equal).grid(row=4,column=3,pady=3)

    

root=Tk()   
Calculator(root)
root.title("Rajneesh Calculator")
root.geometry('341x426+0+0')
root.resizable(False, False)
root.configure(background='black')
root.mainloop()

