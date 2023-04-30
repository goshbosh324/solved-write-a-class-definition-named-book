Download Link: https://assignmentchef.com/product/solved-write-a-class-definition-named-book
<br>
<p class="ui header product-top-header" title="Write a class definition named Book Solution">Write a class definition named Book. The Book class should have data attributes for a book’s title, the author’s name, and the publisher’s name. The class should also have the following:

a. An _ _init_ _ method for the class. The method should accept an argument for each of the data attributes.

b. Accessor and mutator methods for each data attribute.

c. An _ _str_ _ method that returns a string indicating the state of the object.

Add this code to the bottom of the file, and run the program.

”’  Unit Test ”’if __name__ == “__main__”:book = Book(“The Cat in the Hat”, “Dr. Seuss”, “Random House”)print(book)

# Car class

class Car:

def _ _init_ _(self, make, model, year):

self._ _make = make

self._ _model = model

self._ _year = year

def set_make(self, make):

self._ _make = make

def set_model(self, model):

self._ _model = model

def set_year(self, year):

self._ _year = year

def get_make(self):

return self._ _make

def get_model(self):

return self._ _model

def get_year(self):

return self._ _year