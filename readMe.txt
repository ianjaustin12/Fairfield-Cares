Instructions on how to use/edit the code

Navigation/Header
1. All of the information for the navigation is within the “header.js” file. This is a script that creates a constant element called “header-component”. This file is fairly easy to navigate to the correct spot in. Whichever page or drop down you are trying to change will have a comment starting with “<!--” and ending with “-->” in between this will be the name of the page or dropdown below it. 
2. To add a new page you must add:
<li><a href="PageLink.html">Page Name </a></li>
The page link will be the file name + .html and the page name will be whatever name you wish to be displayed. 
3. To remove a page: 
You must find the respective location as shown in 1 and then from there find the line like <li><a href="PageLink.html">Page Name </a></li>, where the page name is the page you are looking for. 
Then simply delete that line of code.

Minutes
1. First add the pdf file to the folder labeled “Minutes”. Under the correct Year folder.
2. Then go to the “minutes.html” file.
3. Find the year under the comment that will look like this 
“<!---------------------YEAR: 2021--------------------------------------->”
4. Under that there will be a few lines of code. You want to look for the lines:
<ul id = "minutesList"> and </ul>. You will place your new file in these lines.
5. Copy this line:
<li id = "minutesLink"><a href="/Minutes/YEAR/FILENAMELINK.pdf">FILENAME</a></li>
6. Change FILENAMELINK to the exact name of the file in the folder. And change FILENAME to however you would like the file to appear on the site. And change YEAR to the year you placed your pdf under ie. “2021”
7. Place this new line in between the two lines mentioned in step 4.

Agendas
1. First add the pdf file to the folder labeled “Agendas”. Under the correct Year folder./
2. Then go to the “agendas.html” file.
3. Find the year under the comment that will look like this 
“<!---------------------YEAR: 2021--------------------------------------->”
4. Under that there will be a few lines of code. You want to look for the lines:
5. <ul id = "agendasList"> and </ul>. You will place your new file in these lines.
6. Copy this line:
<li id = "agendasLink"><a href="/Agendas/YEAR/FILENAMELINK.pdf">FILENAME</a></li>
7. Change FILENAMELINK in to the exact name of the file in the folder. And change FILENAME to however you would like the file to appear on the site. And change YEAR to the year you placed your pdf under ie. “2021”
8. Place this new line in between the two lines mentioned in step 4.


General Content
1. Find the name of the respective page you wish to change and open that file. If you cannot match the name on the website with the name of the file, then go to the header.js file and press Control and f and search the name of the page. It should take you to a portion of the code that resembles <li><a href="PageLink.html">Page Name </a></li>, where the Page Name is what you searched then the PageLink is going to be the name of the file you are looking for.
2. Once you have the correct file for the page open then search again by pressing control and f. Search for the text or a portion of the text you wish to change to find the location on the file. Then just simply delete and type over whatever you would like to change.
3. ***NOTE*** do not delete or change anything within “<” and “>” tags or it will cause errors. If you accidentally delete something within these tags and do not know what you changed, then close the file and do not save and reopen it and try again.

Images
1. To replace an image in every instance on the site.
   1. Go to the Images folder.
   2. Find the image you wish to replace.
   3. Copy the name of the image.
   4. Rename your new image to the old image's name.
   5. Delete the old image from the folder.
   6. Place the new image in the images folder.
2. To replace a page on a certain page.
   1. Go to the images folder and find the image you wish to replace.
   2. Copy the name of the image.
   3. Find the page you wish to replace.
   4. Open that file.
   5. Search the file by pressing “Control + f”. In the search bar put in the image name you copied.
   6. Replace the location that pops up with the name of the new image you wish to see in that location.
3. To replace a header image.
   1. Go to the images folder and find the image you wish to replace.
   2. Copy the name of the image.
   3. Go to the “coalition.css” document.
   4. Search the file by pressing “Control + f”. In the search bar put in the image name you copied.
   5. Replace the location that pops up with the name of the new image you wish to see in that location.

Footer
1. All of the information for the navigation is within the “footer.js” file. This is a script that creates a constant element called “footer-component”. 
2. To change the email simply change both instances of the email address in the footer.js file.