# Materialize online editor
Write, Run & Share Materialize code online using OneCompiler's Materialize online editor for free. It's one of the robust, feature-rich online editor for Materialize. Getting started with the OneCompiler's Materialize online editor is really simple and pretty fast. The editor shows sample boilerplate code when you choose language as 'Materialize' and start writing code to learn and test online instantly.

# About Materialize

Materialize CSS is a UI component library which is created with CSS, JavaScript and HTML by Google. 

### Key principles:

* Material is the metaphor
* Bold, graphic, intentional
* Motion provides meaning

# Syntax help

## CSS

## Color

### Background color
```html
<div class="card-panel teal lighten-2">This is a card panel with a teal lighten-2 class</div>
```
### Sass
```css
.ilike-blue-container {
    @extend .blue, .lighten-4;
  }
```
### Text color
```html
<span class="blue-text text-darken-2">This is a card panel with dark blue text</span>
```
#### Sass
```css
 .ilike-blue-container {
    @extend .blue-text, .text-lighten-4;
  }
```
|Color Names| | | | |
|---|---|---|---|---|
|.red|.lighten-5|.pink|.lighten-4|.purple|
|.lighten-3|.deep-­purple|.lighten-2|.indigo|.lighten-1|
|.blue|.darken-1|.light­-blue|.darken-2|.cyan|
|.darken-3|.teal|.darken-4|.green|.accent-1|
|.light­-green|.accent-2|.lime|.accent-3|.yellow|
|.accent-4|.amber|.orange|.deep-­orange|.brown|
|.grey|.blue-grey|.black|.white|.trans­parent|

|classes to vary the color applied| | | |
|---|---|---|---|
|lighten-1| lighten-2| lighten-3| lighten-4| lighten-5|
| darken-1| darken-2| darken-3|| darken-4||
| accent-1| accent-2| accent-3| accent-4||

## Grid

* Row and column style classes

|Small Screen Devices|Description|
|---|---|
|s1|Defines 1 of 12 columns with width as 08.33%|
|s2|Defines 2 of 12 columns with width as 16.66%.|
|s3|Defines 3 of 12 columns with width as 25.00%.|
|s4|Defines 4 of 12 columns with width as 33.33%.|
|s5-s11|Defines 5-11 columns respectively|
|s12|Defines 12 of 12 columns with width as 100%. Default class for small screen phones|

|Medium Screen Devices||
|---|---|
|m1|Defines 1 of 12 columns with width as 08.33%|
|m2|Defines 2 of 12 columns with width as 16.66%.|
|m3|Defines 3 of 12 columns with width as 25.00%.|
|m4|Defines 4 of 12 columns with width as 33.33%.|
|m5-m11|Defines 5-11 columns respectively|
|m12|Defines 12 of 12 columns with width as 100%. Default class for medium screen phones|

|Large Screen Devices||
|---|---|
|l1|Defines 1 of 12 columns with width as 08.33%|
|l2|Defines 2 of 12 columns with width as 16.66%.|
|l3|Defines 3 of 12 columns with width as 25.00%.|
|l4|Defines 4 of 12 columns with width as 33.33%.|
|l5-l11|Defines 5-11 columns respectively|
|l12|Defines 12 of 12 columns with width as 100%. Default class for large screen devices like laptops|

### Usage
```html
<div class="col s2 m3 l4"></div>
```
The above specifies to use  2 columns on a small screen, 3 on a medium screen, and 4 on a large screen

```html
 <div class="row">
      <div class="col s12">This div is 12-columns wide on all screen sizes</div>
      <div class="col s6">6-columns (one-half)</div>
      <div class="col s6">6-columns (one-half)</div>
      
      <div class="col s6 offset-s6"><span class="flow-text">6-columns (offset-by-6)</span></div>

      <div class="col s7 push-s5"><span class="flow-text">This div is 7-columns wide on pushed to the right by 5-columns.</span></div>
      <div class="col s5 pull-s7"><span class="flow-text">5-columns wide pulled to the left by 7-columns.</span><div>
</div>
```

# Components

## Buttons
### Raised
```html
<a class="waves-effect waves-light btn"><i class="material-icons left">cloud</i>button</a>
```
### Floating
```html
<a class="btn-floating btn-large waves-effect waves-light red"><i class="material-icons">add</i></a>
```
### Submit
```html
<button class="btn waves-effect waves-light" type="submit" name="action">Submit
    <i class="material-icons right">send</i>
</button>
```
### Small and large Buttons
```html
<a class="waves-effect waves-light btn-small">Button</a>
<a class="waves-effect waves-light btn-large">Button</a>
```
### Disabled
```html
<a class="btn disabled">Button</a>
```

## Breadcrumbs

```html

  <nav>
    <div class="nav-wrapper">
      <div class="col s12">
        <a href="#!" class="breadcrumb">First</a>
        <a href="#!" class="breadcrumb">Second</a>
        <a href="#!" class="breadcrumb">Third</a>
      </div>
    </div>
  </nav>
```

## Cards

```html
  <div class="row">
    <div class="col s12 m6">
      <div class="card blue-grey darken-1">
        <div class="card-content white-text">
          <span class="card-title">Card Title</span>
          <p>I am a very simple card. I am good at containing small bits of information.
          I am convenient because I require little markup to use effectively.</p>
        </div>
        <div class="card-action">
          <a href="#">This is a link</a>
        </div>
      </div>
    </div>
  </div>
```
## Icons

```html
 <!--
  Sizes:
  tiny: 1rem
  small: 2rem
  medium: 4rem
  large: 6rem
  -->
  <i class="large material-icons">insert_chart</i>
```

## Navbar

```html
 <nav>
    <div class="nav-wrapper">
      <a href="#" class="brand-logo">Logo</a>
      <ul id="nav-mobile" class="right hide-on-med-and-down">
        <li><a href="sass.html">Sass</a></li>
        <li><a href="badges.html">Components</a></li>
        <li><a href="collapsible.html">JavaScript</a></li>
      </ul>
    </div>
  </nav>
```

## Pagination
```html
  <ul class="pagination">
    <li class="disabled"><a href="#!"><i class="material-icons">chevron_left</i></a></li>
    <li class="active"><a href="#!">1</a></li>
    <li class="waves-effect"><a href="#!">2</a></li>
    <li class="waves-effect"><a href="#!">3</a></li>
    <li class="waves-effect"><a href="#!">4</a></li>
    <li class="waves-effect"><a href="#!">5</a></li>
    <li class="waves-effect"><a href="#!"><i class="material-icons">chevron_right</i></a></li>
  </ul>
```
## Pre-loader
```html
  <div class="progress">
      <div class="determinate" style="width: 70%"></div>
  </div>
   <div class="progress">
      <div class="indeterminate"></div>
  </div>
```
