# christmas-ribbon

Add the [iLee](http://ilee.co.uk) Christmas ribbon to your website!

### HTML

Place this directly after your opening `<body>` tag:

```html
<div class="christmas-ribbon-wrapper">
  <div class="christmas-ribbon">
    <a href="http://christmas.ilee.co.uk" target="_blank">Merry Christmas!</a>
  </div>
</div>
```

### CSS

```css
.christmas-ribbon-wrapper {
    width: 150px;
    height: 150px;
    position: absolute;
    position: fixed;
    overflow: hidden;
    top: 0;
    right: 0;
    z-index: 1040;
}

.christmas-ribbon-wrapper .christmas-ribbon {
    position: absolute;
    padding: 2px 0;
    background-color: #a00;
    -webkit-box-shadow: 0px 2px 3px 0px rgba(0, 0, 0, 0.5);
    box-shadow: 0px 2px 3px 0px rgba(0, 0, 0, 0.5);
    z-index: 1050;
    pointer-events: auto;
    top: 42px;
    right: -43px;
    -webkit-transform: rotate(45deg);
    -moz-transform: rotate(45deg);
    -o-transform: rotate(45deg);
    transform: rotate(45deg);
}

.christmas-ribbon-wrapper .christmas-ribbon a,
.christmas-ribbon-wrapper .christmas-ribbon a:hover {
    font-size: 13px;
    font-weight: 700;
    color: white;
    text-decoration: none;
    text-shadow: 0 -1px rgba(0,0,0,0.5);
    text-align: center;
    width: 200px;
    line-height: 20px;
    display: inline-block;
    padding: 2px 0;
    border-width: 1px 0;
    border-style: dashed;
    border-color: rgba(255,255,255,0.7);
}
```

## License

[MIT License](http://ilee.mit-license.org)
