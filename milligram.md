# Milligram online editor
Write, Run & Share Milligram code online using OneCompiler's Milligram online editor for free. It's one of the robust, feature-rich online editor for Milligram. Getting started with the OneCompiler's Milligram online editor is really simple and pretty fast. The editor shows sample boilerplate code when you choose language as 'Milligram' and start writing code to learn and test online instantly.

# About Milligram

Milligram is a minimalist CSS framework. It's very useful for smaller projects which only need basic stuff.

# Syntax help

## Button

```html
<!-- Default Button -->
<a class="button" href="#">Default Button</a>

<!-- Outlined Button -->
<button class="button button-outline">Outlined Button</button>

<!-- Clear Button -->
<input class="button button-clear" type="submit" value="Clear Button">
```

## Lists
```html
<!-- Unordered list -->
<ul>
  <li>Unordered list item 1</li>
  <li>Unordered list item 2</li>
</ul>

<!-- Ordered list -->
<ol>
  <li>Ordered list item 1</li>
  <li>Ordered list item 2</li>
</ol>

<!-- Description list -->
<dl>
  <dt>Description list item 1</dt>
  <dd>Description list item 1.1</dd>
</dl>
```

## Forms
```html
<form>
  <fieldset>
    <label for="nameField">Name</label>
    <input type="text" placeholder="Provide Name" id="nameField">
    <label for="genderField">Gender</label>
    <select id="genderField">
      <option value="male">Male</option>
      <option value="female">Female</option>
    </select>
    <div class="float-right">
      <input type="checkbox" id="confirmField">
      <label class="label-inline" for="confirmField">Send a copy to yourself</label>
    </div>
    <input class="button-primary" type="submit" value="Send">
  </fieldset>
</form>
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
```
## Grid
```html
<div class="container">

  <div class="row">
    <div class="column">.column</div>
    <div class="column">.column</div>
    <div class="column">.column</div>
  </div>

  <div class="row">
    <div class="column">.column</div>
    <div class="column column-50 column-offset-25">.column column-50 column-offset-25</div>
  </div>

</div>
```