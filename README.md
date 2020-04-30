# How to create a sticky footer?
![Sticky flex footer](https://raw.githubusercontent.com/droganaida/footer-down/master/footer-d.png)
## HTML

```
<body>
<main></main>
<footer></footer>
</body>
```

## CSS

```
html, body {
    min-height: 100vh;
}
body {
    display: flex;
    flex-direction: column;
}
main {
    flex-grow: 1;
}
footer {
    flex-grow: 0;
}
```
