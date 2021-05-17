# UIkit online editor
Write, Run & Share UIkit code online using OneCompiler's UIkit online editor for free. It's one of the robust, feature-rich online editor for Uikit. Getting started with the OneCompiler's Uikit online editor is really simple and pretty fast. The editor shows sample boilerplate code when you choose language as 'Uikit' and start writing code to learn and test online instantly.

# About UIkit

UIkit is a lightweight and modular framework for front-end web development. It helps developers to develop websites faster and also easy to use. You can use built-in classes which are available hence you don't need to develop elements from scratch.

# Syntax help

## Button
```html
<a class="uk-button" href="">...</a>
<button class="uk-button" type="button">...</button>
<button class="uk-button" type="button" disabled>...</button>
```
## Icon
```html
<!-- This is an icon -->
<i class="uk-icon-cog"></i>

<!-- This is an icon in a link -->
<a href=""><i class="uk-icon-cog"></i> ...</a>
```
## Grid

```html
<!-- This is a grid using uk-width-* on each item -->
<div data-uk-grid>
    <div class="uk-width-small-1-2 uk-width-medium-1-4">...</div>
    <div class="uk-width-small-1-2 uk-width-medium-1-4">...</div>
</div>

<!-- This is a grid using uk-grid-width-* on the grid itself -->
<div class="uk-grid-width-small-1-2 uk-grid-width-medium-1-4" data-uk-grid>
    <div>...</div>
    <div>...</div>
</div>
```
### Gutter Grid

```html
<div data-uk-grid="{gutter: 20}">...</div>
```

## Thumbnail

```html
<!-- This is an image as a thumbnail -->
<img class="uk-thumbnail" src="" alt="">
```
## Navbar
```html
<nav class="uk-navbar">
    <ul class="uk-navbar-nav">
        <li class="uk-active"><a href="">...</a></li>
        <li><a href="">...</a></li>
        <li class="uk-parent"><a href="">...</a></li>
    </ul>
</nav>
```
## Breadcrumb
```html
<ul class="uk-breadcrumb">
    <li><a href="">...</a></li>
    <li><a href="">...</a></li>
    <li><span>...</span></li>
    <li class="uk-active"><span>...</span></li>
</ul>
```
## Form

```html
<form class="uk-form">
    <fieldset data-uk-margin>
        <legend>...</legend>
        <input type="text" placeholder="">
        <input type="password" placeholder="">
        <select>
            <option>...</option>
            <option>...</option>
        </select>
        <button class="uk-button">...</button>
        <label><input type="checkbox"> ...</label>
    </fieldset>
</form>
```

## Dropdown

```html
<!-- This is the container enabling the JavaScript in click mode -->
<div data-uk-dropdown="{mode:'click'}">

    <!-- This is the element toggling the dropdown -->
    <div>...</div>

    <!-- This is the dropdown -->
    <div class="uk-dropdown">...</div>

</div>
 <!-- Delayed dropdown in hover mode -->
<div class="uk-dropdown" data-uk-dropdown="{delay: 1000}">
    ...
</div>
```

## Table

```html
<table class="uk-table">
    <caption>...</caption>
    <thead>
        <tr>
            <th>...</th>
        </tr>
    </thead>
    <tfoot>
        <tr>
            <td>...</td>
        </tr>
    </tfoot>
    <tbody>
        <tr>
            <td>...</td>
        </tr>
    </tbody>
</table>
```