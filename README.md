## Sandy ##
=====

Lightweight responsive framework named after my Mini Pischer

### Docs ###
====

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
