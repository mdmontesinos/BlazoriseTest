# BlazoriseTest
Minimal test repo associated with the following Blazorise issue --> https://github.com/Megabit/Blazorise/issues/3514

When starting the application, the LayoutHeader has a HorizontalHeight of 72px, when according to the Theme, it should be 50px.

In the first picture, it can clearly be seen that the header is bigger than it should be, and it goes over the the body.

However, when you wiggle around the debug console, essentially changing the screen size a bit, the header gets the correct height, 50px and remains like that until you reload the app again. This can be seen in the second image.

It seems that the initial size depends on the content of the header itself, because if I include an image or big logo in the BarBrand, it increases even more the size.

![image](https://user-images.githubusercontent.com/90258222/156901131-f72acd80-b4cd-4a72-b781-7f666e6d031d.png)
