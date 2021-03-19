# mylinks

***** OPEN SOURCE code for managing your profile links of all social media. On very simple HTML and CSS based. *****

Since I've made this for everyone I'm gonna write the 
instructions as if you know avery little of HTML and CSS.

Every link , name and photo has a class associated with it in the HTML document 
and those classes give their elemnet styles.

******************************************************************************
                         -------------------->> Change the Background Photo of whole page :  <<--------------------
    1. Copy your photo into the images folder.
    2. Delete the photo that's already in it.
    3. Rename your photo to "background" .

                        -------------------->> Change the Profile Picture :  <<--------------------

    Steps to change Profile picture :
    1. Copy your photo into the images folder.
    2. Delete the photo that's already in it.
    3. Rename your photo to "profilepicture" 
    
    That's it.


                        -------------------->> Change the Profile Name :  <<--------------------

    1. Open "index.html"  file from html/index.html.
    2. Go to Line 20* or class="profile-title"
    3. Change your Profile name.    

                -------------------->> Change the Color of Profile Name :  <<--------------------

    1. Open "index.css" file from css/index.css
    2. Go to Line 33*  or " .profile.title span "
    3. Delete the " /* */ " characters from both sides of color.
    4. Now choose any color of your choice.
    5. Hex codes of colors are more preffered. 

        Similarly, font family or typeface can be changed.


                -------------------->> Change the Name of Link :  <<---------------
    
    1. Open "index.html"  file from html/index.html.
    2. Find class="links ........"
    3. Now Change the Link 1, Link 2 ......to your wish.
    4. That's it.

                -------------->> Change the Address of Link :  <<-----------------
    
    1. Open "index.html"  file from html/index.html.
    2. "Find <div class="links-row ........">"
    3. Then go inside <a class="links .......>
    3. Now Change the address inside href=" .... " to your wish.
    4. That's it.

    Tip:  Remove target="_blank" if you want the link to open in same window.


         -------------->> Change the Background Color of Link button :  <<-----------------

        1. Open "index.css" file from css/index.css
        2. Go to Line 56* or ".btn" .
        3. Now find " /* Background: white */
        4. Remove the " /* " characters from both sides.
        5. Now change the color to your wish.
        6. Hex codes of colors are more preffered. 

         -------------->> Change the Hover action of Link button:  <<-----------------

         1. Open "index.css" file from css/index.css
         2. Go to Line 66* or " .btn:hover " 
         3. CHange the background color to your wish.
         4. Hex codes of colors are more preffered. 
