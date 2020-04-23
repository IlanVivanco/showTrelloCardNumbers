# showTrelloCardNumbers
Bookmarklet that shows the numbers of [Trello](http://trello.com/) cards.

![Numbered card sample](Trello-Card-Numbers.png)

#### Bookmarklet

+ Drag the link below to your browser bar to create a bookmarklet:
  - [Show Card Numbers](//replace_this_by_JS.com)
+ Right Click on bookmarklet created and choose Edit
+ Paste the JavaScript code below into the URL field
+ Visit your Trello page to test the bookmarklet

```javascript
javascript:void function(){var o=$(".card-short-id");o.each(function(){$(this).text($(this).text().replace("#",""))});o.hasClass("hide")?o.removeClass("hide").css({"font-size":".8em","margin-right":"5px",padding:"2.3px 6px",background:"#ebecf0","border-radius":"10px",color:"#172b4d"}):o.addClass("hide")}();
```
