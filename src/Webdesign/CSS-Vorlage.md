# CSS Vorlage

``` css
* {
    box-sizing: border-box;
    --blau: #4658ff;
    --rot: #ff4545;
    --gelb: #ffee00;
    --gruen: #6b8b01
}

body {}

#container {
    background-color: var(--blau);
}

header {
    background-color: var(--rot);
}

main {
    background-color: var(--gelb);
    height: 800px;
}

nav {
    padding-top: 1em;
}

nav ul {
    list-style-type: none;
    padding: 0;
    margin: 0;
}

nav a {
    color: #000000;
    background-color: #ffffff;
    padding: 10px;
    margin-left: 2em;
    margin-bottom: 1em;
    text-align: right;
    display: block;
    text-decoration: none;
}

a {}

nav a:hover {}

nav #actual a {}

footer {
    background-color: var(--gruen);
}

.clearfix::after {
    content: "";
    clear: both;
    display: table;
  }

@media only screen and (min-width: 35em) and (max-width: 51em) {
    nav a {
        float: left;
        width: 15%;
        margin: 0;
        margin-right: 1em;
    }
}

@media only screen and (min-width: 51em) {

    #container {
        max-width: 51em;
        margin-left: auto;
        margin-right: auto;
        background-image: url();
        background-repeat: no-repeat;
        background-position: bottom left;
    }

    nav {
        width: 25%;
        float: left;
    }

    main {
        margin-left: 25%;
        /* clear: none; */
    }

}
```