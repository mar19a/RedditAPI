# RedditAPI

![](redditapiprogram.gif)

How did I accomplish this. Used Jsoup tk set the base url which is "https://old.reddit.com/r/" and add the sub name that was passed by the user from the textfield. This is then stored into variable name doc which has a ty[e document.

Then we get variable doc, and store the headline of each reddit threat by using doc.select("p.title") and store it in variable el which is an Elements type.

Then we get variable doc and store upvotes of each reddit threat and store it in variable score which is an Elements type.

Then I created an for loop which set headline text to headline buttons and score to votes buttons.

All reddit threads are from the "Hot" sections




![](reddit.gif)
