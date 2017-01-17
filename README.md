# slidesbg.js &mdash; [Homepage](http://www.nauvalazhar.net/projects/slidesbg.js/)
Free jquery plugin for background slideshow


##Penggunaan Slidesbg.js
Jadikan website anda menjadi lebih hidup
###1. Memulai
Gunakan jQuery 1.7+ dan panggil file slidesbg.js
```html
<script src="jquery-1.7.1.min.js"></script>
<script src="slidesbg.min.js"></script>
<link rel="stylesheet" src="slidesbg.css">
```

###2. HTML
Slidesbg.js tidak memerlukan pengaturan lebih pada html anda
cukup berikan id/class pada element yang akan dijadikan slider.
```html
<header id="myheader">
</header>
```

###3. Panggil Plugin
Letakan code berikut dan header anda sudah menjadi slider.
```javascript
var slides = [
  "image1.jpg",
  "image2.jpg "
];

$("#myheader").slidesbg({
  dataSlide: slides
});
```

##Demo
Anda bisa melihat contoh dari slidesbg.js.

Demo: [Click Me](http://www.nauvalazhar.net/projects/slidesbg.js/#/demo/)


##License
The MIT License (MIT)
