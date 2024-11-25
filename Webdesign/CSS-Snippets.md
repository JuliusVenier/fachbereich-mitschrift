# CSS Snippets

## Bildrechts

``` css
.bildrechts{
    float: right;
    margin-left: 1em;
    margin-top: 0;
}
```

## Bildlinks

``` css
.bildlinks{
    float: left;
    margin-right: 1em;
    margin-top: 0;
}
```

## Clearfix
> ❗ **Wichtig**
> Sollte sich auf der Seite irgendwas verschieben benutzt dieses Clearfix, sollte eigentlich überall funktionieren
``` css
.clearfix::after {
    content: "";
    clear: both;
    display: table;
  }
```
