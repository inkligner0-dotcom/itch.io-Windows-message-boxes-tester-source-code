```python
from tkinter import messagebox
import tkinter as tk
def info():
    messagebox.showinfo("Info working", "If you see this, then your info window is working")
def warning():
    messagebox.showwarning("Warning working", "If you see this, then your warning window is working")
def error():
    messagebox.showerror("Error working", 'If you see this, then your error window is working')
root = tk.Tk()
root.title('Error window test')
root.geometry('360x180')
root.resizable(False, False)
root.configure(bg="grey20")
button = tk.Button(root, text="Info window", fg='black', bg='light blue', font=('Arial', 12, 'bold'), command=info)
button.pack(padx=20, pady=10)
button2 = tk.Button(root, text = 'Warning window', fg='black', bg='orange', font=('Arial', 12, 'bold'), command=warning)
button2.pack(padx=20, pady=10)
button3=tk.Button(root, text='Error window', fg='black',bg='red',font=('Arial', 12, 'bold'), command=error)
button3.pack(padx=20,pady=10)
root.mainloop()
```

THIS IS THE CODE !! YOU CN ALSO VIEW THE FILE ON NOTEPAD OR VSCODE !!
