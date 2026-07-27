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
 
THIS IS THE CODE !! YOU CAN ALSO VIEW THE FILE ON NOTEPAD OR VSCODE !!

btw, there is this problem python devs where if they wanna convert they're projects from .py to .exe, they use a module (a module is a library, it just acts like a mod that adds extra stuff to your code to polish it) called pyinstaller, wich bundles the whole code with some extra stuff like a code to execute it at the beggining, basically convert it, but when it runs the code, the whole bundled stuff gets exposed, wich mimics a trojan even tho it's not, so it shows some false positives, but trust me, it won't do anything, if you don't believe me, 1st, check the code and the file "message box test.py" or just tell me of a way to convince you, and if you wanna see the app so badly, you could copy the code and paste it in an engine, or easier, use a VM, and tell me what it did, I'd like to here about any problems, and thx :)


```python
print('Huge update !!')
```

GUYS HUGE UPDATE 🎉🎉🎉🎉:
so I found a solution, wich lets the file seperate from any bundling, wich has one downside, it will become a labyrinth folder, but I made the paths obvious using names, the app's name is 'message box test', it's the only .exe file there so don't worry, so basically what I did is make the app have multiple .dll files to run it, wich ended up being a clever solution, I only changes 'onefile' with 'onedir'
<img width="1366" height="768" alt="Capture d’écran (4)" src="https://github.com/user-attachments/assets/1621f7a4-62b7-46b2-bd7b-0e780a0f51f3" />
<img width="1366" height="768" alt="Capture d’écran (3)" src="https://github.com/user-attachments/assets/10ff6a5b-5403-4383-b396-7c248b43292e" />
<img width="1366" height="768" alt="Capture d’écran (2)" src="https://github.com/user-attachments/assets/8c651e7c-09c0-4e20-b495-51d80c2ff6f8" />
<img width="1366" height="768" alt="Capture d’écran (1)" src="https://github.com/user-attachments/assets/05a0f0e1-915e-4aad-b6a4-309eb7b8fd62" />
proof, and thx again :)
