# Instagram API
This project is a website that contains a button that users can click on that will send them to instagram's log-in page where they give access to the website to view their instagram content. They're then redirected to the website where their instagram photos taken at the current tag location are displayed.   


## How It's Made:

**Tech used:** 
*HTML
*CSS
*JavaScript jQuery 
*Node

In HTML I put an authoriztion code link in an anchor tag. That authorization code link contained the access token that sent a request to intagram and then took the user back to the redirect uri.
I used JS to to request the images taken at the curent tag location and node to run the request on localhost8000 on the browser. 


