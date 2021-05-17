# Paper CSS online editor
Write, Run & Share Paper CSS code online using OneCompiler's Paper CSS online editor for free. It's one of the robust, feature-rich online editor for Paper CSS. Getting started with the OneCompiler's Paper CSS online editor is really simple and pretty fast. The editor shows sample boilerplate code when you choose language as 'PaperCSS' and start writing code to learn and test online instantly.

# About Paper CSS

Paper CSS is a less formal CSS framework, with a quick and very easy integration

# Syntax help

## Alerts
```html
<div class="row flex-spaces">
  <div class="alert alert-primary">primary</div>
  <div class="alert alert-secondary">secondary</div>
  <div class="alert alert-success">success</div>
  <div class="alert alert-warning">warning</div>
  <div class="alert alert-danger">danger</div>
</div>
<!--Dismissable alert -->
<div class="row flex-spaces">
  <input class="alert-state" id="alert-1" type="checkbox">
  <div class="alert alert-primary dismissible">
    Primary alert
    <label class="btn-close" for="alert-1">X</label>
  </div>
</div>
```
## Button

```html
<button class="btn-large">Large</button>
<button>Default</button>
<button class="btn-small">Small</button>
<a href="#" class="paper-btn">Link</a>
<div class="row">
  <div class="col-6 col">
    <button class="btn-block">Block level</button>
  </div>
</div>
<button class="disabled">Disabled</button>
<button disabled>Disabled</button>
<!-- color buttons -->
<input type="button" class="paper-btn btn-primary" value="Primary"/>
<input type="button" class="btn-secondary" value="Secondary"/>
<button class="btn-success">Success</button>
<button class="btn-warning">Warning</button>
<button class="btn-danger">Danger</button>
<!-- Outline buttons -->
<input type="button" class="paper-btn btn-primary-outline" value="Primary"/>
<input type="button" class="btn-secondary-outline" value="Secondary"/>
<button class="btn-success-outline">Success</button>
<button class="btn-warning-outline">Warning</button>
<a href="#" class="paper-btn btn-danger-outline">Danger</a>
```

## Card
```html
<div class="card" style="width: 20rem;">
  <img src="sample.jpeg" alt="sample image">

  <div class="card-body">
    <h4 class="card-title">Card title</h4>
    <h5 class="card-subtitle">Cardsubtitle.</h5>
    <p class="card-text">Card content</p>
    <a class="card-link" href="#">link</a>
  </div>
</div>
```

## Breadcrumb
```html
<ul class="breadcrumb border">
  <li><a href="#">Documentation</a></li>
  <li><a href="#">Components</a></li>
  <li>Breadcrumb</li>
</ul>
```

## Tables

```html
<table>
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

<!-- Add table-hover or table-alternating to change the style of the table -->
<table class="table-hover">
<table class="table-alternating">
```
## Flexbox
```html
<div class="row">
  <div class="col-4 col">col-4 col</div>
  <div class="col-4 col">col-4 col</div>
  <div class="col-4 col">col-4 col</div>
</div>
<div class="row">
  <div class="col-3 col">col-3 col</div>
  <div class="col-9 col">col-9 col</div>
</div>
<div class="row">
  <div class="sm-6 md-8 lg-10 col">sm-6 md-8 lg-10 col</div>
  <div class="sm-6 md-4 lg-2 col">sm-6 md-4 lg-2 col</div>
</div>
<div class="row">
  <div class="sm-5 col">sm-5 col</div>
  <div class="col-fill col">col-fill col</div>
  <div class="col-fill col">col-fill col</div>
</div>
<!-- Use class="row" for left-aligned and class="row flex-right" for right aligned-->
<div class="row flex-center">
  <div class="sm-4 col">Aligned</div>
  <div class="sm-4 col">Center (flex-center)</div>
</div>
<!-- Use class="row flex-spaces" for evenly spaced alignment -->
<div class="row flex-edges">
  <div class="sm-4 col">Aligned</div>
  <div class="sm-4 col">to edges (flex-edges)</div>
</div>
<!-- Use class="row flex-bottom" for bottom alignment and class="row flex-middle" for middle alignment  -->
<div class="row flex-top">
  <div class="sm-6 col">Aligned top</div>
  <div class="sm-6 col">Content</div>
</div>
```