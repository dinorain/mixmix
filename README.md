# Mixmix

A multi-player, multi-screen game built to experiment with Socket.IO and Node.js. It reuse the concept of Mixmix, a party-game included in the game JackBox Party Pack 2.

The game is available at https://mixmix.herokuapp.com/

## To Install

1. Ensure Node.js is installed
2. Clone this repository - `git clone https://github.com/Minious/mixmix.git`
3. Install the dependences:
    1. `cd mixmix`
    2. `npm install`
4. Start the server: `node index.js`
5. Visit http://127.0.0.1:8080 in a browser and click CREATE.

## To Play

### Setup
1. Ensure at least 3 devices are on a local network, or that the application server is accessable by at least 3 devices.
2. Start the Anagrammatix application
3. Visit http://your.ip.address:8080 on a PC, Tablet, SmartTV or other large screen device
4. Click CREATE
5. On a mobile device, visit http://your.ip.address:8080
6. Click JOIN on the mobile device screen.
7. Follow the on-screen instructions to join a game.
8. Find an opponent and have him/her repeat steps 5-7 on another mobile device.

### Gameplay
1. On the large screen (the game Host), a sentence with a missing word will appear.
2. On each players' devices, a text field appears.
3. The players must provide a ploy which has to be credible.
4. One each players send their ploys, the game host and the players' devices display the ploys and the real answer to the sentence.
5. The player who taps the correct answer gets 10 points and if a player choose a ploy, the player who provided it gets 5 points.
6. The player with the most points at the end of the game wins!
