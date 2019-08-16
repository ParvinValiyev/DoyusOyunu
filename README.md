# DoyusOyunu
Doyusoyunu.py
from tkinter import *

pencere = Tk()
pencere.title ("AYE")
pencere.geometry("500x600")



x = StringVar()
x.set("Rehim")

def yazdirin():
    yazdir2 ["text"] = x.get()

yazdir = Label(text = "Hansi oyuncu ile oynamaq isteyirsen?")
yazdir.pack()

Rehim = Radiobutton (text = "Rehim", indicatoron = 1, value = "Rehim\n hucum gucu:97\nmudafie gucu:75\nkomando gucu:85", variable =x, command = yazdirin)
Rehim.pack()
Pervin = Radiobutton (text = "Pervin", indicatoron = 1, value = "Pervin\n hucum gucu:86\nmudafie gucu:84\nkomando gucu:80", variable =x, command = yazdirin)
Pervin.pack()
Cavid = Radiobutton (text = "Cavid", indicatoron = 1, value = "Cavid\n hucum gucu:70\nmudafie gucu:90\nkomando gucu:83", variable =x, command = yazdirin)
Cavid.pack()
Kenan = Radiobutton (text = "Kenan", indicatoron = 1, value = "Kenan\n hucum gucu:76\nmudafie gucu:98\nkomando gucu:79", variable =x, command = yazdirin )
Kenan.pack()
Resad = Radiobutton (text = "Resad", indicatoron = 1, value = "Resad\n hucum gucu:79\nmudafie gucu:82\nkomando gucu:78", variable =x, command = yazdirin)
Resad.pack()
Togrul = Radiobutton (text = "Togrul", indicatoron = 1, value = "Togrul\n hucum gucu:84\nmudafie gucu:80\nkomando gucu:69", variable =x, command = yazdirin)
Togrul.pack()
yazdir2 = Label()
yazdir2.pack()
mainloop()
