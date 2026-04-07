# task-18-OOP-1-Classes
object oriented programming
# Classes are a form of generalising in programming 
# We need Logic when creating a class, so attributes are assigned to a class 
for example the attributes of a car (the make of a car, its top speed and its weight) 

# our method(constructor), assume our object is a car
car_one = car

  def__innit__(self.make, top.speed, self.weight) :
  
'''
 innit is short for initialise, its a command to our code and "self" refers to our class in our code
 we also need to bind our said attributes into variables for our code to run.
 
'''
  self.make = GMC
  self.top_speed = 200
  self.weight = 3000 
# our class has been created for our object according to our given attributes assigned to the designated variables, in this case a car.
class car

  def get_speed(self) :

      return self.top_speed : 

  def get_weight(self) :

     return self.weight :
# from our given class and variables, we can give commands to retrieve specific attributes about our car using the "self" (self = class), "get" and "return" instructions in Python. 

we can use strings to also manipulate our object like : 
    def __str__(self):

       return f " {self.make}. {self.top_speed}, {self.weight}"

car_one = Car("GMC", 300, 3000)
print(car_one)
# we would get all the characteristics/attributes of our car according to our set variables.
# our object has been turned into a string, thus serves as a short-cut to our previous method.

  
# create new variable
  def   set_weight(self, new_weight) :
car_one.set.weight(2999)
print(car_one)
# we would get the new weight of 2999
