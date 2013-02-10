__RealtimeMultiplayerNodeJS is a framework specifically for building HTML5 multiplayer games with the Client / Server model__  
  
## How to use
1. Download this repo
2. In the terminal type "node js/DemoHelloWorld/server.js"
3. Browse to "/DemoHelloWorld.html"

[!http://onedayitwillmake.com/blog/2011/08/creating-realtime-multiplayer-games-using-node-js/] Blog Post

[![DemoBox2D](http://farm6.static.flickr.com/5105/5694643562_fffce8b9cf_z.jpg)](http://farm6.static.flickr.com/5105/5694643562_53e54993dd_o.png)
         
# RealtimeMultiplayerNodeJS comes with 3 demos
### DemoHelloWorld
The most basic interesting working demo I could come up with. Objects move from left to right
![DemoHelloWorld](http://farm6.static.flickr.com/5309/5694599438_6fd56e21bd_b.jpg "DemoCircle")

### DemoCircle
A demonstration of the engine's simple CircleCollision engine, which can provide you with simple collision information and fires an event when two objects collide with the two objects.  
This demo __also shows one implementation__ of having a special kind of entity which is controlled by the keyboard from a connected user. __A character controlled entity__  
![DemoCircle](http://farm4.static.flickr.com/3483/5694599612_1cdb1f935e_b.jpg "DemoCircle")

### DemoBox2D 
This demo uses a [Box2D.js](https://github.com/HBehrens/box2d.js) implementation to create a world, and show's off the idea of synchronized physics, and taking advantage that all the simulation happens on the server.  
It also shows __synchronized interaction__ between multiple users, and an example of sending a message to the server which it interprets back into the game  
![DemoBox2D](http://farm6.static.flickr.com/5027/5694599478_7c9339c99c_b.jpg)
