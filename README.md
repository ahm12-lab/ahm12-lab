from PyQt5.uic import loadUi
from PyQt5.QtWidgets import QApplication

def play():
    a=int(input())
    b=int(input())
    x=windows.a.text()
    y=windows.b.text()
    t=somme()
    windows.setText(t)
    return play()

def somme(a, b):
    return a + b

app = QApplication([])
windows = loadUi ("untitled.ui")
windows.show()
windows.w.clicked.connect (play)
app.exec_()
