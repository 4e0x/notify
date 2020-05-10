# Notify
Nice little Notification alerts with a simple animation without writing any HTML code, Dosen't even require Jquery!!.

## Getting Started
Download the distribution and include the file in your pages!

```html
<script type="text/javascript" src="pathtontfy.min.js"></script>
<script>ntfy.init(),ntfy.ntfy(type,position,title,message);</script>
```
## YES! That's it you are all set.

## Options
+ Types
    + success
    + error
    + warning
    + info
    + fav
    + notification
    + date
    + pending
    + printing
    + filecopy
+ Position
    * top-left
    * top-right
    * bottom-left
    * bottom-right
    * bottom-left
    * top-center
    * bottom-center

## Example
```html
<script>ntfy.init(),ntfy.ntfy("date","top-center","Appointment Booked!,"You have booked the following on 12/01/2020");</script>
```
![](https://i.ibb.co/Tv99Gb5/ntfypreview.png)

## NOTE
Have a look at /docs to read the docs/requirements.

## Contributing
Feel free to edit/add more features. Pull requests are really appreciated

## License
MIT License

```
Copyright (c) [2019] [Nithin/0x5a]

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
```
