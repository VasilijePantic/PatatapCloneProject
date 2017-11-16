--PatatapCloneProject--

PatatapCloneProject is a simple project with a point of recreating patatap.com.
This project combines paper.js and howler.js libraries.

Logic is very simple. When you press any letter key on the keyboard. Circle shrinking animation will appear on the canvas and it will be followed by a short sound.

Every circle will have random color that will change over time and will appearl on a random spot on the canvas.

Every sound is already binded to all the letter keys.

All circles are being stored into an empty array. A circle will be removed if the next random circle takes place on the same field unit on the canvas so the number of circles is finite.

Code example:

-var keyData = {
	q: {
		sound: new Howl({
  		src: ['sounds/bubbles.mp3']
		}),
		color: '#1abc9c'
	},
	w: {
		sound: new Howl({
  		src: ['sounds/clay.mp3']
		}),
		color: '#2ecc71'
	},
	e: {
		sound: new Howl({
  		src: ['sounds/confetti.mp3']
		}),
		color: '#3498db'
	}
		...
};

This project is a final piece of the front-end development part from the Udemy's "Web Developer Bootcamp" that I'm currently working on.

