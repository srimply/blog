---
layout: post
title: Solving Einstein's Riddle
categories: [Random]
tags: [Random, Einstein, Riddle]
cover: 'assets/images/cover3.jpg'
navigation: True
subclass: 'post tag-random'
logo: 'assets/images/logo.png'
---

<img src="http://i.imgur.com/IgXHPOF.jpg " alt="Einstein" style="width: 200px;"/>

There is an interesting riddle written by Einstein in the last century. He claimed that **98%** of the people in the world will not be able to solve it.

## The Riddle:

* There are 5 different houses, each of a different colour.
* There is a owner of a different nationality in each house.
* Each of the owner drinks a specific type of drink.
* Each of the house owner smokes a specific type of cigarettes.
* Each of the house owner has a specific type of pet.

_None of the owners drink the same drink / smoke the same cigarette brand / have the same type of pets / have same nationality / live in the same house._

## The Clues:

* the Brit lives in the red house
* the Swede keeps dogs as pets
* the Dane drinks tea
* the green house is on the left of the white house
* the green house's owner drinks coffee
* the person who smokes Pall Mall rears birds
* the owner of the yellow house smokes Dunhill
* the man living in the center house drinks milk
* the Norwegian lives in the first house
* the man who smokes blends lives next to the one who keeps cats
* the man who keeps horses lives next to the man who smokes Dunhill
* the owner who smokes BlueMaster drinks beer
* the German smokes Prince
* the Norwegian lives next to the blue house
* the man who smokes blend has a neighbor who drinks water

## The Challenge:

You are challenged to find out who has the fish using the above information and clues.

## The Solution:

The first thing to understand is that though the information seems sparse and disjointed, there is indeed a logical path for you to work out the riddle. 

Imagine the houses layed out in a horizontal manner with the first house on your left to the last house on your right.

<iframe src="https://drive.google.com/file/d/0BwSVKyZQM1obZ1VNWm8waHp2NUU/preview" width="640" height="480"></iframe>

Next, we list out all the possibilities for each category. The categories are nationality, colours, drinks, pets, house number and cigarette brand.

1. Nationality
- Norwegian
- Brit
- Dane
- Swede
- German

2. Colours
- Blue
- Red
- White
- Yellow
- Green

3. Drinks 
- Coffee
- Tea
- Beer
- Water
- Milk

4. Pets
- Dogs
- Cats
- Birds
- Horses
- Fishes

5. House Number
1,2,3,4,5 respectively for each house from left to right

6. Cigarette Brand
- Dunhill
- Blends
- BlueMaster
- Pall Mall
- Prince

Now we write whatever we know in a table form. As we gather more and more information from the clues, we fill the table.

We know that the Norwegian lives in the first house. Next, we know that the Norwegian lives next to the blue house. This means that the 2nd house in the row is blue. The man in the center house drinks milk. And we are told that the green house is on the left of the white house and that the green house's owner drinks coffee. The clue that the green house is on the left of the white house tells that the 4th and 5th houses have to be green and white respectively.

The Brit lives in a red house. The first house has already been occupied by the Norwegian and we know the colours of the 2nd, 4th and 5th houses. This leads us to the fact that the center house is red and the Brit lives there. Also, this leaves the first house to be yellow.

The green house's owner drinks coffee. 

Putting together all these information, we have:

![](http://i.imgur.com/UkHinqI.png)

<table style="undefined;table-layout: fixed; width: 435px">
<colgroup>
<col style="width: 120px">
<col style="width: 120px">
<col style="width: 120px">
<col style="width: 120px">
<col style="width: 120px">
<col style="width: 120px">
</colgroup>
  <tr>
    <th>Nationality</th>
    <th>Drink</th>
    <th>Smokes</th>
    <th>Pets</th>
    <th>Color</th>
    <th>House No.</th>
  </tr>
  <tr>
    <td>German</td>
    <td><br></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Dane</td>
    <td>Tea</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Brit</td>
    <td></td>
    <td></td>
    <td></td>
    <td>Red</td>
    <td></td>
  </tr>
  <tr>
    <td>Swede</td>
    <td></td>
    <td></td>
    <td>Dogs</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Norwegian</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td>1</td>
  </tr>
</table>


Since the owner of the yellow house smokes Dunhill, we know the Norwegian smokes Dunhill. Therefore, the 11th clue tells us that the man in the blue house keeps horses. 

The 12th clue tells us that the man who smokes BlueMaster and drinks beer must be in the 2nd or 5th house (since the first house is occupied by the Norwegian and men in 3rd and 4th house drink milk and coffee respectively). 

Now consider the first house. The options of drinks left for the Norwegian are water, beer and tea. Since the Dane drinks tea, that option is out. Since the Norwegian smokes Dunhill, beer is out. We are left with water.

The last clue makes it evident that the man in the 2nd house smokes blend. That means the man in the last (5th) house smokes BlueMaster and drinks beer.

This leaves us with the option of tea for the 2nd house and hence, it means the Dane lives in the 2nd house.

The current table looks like:

![](http://i.imgur.com/Zi95yp8.png)

<table style="undefined;table-layout: fixed; width: 435px">
<colgroup>
<col style="width: 120px">
<col style="width: 120px">
<col style="width: 120px">
<col style="width: 120px">
<col style="width: 120px">
<col style="width: 120px">
</colgroup>
  <tr>
    <th>Nationality</th>
    <th>Drink</th>
    <th>Smokes</th>
    <th>Pets</th>
    <th>Color</th>
    <th>House No.</th>
  </tr>
  <tr>
    <td>German</td>
    <td><br></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Dane</td>
    <td>Tea</td>
    <td>Blend</td>
    <td>Horses</td>
    <td>Blue</td>
    <td>2</td>
  </tr>
  <tr>
    <td>Brit</td>
    <td>Milk</td>
    <td></td>
    <td></td>
    <td>Red</td>
    <td>3</td>
  </tr>
  <tr>
    <td>Swede</td>
    <td></td>
    <td></td>
    <td>Dogs</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Norwegian</td>
    <td>Water</td>
    <td>Dunhill</td>
    <td></td>
    <td>Yellow</td>
    <td>1</td>
  </tr>
</table>

The 13th clue now shows that the only option for the German who smokes Prince is in the 4th house. This leaves the last house for the Swede who has dogs as pets. 

The 6th clue shows that the Brit smokes PallMall and rears birds.

The 10th clue shows that either the first or third house has cats. Since the third house has birds, this means that the Norwegian keeps cats.

And we are done.

The finished table will look like this.

<table style="undefined;table-layout: fixed; width: 435px">
<colgroup>
<col style="width: 120px">
<col style="width: 120px">
<col style="width: 120px">
<col style="width: 120px">
<col style="width: 120px">
<col style="width: 120px">
</colgroup>
  <tr>
    <th>Nationality</th>
    <th>Drink</th>
    <th>Smokes</th>
    <th>Pets</th>
    <th>Color</th>
    <th>House No.</th>
  </tr>
  <tr>
    <td>German</td>
    <td>Coffee</td>
    <td>Prince</td>
    <td>Fish</td>
    <td>Green</td>
    <td>4</td>
  </tr>
  <tr>
    <td>Dane</td>
    <td>Tea</td>
    <td>Blends</td>
    <td>Horses</td>
    <td>Blue</td>
    <td>2</td>
  </tr>
  <tr>
    <td>Brit</td>
    <td>Milk</td>
    <td>PallMall</td>
    <td>Birds</td>
    <td>Red</td>
    <td>3</td>
  </tr>
  <tr>
    <td>Swede</td>
    <td>Beer</td>
    <td>BlueMaster</td>
    <td>Dogs</td>
    <td>White</td>
    <td>5</td>
  </tr>
  <tr>
    <td>Norwegian</td>
    <td>Water</td>
    <td>Dunhill</td>
    <td>Cats</td>
    <td>Yellow</td>
    <td>1</td>
  </tr>
</table>

This only leaves us with the German who must have the fish. :)

Cheers, <br>
Harish V
