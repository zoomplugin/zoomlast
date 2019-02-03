# Easy Jquery Photo Gallery Plugin

Simple and Responsive Photo Gallery with jQuery

## Prerequisites

jQuery 1.3+
## Demo

[Demo Gallery](http://www.tiendasdigitales.net/github/easyjquerygallery/)

## Quick start

Include CSS And JS Files

1. Include Files:
```html
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
<link rel="stylesheet" href="css/easyjquerygallery.min.css">
<script src="js/easyjquerygallery.min.js"></script>
```

2. Scope

```js
$('.pluginSelector').easyGalleryJquery(
    {
      title:'My first gallery',
      preloader:'images/loader.gif', //optional
      percent: 80 //optional, default value: 80% of screen
    }
);
```
**HTML**

```html
<section class="pluginSelector">
 <a href="images/0.jpg">
  <img src="images/mini_0.jpg" alt="My Photo Caption at Window Bottom #1"/>
 </a>
 <a href="images/1.jpg">
  <img src="images/mini_1.jpg" alt="My Photo Caption at Window Bottom #2"/>
 </a>
</section>
```

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Authors

* **Lucas G. Martinez** - *Initial work* - [Lucasato](https://github.com/lucasato)

See also the list of [contributors](https://github.com/lucasato/easyjquerygallery/graphs/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
