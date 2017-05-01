[![Build Status](https://travis-ci.org/mpachnis/mp-slider.svg?branch=master)](https://travis-ci.org/mpachnis/mp-slider) [![Build Status](https://saucelabs.com/buildstatus/mpachnis)](https://saucelabs.com/beta/builds/bb74e5995c5b4accb63501628cd85dbf) [![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/mpachnis/mp-slider)


## &lt;mp-slider&gt;


## Demo

[mp-slider docs & demo](http://minas.pachnis.com/projects/mp-slider/bower_components/mp-slider/)


## Install the component using [Bower](http://bower.io/):

```bash
$ bower install --save mp-slider
```

## Usage

1. Import Web Components' polyfill:

```html
<script src="bower_components/webcomponentsjs/webcomponents-lite.js"></script>
```

2. Import Custom Element:

```html
<link rel="import" href="bower_components/mp-slider/mp-slider.html">
```

3. Start using it!

    Wrap the image in a div. To add caption to your image just include the 'mp-caption' element with slider-header, slide-content properties.

<!--
```
<custom-element-demo>
    <template>
        <script src="../webcomponentsjs/webcomponents-lite.js"></script>
        <link rel="import" href="mp-slider.html">
        <next-code-block></next-code-block>
    </template>
</custom-element-demo>
```
-->

```html
<mp-slider controls bullets show-thumbs>
    <div>
        <img src="demo/images/img1.jpg" />
        <mp-caption slider-header="Kung Fu Panda"
                    slider-content="Po and the legends of awesomeness">
        </mp-caption>
    </div>

    <div>
        <img src="demo/images/img2.jpg" />
        <mp-caption slider-header="Despicable Me"></mp-caption>
    </div>
</mp-slider>
```

## License

MIT License
