# dropdown

下拉菜单

# Example

```
<jie-dropdown>
  <jie-btn>Click Me!</jie-btn>
  <jie-menu>
    ...
  </jie-menu>
</jie-dropdown>

<script>
  var dropdown = document.querySelector('jie-dropdown');

  dropdown.addEventListener('select', function (e) {
    // e.detail.selected
  });

  dropdown.open();
  dropdown.close();
  dropdown.toggle();
</script>
```
