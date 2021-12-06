# Quote-of-the-Day
Hey friends, today we learn how to Build A Random Quote Generator in HTML CSS & JavaScript
Random Quote Generator used to generate random quotes.
 In this Random Quote Generator project,
 there is a quote that will be changed randomly,
 a button,
 and some icons.

Each time you click on the new quote button,
 you’ll get a new quote.
 You can also convert a quote to speech, copy a quote,
 or share a quote on Twitter by clicking the given button.
 
In the project,
 we see the demo of this random quote generator 
 and know how I created it using HTML CSS & JavaScript. To show random quotes,
 I used a free API named quotable (https://quotable.io/random). 
 we can use any other API for this project.
 
 let’s understand the main JavaScript codes and concepts behind creating this random quote generator.
 In the JavaScript codes, 
 first: I called a randomQuotes() function on the new quote button clicked.

Inside this function,
 using the quotable API I fetched the random quotes and showed them on the Quote App.
 Second: for the TTS (Text To Speech) functionality,
 there is no external API is used and it’s possible with the Web Speech API of JavaScript.

Third: to copy the quote,
 I used the writeText() property of the navigator object.
 Last: for sharing to Twitter,
 I passed the quote text in the Tweet URL,
 and using the window open() method,
 I opened this URL in the new tab.
