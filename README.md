First we import Tkinter giving it the  alias tk for brevity .we begin this example by subclassing Tkinter's main window  widget—Tk (tk.Tk) .We do this because we want to be able to change various aspects of it ,for exmple the title which is displayed
 on the top bar of our window.We set the title "Hello' in this example(self.title("Hello")  ) .
 We want to display some text within our window so we use the widget Label which is not interactive and is used to display text or image 
When we want to define a widget the firt argument is the parent which will hold  it (tk.Label).We use the word self in order to refer to our main window . After that there is a  variety of arguments we can use and  in our case we use text which
will take a string in order to tell the label what to display (label=tk.Label(self,text="Hello,world")  ) 
We have two widgets and we need to place our label inside our main window Tk and to achieve that we use pack( ) ( label.pack(fill=tk.BOTH, expand=1, padx=100, pady=50))
In order to tell the main window to show
itself, we call the mainloop method. This is all enclosed within   if __name__ == "__main__":

  This code was taken from the book "Tkinter GUI programming  by example by David Love
