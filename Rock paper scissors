import tkinter as tk
import random as r
rps = ('ROCK','PAPER','SCISSORS')
def clickr():
    R = "ROCK"
    print("You chosen Rock")
    c.delete(0, "end")
    computer = (r.choice(rps))
    c.insert(0, computer)
    if R=="ROCK" and computer=="PAPER":
        c.delete(0, "end")
        c.insert(0, computer+" ,YOU LOST")
    elif R=="ROCK" and computer=="ROCK":
        c.delete(0, "end")
        c.insert(0, computer+" ,IT'S A DRAW")
    elif R=="ROCK" and computer=="SCISSORS":
        c.delete(0, "end")
        c.insert(0, computer+" ,YOU WON")
def clickp():
    P = "PAPER"
    print("You chosen Paper")
    c.delete(0, 17)
    computer = (r.choice(rps))
    c.insert(0, computer)
    if P=="PAPER" and computer=="SCISSORS":
        c.delete(0, "end")
        c.insert(0, computer+" ,YOU LOST")
    elif P=="PAPER" and computer=="PAPER":
        c.delete(0, "end")
        c.insert(0, computer+" ,IT'S A DRAW")
    elif P=="PAPER" and computer=="ROCK":
        c.delete(0, "end")
        c.insert(0, computer+" ,YOU WON")
def clicks():
    S = "SCISSORS"
    print("You chosen Scissors")
    c.delete(0, "end")
    computer = (r.choice(rps))
    c.insert(0, computer)
    if S=="SCISSORS" and computer=="ROCK":
        c.delete(0, "end")
        c.insert(0, computer+" ,YOU LOST")
    elif S=="SCISSORS" and computer=="SCISSORS":
        c.delete(0, "end")
        c.insert(0, computer+" ,IT'S A DRAW")
    elif S=="SCISSORS" and computer=="PAPER":
        c.delete(0, "end")
        c.insert(0, computer+" ,YOU WON")
root = tk.Tk()
root.title("ROCK PAPER SCISSORS")
root.geometry('250x250')
l1 = tk.Label(text="COMPUTER SAY'S").pack()
br = tk.Button(text="ROCK",width=15,height=3,command=clickr)
bp = tk.Button(text="PAPER",width=15,height=3,command=clickp)
bs = tk.Button(text="SCISSORS",width=15,height=3,command=clicks)
c = tk.Entry()
c.pack()
c.insert(0, "SELECT YOUR POWER")

br.pack();bp.pack();bs.pack()
root.mainloop()
