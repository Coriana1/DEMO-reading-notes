# Video and Audio Content
1. Explain how the ability to use video and audio on the web has evolved since the early 2000s.
  - There used to be competition between CDs and flashdrives, auto tune was very popular, and digital platforms such as youtube and myspace were just introduced along with spotify and apple music. 
2. Describe the use of the src and controls attributes in the <video> element.
  - You can use the <source> element instead of the URL to specify the video to embed, and controls offers control to allow users to do video playback, pause/resume, and volume. 
3. Why is it important to have fallback content inside the <video> element?
  - It's needed for the content to be used when the external resources can't be used. (usually due to unsupported format)
4. Write a very short story where <audio> and <video> are characters.
  - **Once upon a time there was a little webpage named <video> and her whole life she lived on a sate of mute. She yearned to hear the sounds of the beautifly clicking birds of a mouse, or to be able to enjoy the laughs some of her family shared over TikTok videos. She would try and try and try but still nothing, until she was granted a wish from the <source> fairy. She wsihed to be able to hear in exchange for her ability to dance, and by the morning she had a new friend on her ears called <audio> that would be apart of her for life.**


## A Complete Guide To Grid
1. How does Grid layout differ from Flex?
  - Flex was designed for one dimension rows or colums and grid for two dimenstional. 
2. Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.
  - *Grid container*: defines a grid layout with rows and columns
    *Grid item*: specifies item's size and location within a grid colomn by addind a line/span/or nothing to it's grid placement
    *Grid line*: the lines between columns 
## Responsive Images
1. Besides making a site visually appealing across different screen sizes, why should developers make images responsive?
  - Helps deliver optimal file size, right image for right screen, and allows access to content across multiple device resolutions.
2. Define the following <img> attributes srcset and sizes. Write an example of how they are used.
  - srcset: specifies the URL of the image to use in different situations. 
    <picture> (*element with two source files*)
  <source media="(min-width:650px)" srcset="img_pink_flowers.jpg">
  <source media="(min-width:465px)" srcset="img_white_flower.jpg">
  <img src="img_orange_flowers.jpg" alt="Flowers" style="width:auto;">
</picture>
    - sizes: specifes the size of icons for visual media
    Icon with specified size: <link rel="icon" href="demo_icon.gif" type="image/gif" sizes="16x16">
3. How is srcset more helpful for responsive images than CSS or JavaScript?
  - Allows you to define a list of different sized version of the same image and information about the size of all of the images.