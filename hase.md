back

published on 31/12/18

# make mechanics & forget the game

People often ask me how I come up with ideas for my prototypes and games.<br>This text tries to answer that question.




**Think in terms of actions and reactions**

  I am assuming that *games are a series of causes and effects.*<br>
  - The player presses a button on the keyboard and the character moves. 
  - The character touches a button inside the game and a door opens.


  Certain conventions have arisen in game developement that we have internalised without realising it.
  
  *Arrow keys to move. tap to jump. click to shoot. e to interact. spikes kill you. <br> 
  death makes you respawn in the same level. etc etc*

Conventions are not necessarily bad, but they are conventions. <br>
Interesting stuff lies behind them.<br>
To explore these possibilities, it is important to consider that: <br>
*For every action, there is a reaction.*

  
  Please stay with me for a few short examples of actions and reactions.<br>
  
  - If you hold down the right arrow key, your character will move to the right until it runs into a wall.
  Both holding down the arrow key and the player being next to a wall are actions. They cause a reaction.<br>
  
  - If you click the left mouse button, your character shoots a bullet towards the cursor. 
  - The bullet gets destroyed when it hits a wall.
  Both the clicking of the mouse button and the bullet hitting a wall are actions. <br>
  They cause a reaction.
  
  
  - If you click the left mouse button, your character shoots a bullet towards the cursor. 
  - When the bullet hits a wall it gets destroyed and the player starts moving <br>
  towards the point where the bullet hit the wall.
  
  
  Both the clicking of the mouse and the bullet being destroyed are actions. <br>
  This time they even cause an interesting reaction.
  
  
Any action can trigger any reaction.<br>
A single action triggering multiple reactions can create interesting mechanics.


**Examine movement**

  I only make 2D games, which makes this a lot easier. <br>
  In 2D space, all movement can be expressed through two numbers:<br>
  - angle and speed.
  
  You can simulate complex movement by changing these numbers over time:<br>
  - Increasing speed is called accerlaration.
  - Rotating the angle of movement is called turning.
  - Inverting the angle of movement while decreasing speed simulates bouncing off of something.
  
  This might sound like super basic stuff, but thinking about movement in these terms <br>
  has enabled me to look at other games as a simple collection of movement sets.
  

**Look for Loops**

  Actions, reactions and movement are not taking place in a vacuum.<br>
  In conventional games, players expect to reach a goal and finish the game at some point. <br>
  To do that, they perform a set of actions  over and over again.<br>
  These repeated actions and their reactions can be called a core gameplay loop.<br>
  
  For example, here is the core loop of golf:
  - apply force to a non moving opject
  - object moves
  - object comes to rest
  - repeat until object is in the goal
    
  This is pretty basic stuff, and again it enables us to see games in a new light.<br>
  If one wanted to create a new take on golf, each of the steps of the core loop offers <br>
  concrete possibilities for deviation and innovation.<br>
  
  Here are some examples:
  - players can apply force to the object while it is moving
  - the object does not move, the goal moves
  - the object never comes to rest
  - the goal is to not let the object reach the goal for as long as possible
    
  Being able to recognise gameplay loops enables us to see games as a collection of actions<br>
  and reactions, each of which can be subverted to create a new core loop.
  
- **Prototype a lot**
  
  Prototyping is a skill that can be learned.<br>
  The only way to learn it, is to prototype.
  
  What has been incredibly helpful to me in this process is the fact that I can not code well.<br>
  Using visual scripting and an engine that has a lot of pre-build movement sets enables me to iterate pretty quickly over ideas.<br>
  When coming up with ideas by means of examing actions, reactions and movement, the results are often absolute garbage, <br>
  so it pays off to be quick in testing them.

  I also try my hardest to keep my projects very small, again increasing the speed at which I am able to iterate.<br>
  You can use your awareness of actions, reactions, movement and loops to come up with an endless<br>
  stream of mechanics for conventional games. 
  
  Anyways, here is the core loop of creative work:
  - attmept to do something
  - fail
  - despair
  - repeat
  
**Forget the game**

Creating innovative mechanics is fun, exciting and makes you feel very smart indeed.<br>
It is also pretty addicting.<br>
It is also only a small part of game developement.<br>
  
Much more challenging problems arise much later.<br>
There is no time to talk about that here, but please believe me:
  - finishing a mediocre game is better than to never finish a hundred great games

I used to think that I had to come up with extremely clever mechanics to make a good game.<br>
Downwell, VVVVVV, Braid, all the games I look up to, have incredibly unique and smart mechanics. <br>
I thought that had to have the same.<br>
  
So after prototying for months on end, a curious thing happened:
  - I got so used to making mechanics that I forgot how to make a game.
  
Being able to prototype interesting mechanics quickly is pretty neat, but it does not turn you into a good game developer.<br>
To become a good game developer, you need to develop games.
  
  
  
