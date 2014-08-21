## Sandy ##
=====

Lightweight responsive framework named after my Mini Pischer

### Docs ###
#### Components ####

* navbar - you can create a navigation bar like this:
  
  ```html
  <div class="navbar">
  ...
  </div>
  ```
  then add some contents to the navigation bar:
  
  ```html
  <div class="navbar">
    <div class="brand">Sandy</div>
    <div class="navbar-body">
      <ul class="nav">
        <li><a href="#">Home</a> </li>
        <li class="active"><a href="#">Project</a> </li>
        <li><a href="#">we are the world</a> </li>
        <li><a href="#">About</a> </li>
        <li class="divider"></li>
        <li><a href="#">Contact</a> </li>
      </ul>
    </div>
  </div>
  ```
  if you want the navigation bar stay fixed on the top/bottom of the page, you could add the `fixed-top` or `fixed-bottom`:
  
  ```html
  <div class="navbar fixed-top">
    ...
  </div>
  ```
  if you have used Bootstrap you must remember *inverse* which is used to inverse the color of the element, turns the color to its similarly inversed color:
  
  ```html
  <div class="navbar inverse">
    ...
  </div>
  ```
* button - like many frontend components, Sandy provides a few different kinds and states of buttons:
  
  ```html
  <button type="button" class="btn">Default</button> <!--default button-->
  <button type="button" class="btn btn-primary">Primary</button> <!--primary blue button-->
  <button type="button" class="btn btn-success">Success</button> <!--success green button-->
  <button type="button" class="btn btn-warning">Warning</button> <!--warning orange button-->
  <button type="button" class="btn btn-danger">Danger</button> <!--danger red button-->
  ```
  also, Sandy provides different sizes of buttons:
  
  ```html
  <button type="button" class="btn btn-large">Large</button>
  <button type="button" class="btn btn-xlarge">XLarge</button>
  <button type="button" class="btn btn-xxlarge">XXLarge</button>
  <button type="button" class="btn btn-small">Small</button>
  <button type="button" class="btn btn-xsmall">XSmall</button>
  <button type="button" class="btn btn-xxsmall">XXSmall</button>
  <button type="button" class="btn btn-xxsmall btn-danger">XXSmall</button>
  ```
  if you want to disable a button, just follow this, which will make the button unclickable(no visual effect after clicked), and the color is much gray:
  
  ```html
  <button type="button" class="btn disabled">Disabled</button>
  ```
* button group - button group contains a row or a column of buttons:
  
  ```html
  <div class="btn-group">
    <button type="button" class="btn">button</button>
    <button type="button" class="btn">button</button>
    <button type="button" class="btn">button</button>
    <button type="button" class="btn">button</button>
  </div>
  ```
* pager - jump between pages:
  
  ```html
  <div class="pager">
  <ul>
    <li><a href="#">&lt;</a></li>
    <li class="active"><a href="#">1</a></li>
    <li><a href="#">2</a></li>
    <li><a href="#">3</a></li>
    <li><a href="#">4</a></li>
    <li><a href="#">5</a></li>
    <li><a href="#">&gt;</a></li>
  </ul>
</div>
  ```
