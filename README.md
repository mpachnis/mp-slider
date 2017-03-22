[![Build Status](https://travis-ci.org/mpachnis/mp-slider.svg?branch=master)](https://travis-ci.org/mpachnis/mp-slider) [![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/mpachnis/mp-slider)


### &lt;mp-slider&gt;


### Demo

[mp-slider docs & demo](http://minas.pachnis.com/projects/mp-slider/bower_components/mp-slider/)


### Install

```bash
# via bower
$ bower install mp-slider
```

### Usage

Load the slider

```html
<link rel="import" href="path_to_bower_components/mp-slider/mp-slider.html" />
```
<!--
```
<custom-element-demo>
    <template>
        <link rel="import" href="mp-slider.html">
        <next-code-block></next-code-block>
    </template>
</custom-element-demo>
```
-->

add the slider element

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

### License

MIT License
