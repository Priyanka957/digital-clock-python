from tkinter import *
from time import strftime

# Create window
root = Tk()
root.title("Digital Clock")
root.geometry("400x200")
root.configure(bg="black")

# Function to update time
def time():
    current_time = strftime('%H:%M:%S %p')
    label.config(text=current_time)
    label.after(1000, time)

# Clock label
label = Label(
    root,
    font=('Arial', 40, 'bold'),
    background='black',
    foreground='cyan'
)

label.pack(anchor='center', pady=40)

# Call function
time()

# Run window
root.mainloop()