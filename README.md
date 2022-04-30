# Code Refactor Starter Code
For index.HTML
1/The title of the html web page might need to change to Horiseon,so the browser understand they who is the agency they are currently contacting (or reading) with.   
2 /I realize that the <header> and <footer> is kind of betterversion for <div class="header"> and <div class="footer">, for shorter and easier for futher editting and debugging.
3/ In the <header> tag has some <a href=""> tags, so I want to see the tag works when I click on the link on browser, after knowing it is not working for the <a href="#search-engine-optimazation"> I scroll down and figure out that at <div class="search-engine-optimization" > should be <div class="search-engine-optimization" id="search-engine-optimization">, after changed, the link direct me to the needed division.
4/ As the challenge requirement all the alt attributes are added for all <img> tags.
5/ Considering <div> and <section> are not needed to switch, so I don't change much on these element.
For Style.css
1/ I change all style .header and .footer to header and footer, accordingly to the #2 Code Refactor above.
2/ There are some repetition (etc. style for .search-engine-optimazation and .online-reputation-management), I make some change include:
        1-I find out that class .search-engine-optimazation, .online-reputation-management and .social-media-marketing are having the same style attributes. Thus I deleted all above classes and add class .content-factor with the same attriburtes to replace the deleted classes.
        2- I find out that class .benefit-lead, .benefit-awareness and .benefit-cost are having the same style attributes. Thus I deleted all above classes and add class .benefit-factor with the same attributes to replace deleted classes.
