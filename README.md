help-needed
===========

//Remember to set your condition outside the loop!
var count = 0;
var loop = function(count){
	while(count < 3){
		console.log("I'm looping!");
		loop = false;
	}
};

loop();
