Griddable
=========

Non-intrusive (but opinionated) responsive SASS grids.



Using the mixin
---------------

### 1 - Bootstrap-like

```sass
.g
  +griddable(12, 1rem, ( s: 576px, m: 768px, l: 992px, xl: 1200px ))
```

```html
  <div class="g">
    <div class="g-r">
      <!-- @TODO -->
    </div>
  </div>
```


### 2 - No gutters, 3 columns, collapsing below 400px

```sass
.g
  +griddable(3, 0, ( s: 500px, max: 100% ))
```

```html
  <div class="g">
    <div class="g-r">
      <div class="g-c _s1">First</div>
      <div class="g-c _s1">Second</div>
      <div class="g-c _s1">Third</div>
    </div>
  </div>
```

*To be continued…*
