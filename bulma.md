# Bulma online editor
Write, Run & Share Bulma css code online using OneCompiler's Bulma online editor for free. It's one of the robust, feature-rich online editor for Bulma css. Getting started with the OneCompiler's Bulma online editor is really simple and pretty fast. The editor shows sample boilerplate code when you choose language as 'Bulma' and start writing code to learn and test online instantly.

# About Bulma

Bulma is a free open-source CSS framework for front-end web development. It helps developers to develop websites faster and also easy to use. You can use built-in classes which are available hence you don't need to develop elements from scratch.

# Syntax help

## Modifiers

|Color classes| Size classes|State classes|
|----|----|----|
|.is-primary|.is-small|.is-outlined|
|.is-link|.is-medium|.is-loading|
|.is-info|.is-large|
|.is-success| | |
|.is-warning| | |
|.is-danger| | |

## Typography helpers

|Class|Size|
|----|----|
|.is-size-1|3rem|
|.is-size-2	|2.5rem|
|.is-size-3	|2rem|
|.is-size-4	|1.5rem|
|.is-size-5	|1.25rem|
|.is-size-6	|1rem|
|.is-size-7	|0.75rem|

|Class|Description|
|----|----|
|.has-text-centered|	Makes the text centered|
|.has-text-justified|	Makes the text justified|
|.has-text-left|	Makes the text align to the left|
|.has-text-right|	Makes the text align to the right|
|.is-capitalized|	Transforms the first character of each word to uppercase|
|.is-lowercase|	Transforms all characters to lowercase|
|.is-uppercase|	Transforms all characters to uppercase|

## Breadcrumbs

```html
<nav class="breadcrumb" aria-label="breadcrumbs">
  <ul>
    <li><a href="#">Bulma</a></li>
    <li class="is-active"><a href="#" aria-current="page">Breadcrumb</a></li>
  </ul>
</nav>
```

## Dropdown
```html
<div class="dropdown is-active">
  <div class="dropdown-trigger">
    <button class="button" aria-haspopup="true" aria-controls="dropdown-menu">
      <span>Dropdown button</span>
      <span class="icon is-small">
        <i class="fas fa-angle-down" aria-hidden="true"></i>
      </span>
    </button>
  </div>
  <div class="dropdown-menu" id="dropdown-menu" role="menu">
    <div class="dropdown-content">
      <a href="#" class="dropdown-item"> Dropdown item </a>
      <a class="dropdown-item"> Other dropdown item </a>
      <a href="#" class="dropdown-item is-active"> Active dropdown item </a>
      <a href="#" class="dropdown-item"> Other dropdown item </a>
      <hr class="dropdown-divider">
      <a href="#" class="dropdown-item"> With a divider </a>
    </div>
  </div>
</div>
```

## Menu
```html
<aside class="menu">
  <p class="menu-label">
    General
  </p>
  <ul class="menu-list">
    <li><a>Dashboard</a></li>
    <li><a>Customers</a></li>
  </ul>
</aside>
```
## Modal
```html
<div class="modal">
  <div class="modal-background"></div>
  <div class="modal-content">
    <!-- Any other Bulma elements you want -->
  </div>
  <button class="modal-close is-large" aria-label="close"></button>
</div>
```
## Tabs
```html
<div class="tabs">
  <ul>
    <li class="is-active"><a>Pictures</a></li>
    <li><a>Music</a></li>
    <li><a>Videos</a></li>
    <li><a>Documents</a></li>
  </ul>
</div>
```
## Form
```html
<div class="field">
  <label class="label">Name</label>
  <div class="control">
    <input class="input" type="text" placeholder="e.g Alex Smith">
  </div>
</div>

<div class="field">
  <label class="label">Email</label>
  <div class="control">
    <input class="input" type="email" placeholder="e.g. alexsmith@gmail.com">
  </div>
</div>
```


