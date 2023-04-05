# demo1
from math import pi
class Shape:
    def __init__(self,name):
        self.name=name
    def area(self):
        pass
    def fact(self):
        return"Im a two dimentional shape"
    def __str__(self):
        return self.name
class Square(Shape):
    def __init__(self
