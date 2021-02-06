# HoriseonCodeRefactor

## Description

In this assignment, we were tasked with refactoring a website's code to make it more accessible. Making a website more accessible not only attracts more users and potential customers, but also makes it search engine optimized, meaning search engines will place the website higher on the results list.

Search engine optimization covers a broad spectrum of topics, but this assignment focused primarily on clarity for screen readers. This includes link titles, alt tags for images, text that the readers will understand, organization of layout, and HTML semantic tags. It's was good practice for learning how screen readers are used to access websites, and why it's so important to structure code with deliberate clarity.

Something I would have done in a client-based scenario is suggest changing some items. I would have mentioned to them that they should look into changing the colors on the "Horiseon" title of their website. The "SEO" is very low contrast and it's extremely likely users with color blindness would not see the difference at all. In addition, there is an issue with the same title where a screen reader is unable to read it all as one word. It would solve a lot of that issue if they changed it into an image instead of using code to put the text there. However, I did notice that the screen reader still reads it all as one word when doing a whole-page overview. It's only when the mouse hovers over it that the screen reader reads it in parts instead of a whole.

[Deployed Website](https://ashleyaggie.github.io/HoriseonCodeRefactor)

![Top picture of website](/assets/images/WebsiteBottom.png)

![Middle picture of website](/assets/images/WebsiteMid.png)

![Bottom picture of website](/assets/images/WebsiteBottom.png)

## Changes Made

GIVEN a webpage meets accessibility standards

WHEN I view the source code

THEN I find semantic HTML elements

    * Changed all divs to semantic elements, ex. main, section, aside, etc.

WHEN I view the structure of the HTML elements

THEN I find that the elements follow a logical structure independent of styling and positioning

    * Includes an HTML declaration, head, body, and footer.

WHEN I view the image elements

THEN I find accessible alt attributes

    * Added alt attributes to all images in Markup.
    
    * Those that were in css or did not use a img tag were labeled with aria-label.

WHEN I view the heading attributes

THEN they fall in sequential order

    * Markup more or less already was in order.
    
    * Changed CSS to follow the same order as the Markup, and grouped like elements together.

WHEN I view the title element

THEN I find a concise, descriptive title

    * Added the company's title into the title element.

## Credits

Horiseon is a fake SEO services company used in the teaching of HTML5.

Assignment is part of the SMU Coding Boot Camp

## License

Copyright (c) 2021 Ashley Wright

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.