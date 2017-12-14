# ComicBookChallengeMVC
The Challenge was to build a Master Detail Style Application using the comic book information that was already provided. Where each
comic book title is a hyper link that will take the user to the details of that given comic book. Another part of the Challenge is 
to setup the URL so it shows up as the /Home/Detail/bookIdNumber. 

One of the Challenges that I ran into was taking multiple characters in a comicbook and display them in the index page. 

The way I solved that problem is by using the Razer syntax in the index page, I created a variable for the characters 
and used the select method to get the name element of the character. I then created a second varaible called characterString were I 
used the String.Format method to add a "," as a separator between characters if there where more then one.
