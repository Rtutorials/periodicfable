
Hello everyone,

As a part of the projects I am working on to keep myself busy during these weeks after the tragic passing of my parents, I am seeking assistance on this game I was coming up with a while ago. It was relaxing and enjoyable to work on and see it grow, and I would often keep my parents updated on the progress and they were happy to see that. If you want to contribute, open the html and play around, it's pretty easy to get started. Aside from playtest feedback, at the end of this readme there is a list of things I eventually want to add. If you have questions about your changes or they aren't obvious, make a new branch. 




Welcome to Periodic Fable (name subject to change), a solo alchemy puzzle game. In this game you are trying to use elements to clear encounters, gain rewards, and fuse together elements to make new ones. In the same style of games such as Little Alchemy and Doodle God, you can combine two elements to make a new one, for example Fire + Earth would give you Rock. The goal of the first scenario is to create Gold. 

Encounters

The map is a grid of encounters, each with an element that is both the theme of the challenge and the element you get as a reward. For example, if you move to the “Fire” space of the map you face the Phoenix. Encounters that start with “The” are not combats and are more like physical puzzles. 

To win the encounter, you must click on a verb on one of your elements that would defeat whatever puzzle or combat you are up against- for example, a way to defeat the Phoenix is to use the word “Flood” from the element “Water”. 

If you choose a verb that wins the encounter, a “SUCCESS” message will appear, you receive that element as a permanent reward, and the encounter is removed from the map. If you fail three times in a row, you must leave and try another encounter before you are allowed to try again. You will receive a hint on the first and third failures. It is also possible to get a “half-success” for verbs that kind of work but not completely. Two half successes equals one success. 

Fusing elements

In order to create a new element, click on two elements in your reagents row and click the “fuse” button. The first element you clicked on will be temporarily deactivated as a cost. If you want these back, you can click “Untap all”, which gives reactivated all your elements but gets rid of all the new elements you have created in the products row. Some combinations of elements are not possible and will be highlighted in red when you select them. Some elements with a special symbol are final products and cannot be used to make any new fusions. 


Improvements roadmap: 

Improve rules and add visuals

Reagents wrap

Maybe warn player that they can't win that room with what they have, or unlock rooms when they are possible

If reward is in products it should move it to reagents or else it locks them out

If element already exists in reagents warn but don't tap

Half successes bugs

Move encounter element to bottom

Row hints, done when completing of the bottom row of encounters?

New encounter set and solutions and scenario select

final room hints system (completing a full row or column gives you the next hint for the final room, each sentence is a new hint).: (The Alchemist's Endgame: There is a shining, unbreakable door, in order to proceed you will need to provide the ultimate, most prized creation. They say it is a material that shines with the very essence of the sun. The sun is fire in the sky. The sky is clouds and air. Clouds are steam and air, steam is water and air, try to piece this all together into a metal that shines like the sun. You will need to give it gold which can be formed by combining sun and metal. )   
UI Improvements and bug fixes
Basic art for each encounter
Basic website elements or security (contact, privacy, etc)
Save and reset game
rules improvements and tutorial images
Set 2 and 3 of encounters (to be provided later)
Scenario 2,3,4,5 of endgame rooms (to be provided later)
