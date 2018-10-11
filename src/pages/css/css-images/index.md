---
title: CSS Images
---
# CSS Images
<p>This helps in adding an image to a website.</p>


####Code Sample</h4>

```<img src="picture.jpg" alt="Picture" width="100" height="100">```

* **src:** It consists the value of the path to the required image</li>
* **alt:** If the image is not displayed then an alternate text can be displayed using alt attribute.</li>
* **width:** This specifies a width for the image(can be percent or px or auto)</li>
* **height:** This specifies a height for the image(can be percent or px or auto)</li>


## Styling the image
There are many type of styling can be made to the image such as image border, polaroid image, responsiveness of the image, implementing the filters, adding text on the image, etc.

#### Border Radius
The border radus make the corner round.The radius of the corners need to be rounded in shape can be cahnged as per requirement.
Mostly it's delt in term of percentahe(%) and pixel unit(px).

```css
image_border{
    border-radius: 8px;
}
```

```css
image_border{
    border-radius: 50%;
}
```

-Giving the border radius 50% makes the image to take shape of an ellipse( in cae of square shape image the image formed will be circular in nature)

#### Polaroid Image
Basically in polaroid image the image is placed on the white paper(or the required color) which have the caption related to that image.

```css
div.polaroid {
    width: 70%;
    background-color: #ffffff;
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
}

img {width: 100%}

div.container {
    text-align: center;
    padding: 10px 20px;
}
```

#### Responsive Image
Responsive image means that the iamge will changes its width and height as per the shape and size of the device.
For samller devices the image should fit under the bounderies of the device.
```css
img {
    max-width: 100%;
    height: auto;
}
```
-Note:The above code can help to size down the image but it will never make the image larger than its original size.

For mor information and learning some new concepts refer:

[CSS Styling Images](https://www.w3schools.com/css/css3_images.asp)
