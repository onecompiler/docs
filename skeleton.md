# Skeleton online editor
Write, Run & Share Skeleton code online using OneCompiler's Skeleton online editor for free. It's one of the robust, feature-rich online editor for Skeleton. Getting started with the OneCompiler's Skeleton online editor is really simple and pretty fast. The editor shows sample boilerplate code when you choose language as 'Skeleton' and start writing code to learn and test online instantly.

# About Skeleton

Skeleton is a lightweight CSS framework created by Dave Gamache. It is a very simple and responsive boilerplate. It's very useful for smaller projects if you feel larger frameworks is not your choice.

# Syntax help

## Grid

```html
<!-- .container is main centered wrapper -->
<div class="container">

  <!-- columns should be the immediate child of a .row -->
  <div class="row">
    <div class="one column">One</div>
    <div class="eleven columns">Eleven</div>
  </div>

  <!-- just use a number and class 'column' or 'columns' -->
  <div class="row">
    <div class="two columns">Two</div>
    <div class="ten columns">Ten</div>
  </div>

  <!-- there are a few shorthand columns widths as well -->
  <div class="row">
    <div class="one-third column">1/3</div>
    <div class="two-thirds column">2/3</div>
  </div>
  <div class="row">
    <div class="one-half column">1/2</div>
    <div class="one-half column">1/2</div>
  </div>

</div>
```

## Button
```html
<a class="button" href="#">Anchor button</a>
<input type="submit" value="submit input">
<button class="button-primary">Primary Button</button>
```
## Forms
```html
<form>
  <div class="row">
    <div class="six columns">
      <label for="email">email</label>
      <input class="u-full-width" type="email" placeholder="test@mailbox.com" id="email">
    </div>
  </div>
  <label for="exampleMessage">Message</label>
  <textarea class="u-full-width" placeholder="Hello.." id="exampleMessage"></textarea>
  <input class="button-primary" type="submit" value="Submit">
</form>
```

## Lists
```html
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ul>
```

## Tables

```html
<table class="u-full-width">
  <thead>
    <tr>
      <th>Name</th>
      <th>Gender</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Dave</td>
      <td>Male</td>
    </tr>
    <tr>
      <td>Ava</td>
      <td>Female</td>
    </tr>
  </tbody>
</table>
```
## Media queries
```c
/* Mobile first queries */

/* Larger than mobile */
@media (min-width: 400px) {}

/* Larger than phablet */
@media (min-width: 550px) {}

/* Larger than tablet */
@media (min-width: 750px) {}

/* Larger than desktop */
@media (min-width: 1000px) {}

/* Larger than Desktop HD */
@media (min-width: 1200px) {}
```