#Centered Template

This is a simple html template which consists of a main content horizontally and vertically centered, 
and a sticky footer that will remain at the bottom, for any given viewport size (widht and height).

A flexbox container is used to place the elements of the main content, 
and the footer will be stacked depending on the height of the flex container itself.

##Use

* Install sass
```
$ gem install sass
```

* From ./sass folder, compile site.scss
```
$ sass site.scss ../css/test.css -t expanded
```

* Enjoy index.html
