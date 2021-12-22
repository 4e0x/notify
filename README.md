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
<script>ntfy.init(),ntfy.ntfy("date","top-left","Appointment Booked!,"You have booked the following on 12/01/2020");</script>
```
![](https://i.ibb.co/Tv99Gb5/ntfypreview.png)

## NOTE
Have a look at /docs to read the docs/requirements.

## Contributing
Feel free to edit/add more features. Pull requests are really appreciated

## License
MIT License
