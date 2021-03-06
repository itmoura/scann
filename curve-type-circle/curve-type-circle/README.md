# Description

Circle text is a simple jquery plugin to create text in circle shape. 

git : https://github.com/bable3/circle-text

# Init

```html
<div class="circle">My beautiful circle</div>
```

```js
$(".circle").circleText({
        glue: " ~~ ",
        turn: true,
        padding: 40,
        radius: 120,
        duration: 80,
        repeat: 2,
        background: "#f4af1b"
    });
```

## Result 

![Alt text](https://i.ibb.co/9NvHPYs/Capture.png "Circle text exampl")

# Settings

Option | Type | Default | Description
------ | ---- | ------- | -----------
content | string | "You forgot to include content ❤" | Content of the text, if you write in your html element the plugin use this content. If you set content in your Js it's gonne override the html content.
repeat | number | 1 | Number of time you want your content repeat.
glue | string | "" | String placed at the end of the content (used to separate repeats).
radius | number | 100 | Radius of the circle (px).
padding | number | 10 | Padding for the container don't set this in css (px).
background | string | "" | Color of background.
rounded | boolean | true | Set the border radius of the container at 50%.
turn | boolean | false | Make your circle turn.
duration | number | 10 | Duration of one rotation (s).
reverse | boolean | false | Set the rotation anticlockwise.

# Dependencies

jQuery 1.8

# License

Licensed under the MIT license.

Copyright © François Faucon
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

The Software is provided “as is”, without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose and noninfringement. In no event shall the authors or copyright holders be liable for any claim, damages or other liability, whether in an action of contract, tort or otherwise, arising from, out of or in connection with the software or the use or other dealings in the Software.
