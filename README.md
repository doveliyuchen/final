Final

This game is designed in Canvas and socket.io.
If you have ever played a game called Feeding Frenzy(https://feeding-frenzy-game.en.softonic.com/). I was inspired by this game and another game I recently played a lot called Raft (https://raft-game.com/). So I decied to make a simple game in theme of sea. My first thought was about pirate grabing golds in the sea. But I make the only gold in the canvas which is blue and the background is much more similar to the undersea. So I then decided to make it as a fish game. We are different kinds of fish to fight with a bite. 

The movement is tricky here, I added an acceleration with the original direction before it was broadcasting to the server. It will cause some delay of movements. So the control is harder and gives players more feeling of underseas.
The UI design was also important in this game because it is a muti-player game. I firstly designed notify people with underlines, but then I found it is not a good way to show them. 
The introduction is also another thing I didnt realize until the play testing. People tend to use wasd keys to control it, and some of them don't know how to control it at all. Maybe they are not gamers. 
The game itself is not so difficult to be coded, but the UI is so hard. I assign different players based on their socketid differnt colors. But I messed up the order in some versions, so it shows the wrong color of each player. I have to debug it and it took me 2 hours to figure it out, even though it is super easy.. Also, because of the size of my screen, the size of canvas is also very tricky for me, I have to make it tinier and fits others' screen. So the arrow keys will not cause the up and down in the window. 

After the playtesting, I then designed the fish from simple shapes, but in the further developments, I will implement pictures and animations. I used some animations to change the value of score on the page, but I hope I could use more.
I will also add a timer to end the game, and a start page the start the page together.

Thanks to my dad's debugging, or I will take more time on debugging it. 
https://platinum-mirage-pine.glitch.me/
https://github.com/doveliyuchen/final
https://docs.google.com/presentation/d/1Su6-C5egt36F2S5us5L27ehzDvUZOreQlZrygr3ItUQ/edit?usp=sharing