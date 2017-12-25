

	var count = 0;

	function checkCount (count) {
		count++
		if (count % 2 == 0) {
			color = ''
		}
	}

	

		// var count = 0;

// function colorBox () {
// 	count++;
// 		if (count % 2 == 0) {
// 			// square is yellow
// 		} else {
// 			// square is red
// 		}
// }









	this.src="images/red.jpg"



*** Make two arrays (red) (yellow), on click push to the appropriate array, if the array contains one of the "connect four" patterns, that player wins ***

*** Maybe use .contains inside the arrays ***


//  *** need to call a function to check to see if four are connected



*** MIGHT NOT NEED THIS ***

	function checkSquare (id) {
		console.log(this.id);

		if (this.id == "a1") {
			a1.removeEventListener("click", checkSquare);
			a1.src="images/red.jpg"
			document.getElementById("b1");
			b1.addEventListener("click", checkSquare)
		} else if (this.id == a2) {
				a2.removeEventListener("click", checkSquare);
				a2.src="images/red.jpg"
				document.getElementById("b2");
				b2.addEventListener("click", checkSquare);	
		} else if (this.id == a3) {
				a3.removeEventListener("click", checkSquare);
				this.src="images/red.jpg"
				document.getElementById("b3");
				b3.addEventListener("click", checkSquare);
		}
	}


