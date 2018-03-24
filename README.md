# designkit-labels
1.0.0

A Sass module for labels used in RightScale apps.

## Install
```
npm i --save designkit-labels
```

## CSS

```css
.label {
  display: inline-block;
  padding: 4px 8px;
  font-weight: 600;
  line-height: 20px;
  color: #fff;
  text-align: center;
  background-color: #5e6f7f;
  border-radius: 3px;
}

.label:hover {
  text-decoration: none;
}

.label.label--small {
  padding: 2px 6px;
  font-size: 12px;
}

.label.label--sith {
  background-color: #353B41;
  color: #fff;
}

.label.label--blue {
  background-color: #007bdd;
  color: #fff;
}

.label.label--purple {
  background-color: #6854c0;
  color: #fff;
}

.label.label--green {
  background-color: #2cbe4e;
  color: #fff;
}

.label.label--yellow {
  background-color: #fbca04;
  color: rgba(0, 0, 0, 0.8);
}

.label.label--orange {
  background-color: #fc620f;
  color: #fff;
}

.label.label--red {
  background-color: #cb2431;
  color: #fff;
}

.label.label--outline {
  background: transparent;
  color: #5e6f7f;
  box-shadow: inset 0 0 0 1px currentColor;
}

.label.label--outline-sith {
  color: #353B41;
}

.label.label--outline-blue {
  color: #007bdd;
}

.label.label--outline-purple {
  color: #6854c0;
}

.label.label--outline-green {
  color: #2cbe4e;
}

.label.label--outline-orange {
  color: #fc620f;
}

.label.label--outline-red {
  color: #cb2431;
}

```

## Author

Jason Melgoza

## License

MIT
