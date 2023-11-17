Can you CREATE a static website using only HTML, CSS, JS, and jQuery ? I just want a perfect replica of 2 pages: the homepage and the services page, i do not want the others pages. Photo of what i want exactly are in the folder mockup. So YOU MUST CREATE THE WEBSITE FROM THE TEMPLATE IMG IN THE MOCKUP FOLDER AND ADD TRANSITION AND ANIMATIONS FROM THE ORIGINAL WEBSITE.

 Here's the original  website with effect and transition that you need to reproduce: https://barbershop.framer.website/

THE PROJECT NEED TO FOLLOW SOME RULES:

Project architecture:
-Use the project tree I created with my files and folders

The colors:
-just pick the same color form the original website cause i don t have all the exact rgb code color

The file tree:
-juqs use the project structure i gave you with the same folder and files


The text:
-just use lorem ipsum or copy the text from the original website


The police:
-i don t have them so find them or something that looks likes almost the same on google fonts

In all files:
-DO NOT USE any frameworks


In js files:
-USE js native and if u need a library use jquery 
-DO NOT USE react or node


In the html files:
-DO NOT USE bootstrap or tailwind


In the css files:
-USE flex not grid
-NEVER USE !important;
-create in the css files something like that and reuse those variables in every element to style, so if
 u edit this variable for example it allows u to edit all u re css automaticly where those variables are used:
 :root {

  /**
   * COLORS
   */

  --gold-crayola: hsl(38, 61%, 73%);

  /**
   * TYPOGRAPHY
   */

  /* font-family */
  --fontFamily-forum: 'Forum', cursive;
  --fontFamily-dm_sans: 'DM Sans', sans-serif;

}

exemple: Allbtn{
	  color: --gold-crayola;
	}

