---
layout: default
title: dev Resources
published: false
display: false
---
### AMP

#### Analytics
- [Analytics](https://ampbyexample.com/components/amp-analytics/)
`<script async custom-element="amp-analytics" src="https://cdn.ampproject.org/v0/amp-analytics-0.1.js"></script>`
```html
<amp-iframe class="fixed card"
      width="180"
      height="180"
      layout="fixed"
      sandbox="allow-scripts allow-same-origin"
      frameborder="0"
      src="https://amp-publisher-samples-staging.herokuapp.com/amp-analytics/embed?user=amp-YtkYB-b0WgA-9V3S-fFD41XCuO6gkImgKLvToaxfTQxWZPTorri6SXapseruqX4E&account=ampbyexample">
    <amp-img src="/img/pixel-white.png"
        layout="fixed-height"
        height="350"
        width="auto"
        placeholder>
  </amp-iframe>
  ```

- ANCHOR LINKS
```html
<amp-analytics>
    <script type="application/json">
      {
        "requests": {
          "event": "https://amp-publisher-samples-staging.herokuapp.com/amp-analytics/ping?user=amp-YtkYB-b0WgA-9V3S-fFD41XCuO6gkImgKLvToaxfTQxWZPTorri6SXapseruqX4E&account=ampbyexample&event=${eventId}"
        },
        "triggers": {
          "trackAnchorClicks": {
            "on": "click",
            "selector": "a",
            "request": "event",
            "vars": {
              "eventId": "clickOnAnyAnchor"
            }
          }
        }
      }
    </script>
  </amp-analytics>
```

- specific ANCHOR LINKS
```<amp-analytics>
    <script type="application/json">
      {
        "requests": {
          "event": "https://amp-publisher-samples-staging.herokuapp.com/amp-analytics/ping?user=amp-YtkYB-b0WgA-9V3S-fFD41XCuO6gkImgKLvToaxfTQxWZPTorri6SXapseruqX4E&account=ampbyexample&event=${eventId}"
        },
        "triggers": {
          "trackAnchorClicks": {
            "on": "click",
            "selector": "#anchor-id",
            "request": "event",
            "vars": {
              "eventId": "clickOnSpecialAnchor"
            }
          }
        }
      }
    </script>
  </amp-analytics>```

- CAROUSEL
```<amp-carousel width="400"
      height="300"
      layout="responsive"
      type="slides">
    <div class="slide"
        data-slide-id="slide1">Slide 1</div>
    <div class="slide"
        data-slide-id="slide2">Slide 2</div>
    <div class="slide">Slide 3</div>
  </amp-carousel>```

- [Animation - GIF, WEBP](https://ampbyexample.com/components/amp-anim/)
  - Embed animations (gif, webp) into your AMP HTML files. Animation files should be loaded via HTTPS.
`<script async custom-element="amp-anim" src="https://cdn.ampproject.org/v0/amp-anim-0.1.js"></script>`
```<amp-anim width=245
      height=300
      src="/img/gopher.gif"
      alt="an animation"
      attribution="The Go gopher was designed by Reneee French and is licensed under CC 3.0 attributions.">
  </amp-anim>
<amp-anim width=245
      height=300
      src="/img/gopher.gif"
      alt="an animation"
      attribution="The Go gopher was designed by Reneee French and is licensed under CC 3.0 attributions.">
    <amp-img placeholder
        width=245
        height=300
        src="/img/gopher.png">
    </amp-img>
  </amp-anim>```

#### [Carousel](https://ampbyexample.com/components/amp-carousel/)

#### [Lightbox](https://ampbyexample.com/components/amp-image-lightbox/)

#### [Ad](https://ampbyexample.com/components/amp-ad/)

#### [Product](https://ampbyexample.com/samples_templates/product/)

#### Notifications, Alerts, Modals [DT Codepen](https://codepen.io/devtips/pen/mEjOLg)

### Material Design Icons
- [Icon Library](https://material.io/icons/)
- [Create Sprite SVG sheet](https://github.com/google/material-design-icons/tree/master/sprites)


## Jekyll Docs

### Formatting Dates
- [Jekyll Cast](http://jekyll.tips/jekyll-casts/date-formatting/)


## Social

### Facebook


### Soundcloud


### Linked In


### Twitter


### Pinterest
