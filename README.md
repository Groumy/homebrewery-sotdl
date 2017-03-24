# homebrewery-sotdl
An alternate CSS to make brew on Homebrewery looks like the Shadow of the Demon Lord products.


## How to use it
* Go to [The Homebrewery](http://homebrewery.naturalcrit.com/)
* Create a new Brew
* At the top of your brew simply paste the following line : 
``` html
<link rel = "stylesheet" type = "text/css" href = "https://rawgit.com/Groumy/homebrewery-sotdl/master/homebrewery-sotdl.css" />
```

## Making it you own
If you'd like to make changes in you own repo and use it, don't forget to change the url for the font-family in the `homebrewery-sotdl.css` file and link tag.

I use [Rawgit](https://rawgit.com/) to help out with that, but you could also use your [own page](https://pages.github.com/) and integrate this as a [git submodule](https://github.com/blog/2104-working-with-submodules).

### Example 
``` css
@font-face {
  font-family: 'First Order';
  src: url('https://rawgit.com/Groumy/homebrewery-sotdl/2bf4f06d/fonts/firstv2.ttf?raw=true')
}
```
Change the `Groumy` part of the URL with your user name
``` css
@font-face {
  font-family: 'First Order';
  src: url('https://rawgit.com/**Your User Name**/homebrewery-sotdl/2bf4f06d/fonts/firstv2.ttf?raw=true')
}
```
