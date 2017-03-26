# homebrewery-sotdl
An alternate CSS to make brew on Homebrewery looks like the Shadow of the Demon Lord products.

## Live example

You can visiti [this brew](http://homebrewery.naturalcrit.com/share/r1WkLmer3g) that showcast every options of homebrewery and it's render


## How to use it
* Go to [The Homebrewery](http://homebrewery.naturalcrit.com/)
* Create a new Brew
* At the top of your brew simply paste the following line : 
``` html
<link rel = "stylesheet" type = "text/css" href = "https://groumy.github.io/homebrewery-sotdl/homebrewery-sotdl.css" />
```

## Making it you own
If you'd like to make changes in you own repo and use it, don't forget to change the url for the font-family in the `homebrewery-sotdl.css` file and link tag.

And don't forget to activate *Git Hub Pages* in your repo settings to quickly publish your file.

### Example 
``` css
@font-face {
  font-family: 'First Order';
  src: url('https://groumy.github.io/homebrewery-sotdl//fonts/firstv2.ttf')
}
```
Change the `Groumy` part of the URL with your user name
``` css
@font-face {
  font-family: 'First Order';
  src: url('https://**your user name**.github.io/homebrewery-sotdl/fonts/firstv2.ttf')
}
```
