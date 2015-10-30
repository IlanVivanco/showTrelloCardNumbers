# showTrelloCardNumbers
Bookmarklet that shows the numbers of [Trello](http://trello.com/) cards.

![Numbered card sample](numbered_screenshot.png)

#### Bookmarklet
Add the bookmarklet by selecting and dragging it to your bookmarks bar. Then go to your Trello Board and click the bookmark to toggle the numbers.

```javascript
javascript:!function(){var o=$(".card-short-id");o.hasClass("hide")?o.removeClass("hide").css({"font-weight":"bold","font-size":".8em","margin-right":"7px",padding:"2.3px 6px",background:$("body").css("background-color"),"border-radius":"2px",color:"#f6f6f6","border-bottom":"1px solid rgb(0,101,171)"}):o.addClass("hide")}();
```