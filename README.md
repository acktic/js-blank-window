# js-blank-window
Open to new window to location

```
String.prototype.blank = function () {
  window.open(this, `_blank`, `noreferrer noopener`);
};
```

## example
this.blank()
