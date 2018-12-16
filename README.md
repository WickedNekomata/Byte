# BYTE

Byte is a management demo-game developed by <b>Sandra Alvarez</b> and <b>Guillem Costa</b> for the AI subject under the supervision of the lecturer <b>Ricard Pillosu</b>. The game uses our <b>own steering behaviours</b> (using Recast to generate the path) and Node Canvas for the <b>behaviour trees</b>.
 
In Byte, you take the role of the manager of a burger fast food restaurant (aka diner).
Will you be able to bring the success to your new business or will you throw in the towel? Play with the likes!

For a detailed description about the game as well as of the behaviour trees being used, please check our repository:

- <b>BitBucket repository</b>: https://sandruski@bitbucket.org/wickednekomata/byte.git
- <b>BitBucket wiki</b>: https://bitbucket.org/wickednekomata/byte/wiki/Home
- <b>BitBucket BEHAVIOUR TREES (wiki page)</b>: https://bitbucket.org/wickednekomata/byte/wiki/Behaviour%20Trees

> Download the latest release HERE

## The Team

<i>Alvarez Sandra, code and design:</i>

	- Github Account:
	- Bitbucket Account:
	
<i>Costa Guillem, code and design:</i>

	- Github Account:
	- Bitbucket Account:

## About the game

### Objective

Earn 15 likes without going bankrupt.

Be careful with the mood of the clients. Several things can happen:
- If they are ordered food being happy, they will pay and leave a LIKE!
- If they are ordered food being neutral or annoyed, they will only pay.
- If they get angry, they will leave the diner and leave a DISLIKE!

Also, be careful with the number of likes, since it affects the amount of clients that go to the diner.
The higher it gets, the more clients will come.

### Player interactions

1. Buy ingredients by clicking on the shopping cart icon (bottom left of the screen).
 
There are 3 types of ingredients to cook 3 types of meals. Each of them has a different effect:
- Hamburguer with chips: it has no special effects.
- Nuggets: faster to cook.
- Cake: it makes clients instantly happy.

Each type of meal can only be cooked by a cook specialised in its type in a specialised cooker.

*The ingredients bought appear in a menu on the bottom of the screen. E.g.: cake 1/10: you have cooked 1 cake and you have 10 ingredients to cook 10 more cakes.

2. Buy more workers by clicking on a box. 
- If the box corresponds to a cash register, you will buy a new waitress.
- If the box corresponds to a cooker, you will buy a new cook. There are 3 types of cookers (hamburguers, nuggets and cakes), corresponding to the 3 types of meals.

At the start of the game, the diner has only 2 workers, a waitress and a cook. This cook is specialised in cooking Hamburguer with chips.

*The meals cooked appear in the menu in the bottom of the screen. E.g.: cake 1/10: you have cooked 1 cake and you have 10 ingredients to cook 10 more cakes.

3. When a client is sat, order food for them by clicking on them. A menu with the different types of meals will appear on the bottom left of the screen.
You can only order meals that you have cooked.

### Controls

- Up, Down, Left and Right arrows: move the camera
- Move mouse towards the sides of the screen: move the camera
- Click: 
	- On a button: perform an specific action
	- On a client: open their own menu to order food for them
	- On a box: buy a cash register (with a waitress) or a cooker (with a cook)
- F1: restart game

### Tools used

- Unity 2018.1.6f1
- NodeCanvas for Unity

### Assets

Models are from Simple Assets, available in the Unity Asset Store. The rest of the assets (UI, music and sounds) are royalty-free.

## License
```
MIT License

Copyright (c) 2018 WickedNekomata (Sandra Alvarez & Guillem Costa)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
