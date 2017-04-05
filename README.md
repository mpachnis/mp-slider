[![Build Status](https://travis-ci.org/mpachnis/mp-slider.svg?branch=master)](https://travis-ci.org/mpachnis/mp-slider) [![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/mpachnis/mp-slider)


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
<mp-slider controls caption bullets show-thumbs>
    <div>
        <img src="demo/images/img1.jpg" />
        <span class="caption">
            <h3>Kung Fu Panda</h3>
            <p>Po and the legends of awesomeness</p>
        </span>
    </div>

    <div>
        <img src="demo/images/img2.jpg" />
        <span class="caption">
            <h3>Despicable Me</h3>
            <p>Gru, the trio of orphan girls and the minions</p>
        </span>
    </div>
</mp-slider>
```

## License

MIT License
