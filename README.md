# YouTrackToggleSwimlanes

1. Add a Bookmark in your browser
2. In the URL field of the bookmark paste the following:
```JavaScript
javascript:(function(){document.querySelectorAll(".yt-agile-table__row-title__summary__text").forEach((lane) => {lane.click()});})();
```
![toogleSwimlanes01](https://github.com/user-attachments/assets/65c681c6-8818-4c42-a645-c4d9f9863b2b)
3. Navigate to your YouTrack board
4. Click the bookmark and the swimlanes should toggle open/closed state
