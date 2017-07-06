# showTrelloCardNumbers
Bookmarklet that shows the numbers of [Trello](http://trello.com/) cards.

![Numbered card sample](Trello-Card-Numbers.png)

#### Bookmarklet
Add the bookmarklet by selecting and dragging it to your bookmarks bar. Then go to your Trello Board and click the bookmark to toggle the numbers.

```javascript
javascript:void(function(){var o=$(".card-short-id");o.each(function(){$(this).text($(this).text().replace("#","").replace("#","").replace("N.%C2%BA ", ""))});o.hasClass("hide")?o.removeClass("hide").css({"font-weight":"normal","font-size":".8em","margin-right":"5px",padding:"2.3px 6px",background:$("body").css("background-color"),"border-radius":"10px",color:"#f6f6f6"}):o.addClass("hide")}());
```
