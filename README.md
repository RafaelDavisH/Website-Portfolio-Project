# Personal Portfolio

This project is a layout replica of a mockup provided by Udacity. Its a responsive website using **FLEXBOX**. It was designed mobile first and working up to a desktop screen resolution.  It's a simple website with my name, title, personal quote, and links to some of the projects I have completed throughout a couple of courses I have taken at Udacity.

## Project Specification

The following criterias were required for this project:

* Design
* Responsiveness
* Seoaration of Concerns
* Code Quality

  ***A more detail breakdowm for each criteria with its specifications can be found [here](https://review.udacity.com/#!/rubrics/45/view).***

## Media Queries

This website has three **breakpoints**; `400px, 600px,` and `800px.`. They can be found in `css/media_queries.css`.


## Google Fonts

Two google fonts are used for the website. [`Catarell`](https://fonts.google.com/specimen/Cantarell) and [`Fjalla One`](https://fonts.google.com/specimen/Fjalla+One). They were not @IMPORT but linked by placing link provided by [google fonts](https://fonts.google.com/) between `<head>...</head>` like so:

```html
<head>
   <link href="https://fonts.googleapis.com/css?family=Cantarell:400,700|Fjalla+One" rel="stylesheet">
</head>
```
## BEM - **Block, Element, Modifier**

I used the **BEM** methodology for a more organized code and easier to follow. **BEM** its a popular naming convention for classes in HTML and CSS. Developed by the team at Yandex. for to learn more about **BEM** [click here](https://en.bem.info/).
