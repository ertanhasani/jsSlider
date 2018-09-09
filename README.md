# jsSlider
jsSlider is a jQuery Slider Plugin that works with Bootstrap (v.3).

Give it a height in pixels (number) and it will center all images either if they are smaller or not.

# How to use it
> In order to use it, you should already have imported `Bootstrap v3 CSS` or `Bootstrap v4 CSS` and `jQuery` in your project.

> TESTED IN GOOGLE CHROME, MOZILLA and MICROSOFT EDGE with lastet versions!

Add a `div` inside your with an `id` or a `particular class`. Ex. 
```
<div id='mySlider'></div>
```

Then in you javascript add an create an array that will contain objects with `src` and `alt` properties. Ex.
```
var images = [
    {src: 'images/image1.jpg', alt: 'image1'},
    {src: 'images/image2.jpg', alt: 'image2'},
    {src: 'images/image3.jpg', alt: 'image3'},
    {src: 'images/image4.jpg', alt: 'image4'},  
    {src: 'images/image5.jpg', alt: 'image5'}
]
```

Then just call `jsSlider` function to that `div`. `jsSlider` function takes two parametres: first one takes the object with the images, and the second one takes height (in pixels) of slider (like how many pixels do you want its height).
```
$('#mySlider').jsSlider(images, 500);
```
Or you can use it by just giving images object as parameter, and the height will be taken from the largest image.
```
$('#mySlider').jsSlider(images);
```


And then it will look like this:
![Home Page](https://image.ibb.co/fv45up/image1.jpg)


Here's what it looks like on a real project
![Home Page](https://image.ibb.co/mnXm0U/image2.jpg)
![Home Page](https://image.ibb.co/epKAS9/image3.jpg)
