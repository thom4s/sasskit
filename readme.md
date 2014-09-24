# sasskit


### Structure

Sasskit is a simple reusable (and modest...) kit of sass files for web projects. It is inspired by many systems and thoughts already in use. Nothing's lost, nothing's created, everything's transformed...

### Grid

Simple grid works like that : 

    <div class="row">
        <div class="bd col-s-4 col-m-6">col-s-4 / col-m-6</div>
        <div class="bd col-s-6 ">col6</div>
        <div class="bd col-s-2 hide-m">col-s-2</div>
    </div>

Nested grid works like that : 

    <div class="row">
        <div class="bd col-s-12 col-m-6 col-l-11 col-l-center">col-s-12 / col-m-6</div>
        <div class="row">
            <div class="bd col-s-3">col-s-3</div>
            <div class="bd col-s-3">col-s-3</div>
            <div class="bd col-s-3">col-s-3</div>
            <div class="bd col-s-3">col-s-3</div>
        </div>
    </div>


### code style

#### variables name

$first_color:       #23f;  
$seconde_color:     #f22;    

#### classes name

Keep it simple (see Trello link): 

    <ul class="global-header-nav">
        <li class="global-header-nav-item"></li>
    </ul>

For javascript hooks, use js- prefix : 

    .js-open-content-menu


### Inspired by

- [Css structure at Trello](http://blog.trello.com/refining-the-way-we-structure-our-css-at-trello/)
- [Sass Style Guide - css tricks](http://css-tricks.com/sass-style-guide/)
- [CodePen's CSS](http://codepen.io/chriscoyier/blog/codepens-css)
- [DoCSSa](http://docssa.info/)

### todos

- change folder names (atoms, molecules, etc.)
- clean up da mixins mess 
