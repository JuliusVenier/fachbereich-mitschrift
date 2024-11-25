# CSS Snippets

## Bild Rechts

``` css
.bildrechts{
    float: right;
    margin-left: 1em;
    margin-top: 0;
}
```

## Bild Links

``` css
.bildlinks{
    float: left;
    margin-right: 1em;
    margin-top: 0;
}
```
## Bild Zentriert

``` css
.bildlinks, .bildrechts{
    float: none;
    text-align: center;
    margin: 0;
}
```

## Clearfix
> ❗ **Wichtig**
> Sollte sich auf der Seite irgendwas verschieben benutzt dieses Clearfix, sollte eigentlich überall funktionieren.
``` css
.clearfix::after {
    content: "";
    clear: both;
    display: table;
  }
```

## Variablen
``` css
* {
    --blau: #4658ff;
}

main {
    background-color: var(--blau);
}
```
