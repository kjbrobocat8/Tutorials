## Tutorials.
All of these will be in HTML.
# Create your first web page
```html
<!DOCTYPE html>
<html>
  <head>
    Hello world
  </head>
</html>
```
Make this a file named 
``` index.html ```
and double click it to open it.
Sure, it's no Google, but we'll work on styling once you get it set up.
> Put the text you want to show up on your page.
once that's done, move on to the next step.
# The Next Step
## Styling it
Next, create a file named ```style.css ```
And get your preferred font from [Google fonts](fonts.google.com).
Example: *Roboto Font*
```html
Add this into ```index.html```
<link rel="preconnect" href="https://fonts.gstatic.com">
<link href="https://fonts.googleapis.com/css2?family=Roboto&display=swap" rel="stylesheet">
```

And this into ```style.css```:
```css
head {
font-family:Roboto; /* or any other font */
}
```
And Look at your website.
# Additional thingies
# Frameworks.
Two frameworks are provided here, Bootstrap, and Material Design.
They help make the web easier to develop.
## Bootstrap
Copy and paste this into your ```index.html``` file.
Yep, *all* of it.
```html
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-giJF6kkoqNQ00vy+HMDP7azOuL0xtbfIcaT9wjKHr8RbDVddVHyTfAAsrekwKmP1" crossorigin="anonymous">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta1/dist/js/bootstrap.bundle.min.js" integrity="sha384-ygbV9kiqUc6oa4msXn9868pTtWMgiQaeYH7/t7LECLbyPA2x65Kgf80OJFdroafW" crossorigin="anonymous"></script>
```
That's It!
for more info on components, visit Bootstrap at [This is an accordion tutorial bc I didn't quite know why not](https://getbootstrap.com/docs/5.0/components/accordion/)
## Material design
```
<link href="https://unpkg.com/material-components-web@latest/dist/material-components-web.min.css" rel="stylesheet">
<script src="https://unpkg.com/material-components-web@latest/dist/material-components-web.min.js"></script>
<link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">
```
again, copy and paste to ```index.html```


## Other tutorials
Other tutorials, such as making games, and other languages, are coming soon!
