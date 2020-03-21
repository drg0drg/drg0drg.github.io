

# Code Refactoring



The repo comprise Marketing Agency Horiseon page.

The task is to perform code refactoring for the page, addressing issues regarding the way code has been written.





## SYNOPSIS:

The page now features: 

    Semantic HTML

    Alt attributes for pictures

    Nav bar with links to
        Search Engine Optimisation
        Online Reputation Management
        Social Media Marketing

    Comments

    Proper indentation

    Proper styling on the frontispiece image 





 ## IN DETAIL: 

    HTML:

        Line19: Changed the div to nav semantic element.
        Line20: Changed UL to menu semantic element.
        Line38: Changed the div to section semantic element.
        Line39: Created an image id called "meeting" to be called in CSS. Used <object-fit: cover> in CSS to keep aspect ratio.
                Used Relative path to relink the frontispiece main image in HTML rather than CSS.
        Line45: Changed the div to "main" semantic element.
        Line46: Changed the div to "main" semantic element.
        Line54: Changed the div to "main" semantic element.
        Line62: Changed the div to "main" semantic element.
        Line74: Changed the div to "aside" semantic element.
        Line102: Changed the div to "footer" semantic element.
        Line106: Changed the h2 to h4.


    CSS: 
        Line59: Removed the background image and relinked it in HTML. 
                All the image related attributes deleted from this class.
        Line71: Calling the image class to stylise. 
                The attribute <object-fit:cover> keeps the pic's size & aspect ratio.
        Line111: All three classes feature the same style. 
                 All of them are called in the same time.
        Line124: All three classes/h3s feature the same style. 
                 All of them are called in the same time
        Line138: All three classes/images feature the same style. 
                 All of them are called in the same time.
        Line153: All three classes feature the same style. 
                 All of them are called in the same time.
        Line168: All images in the main section have the same height.
        Line178: All three classes feature the same style. 
                 All of them are called in the same time.
        Line196: The footer must use h4 as it's the least important on the page.

![Snippet](https://user-images.githubusercontent.com/60710786/77237289-c584e280-6bbe-11ea-9901-28f343aa5ab2.jpg)