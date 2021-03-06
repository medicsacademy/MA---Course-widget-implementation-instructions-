<hr>
<div align="center">
   <h3>Medics Academy</h3>
   <h1>Sales widget instructions</h1>
   <img src="http://i63.tinypic.com/esjh4m.png" alt="Medics Academy">
</div>

<hr>

<div align="center">
   <a href="https://www.medics.academy/pages/opportunities">Jobs</a>
   ·
   <a href="https://www.medics.academy/">Medics Academy</a>
</div>

## Table of contents

1. [Quick Start](#quick-start)
1. [Courses](#courses)
2. [Bundles](#bundles)
3. [Style your card](#style-your-card)


### Purpose

This document will give you a step-by-step guide on how to insert a course card widget on your website.
This allows you to place Medics.Academy content easily into your web presence so that you can embed our content in a variety of scenarios, such as:
1. Reference your cards in a Blog and or page article
2. On the front page of your site, to help you maximise sales or sign ups
   
### Quick Start

1) Place the following `<script>` near the end of your page you want to display those cards, right before the closing `</body>` tag:

```javascript
    <script>
        (function (w, d, s, o, f, js, fjs) {
            console.log(w);
            w['MedicsAcademySalesWidget'] = o;
            w[o] = w[o] || function () {
                (w[o].q = w[o].q || []).push(arguments)
            };
            js = d.createElement(s);
            fjs = d.getElementsByTagName(s)[0];
            js.id = o;
            js.src = f;
            js.async = true;
            fjs.parentNode.insertBefore(js, fjs);
        }(window, document, 'script', 'ma', 'https://cdn.medics.academy/js/widgets/ma_widget.js'));
        ma('init');
    </script>
```


#### Bundles
If a bundle is what you want to put in place:

| Tables           | Type              | Description                                                                 |
| ---------------- |:-----------------:| ---------------------------------------------------------------------------:|
| data-productId   | String / Number   | Define the product ID of the course                                         |
| data-slug        | String            | Define the slug of the course, help us to redirect you at the specific page |
| data-duration    | Number            | Define the period between the payments                                      |

2) Copy and paste the following code where you want the cards to be displayed:

```
<div class="medicsacademy-card medicsacademy-card_sm"
     data-productId=14910
     data-slug="pre-hospital-trauma"
     data-duration="3">
</div>
```
3) Update the current code with the _data-productId_, _data-slug_ and *_data-duration_ we sent you via email, if you don't have it please <a href="mailto:hello@medics.academy?Subject=Sales%20widget%20-%20Needed%20products%20id" target="_top">contact us</a> and we will be happy to provide it to you!


**IMPORTANT:**
> For a free bundle the *data-duration* has not to be specified, as the following example:

```
<div class="medicsacademy-card medicsacademy-card_sm"
     data-productId=16109
     data-slug="the-medics-academy-global-health-bundle">
</div>
```

#### Courses
If a Course is what you want to put in place:

| Tables           | Type              | Description                                                                 |
| ---------------- |:-----------------:| ---------------------------------------------------------------------------:|
| data-productId   | String / Number   | Define the product ID of the course                                         |

2) Copy and paste the following code where you want the cards to be displayed:

```
<!--Course: -->
<div class="medicsacademy-card medicsacademy-card_sm"
     data-productId="229658"></div>
```
3) Update the current code with the _data-productId_ we sent you via email, if you don't have it please <a href="mailto:hello@medics.academy?Subject=Sales%20widget%20-%20Needed%20products%20id" target="_top">contact us</a> and we will be happy to provide it to you!

#### Style your card

Always keep the *.medicsacademy-card* class, it is a global-class used by us to init the styles of yours card.

`class="medicsacademy-card"`

 The card can come in two different sizes, choose the one that suits you best.
 To choose the size of your card add just _ONE_ of the following class:

| Size          | Class                 |
| ------------- | ---------------------:|
| 240px * 320px | medicsacademy-card_sm |
| 320px * 400px | medicsacademy-card_md |

     
4) Now, you should be all set and see the course card widget implemented on your website. Enjoy it!


## Features
Next features will arrive soon!
   - [ ] _UTM tracking_
   - [ ] _Include a discount code_
   
   
   
# Credits:
@Medics Academy: [Medics Academy](https://www.medics.academy/)
