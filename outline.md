# Uses for Protected:
# => comparison with wallet class

# Make secret santa program
# secret is gift giving system with a number of people
# that are each assigned to another person to give a gift

# Project Outline
 
## Rules: 
+ Don't match people from the same household
+ no one to one pairings

# Bonus Features: 
+ have history and don't match the two years in a row
+ gift history
+ wish lists

# What is the user intferface?
 + enter you name => your gift reciever
 + read in family list from csv?

```
Start program
Welcome screen

Enter name: Devin
=> You are Jason's secret santa
```

#Potential code outline:

```ruby
module Displayable; end

class Person # Person is a collaborator of itself
  # spouse attribute
  # marital status  
end

class Family
  # pairs (giver/reciever) = {}
    #  { giver => reciever, Droian => Devin, Hernando => Dorian  }
  # collection?
  # an array of all the households
  #  has subarrays of households has persons objects
  
  def assign_santas
  # loop through the collection of people
  # assign people randomly ??? use Array#combination
  # check that person isn't already to that person
  end

  def move_house
  end
  
  def display
  end
end
```


