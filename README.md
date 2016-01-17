[online website]:https://ramonaza.github.io/RamonFeed/ "the online website"
[css file]:https://github.com/ramonaza/RamonFeed/blob/gh-pages/styles.css "the css file"
# Welcome to your RSS Feed gh-pages branch!
### What is this branch?
To put it simply, this branch allows us to host an [online website] with your own RSS feed, and update it automatically!  
If you want to change the styling of the website&mdash;no problem! Just head over to the [css file] and modify it!  
Note that this website might take a few minutes to update after every change to your RSS feed

### How can I use this branch?
Once you have styled the event feed from the [css file] to your liking,  
you can include your RSS feed inside your own website by adding the following tag:

```html
<iframe src="https://ramonaza.github.io/RamonFeed/" id="rss-feed-frame"></iframe>
```

into your html, and then by changing the element's width and height accordingly