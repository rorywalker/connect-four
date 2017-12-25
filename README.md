# connect-four

when i click on a1 the img file is replaced with images/red.jpg and then the a1 square becomes inactive and the b1 square becomes active.
when i click on b1 (after a1) or any other a's (a2, a3, etc.) the img isn't replaced. in debugger the src in b1.src is undefined. i do 
not understand why. 

i tried using this.src and i get the same result. 
__________________________________________________________________________________________________________________________________________

 		switch (this.id) {			
 			case "a1":
 				a1.removeEventListener("click", checkSquare);
 				a1.src="images/red.jpg"
 				document.getElementById("b1");
 				b1.addEventListener("click", checkSquare)
 				break;
 			case "a2":
 				a2.removeEventListener("click", checkSquare);
 				a2.src="images/red.jpg"
 				document.getElementById("b2");
 				b2.addEventListener("click", checkSquare);
 				break;
