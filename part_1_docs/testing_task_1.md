### Testing task 1:

# Carry out static testing on the code below.
# Comment on any errors that you see below.

Note that we are only looking for errors here.

**Not** any issues with, i.e.: 
Thinking that methods should be renamed or should be class level, or using string interpolation etc. 

These aren't errors but rather standards that vary from developer to developer. 

Only comment on errors that would stop the tests running.

```python

class CardGame:

# the else statement is missing a colon marking the syntax
# the if statement should have a == instead of just =
  def check_for_ace(self, card):
    if card.value = 1:
      return True
    else
      return False
   
# There is a spelling mistake for the function definition "dif" instead of "def".
# "card" is not a defined variable, should likely be "card1" instead.
# A comma is missing between the function arguments card1 and card2. 
# The if/else statement is not indented approppriately
  dif highest_card(self, card1 card2):
  if card1.value > card2.value:
    return card
  else:
    return card2
  

# total is not defined as a variable
# the function is not indented
# the return statement attemps to concatenate a string and an integer
def cards_total(self, cards):
  total
  for card in cards:
    total += card.value
    return "You have a total of" + total
  
```
