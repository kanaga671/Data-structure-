PROGRAM:

# List ADT using Array

class ListArray:

def _init (self):

self.arr = []

def insert(self, data):

self.arr.append(data)

def delete(self):

if len(self.arr) == 0:

print ("List is Empty")

else:

self.arr.pop()

def display(self):

print ("List Elements:", self.arr)

# Driver Code

I = ListArray()

l.insert(10)

I.insert(20)

l.insert(30)

I.display()

l.delete(30)

I.display()

OUTPUT:

List Elements: [10, 20, 30]

List Elements: [10, 20]# Data-structure-
