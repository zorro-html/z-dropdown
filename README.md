# `<z-dropdown>`

Dropdown element with a button and a menu

## Import

```
<link rel="import" href="z-dropdown/z-dropdown.html">
```

## Methods

- `toggle()`
- `open()`
- `close()`

## Examples

```
<z-dropdown id="z-dropdown-test">
  <z-btn>Click Me!</z-btn>
  <z-menu>
    <li>ITEM 1</li>
    <li>ITEM 2</li>
    <li disabled>ITEM 3</li>
    <hr>
    <li>ITEM 4</li>
  </z-menu>
</z-dropdown>

<script>
  var dropdown = document.querySelector('html /deep/ #z-dropdown-test');

  dropdown.addEventListener('select', function (e) {
    // e.detail.selected
  });
</script>
```
