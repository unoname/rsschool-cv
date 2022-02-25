# ALEXANDER PANOV

## Junior Frontend Developer

### Contact Me\

email: apanov08@gmail.com\
tel: 89372130416

### About Me

### Education

### Skills

- HTML
- CSS
- JavaScript
- React
- Git

### Code Example

RGB To Hex Conversion

The rgb function is incomplete. Complete it so that passing in RGB decimal values will result in a hexadecimal representation being returned. Valid decimal values for RGB are 0 - 255. Any values that fall out of that range must be rounded to the closest valid value.

Note: Your answer should always be 6 characters long, the shorthand with 3 will not work here.

```
function rgb(r, g, b){
  r = r>255 ? 255 : r < 0 ? 0 : r;
  g = g>255 ? 255 : g < 0 ? 0 : g;
  b = b>255 ? 255 : b < 0 ? 0 : b;
  let hex1 = (r < 16) ? `0${parseInt(r, 10).toString(16)}` : parseInt(r, 10).toString(16);
  let hex2 = (g < 16) ? `0${parseInt(g, 10).toString(16)}` : parseInt(g, 10).toString(16);
  let hex3 = (b < 16) ? `0${parseInt(b, 10).toString(16)}` : parseInt(b, 10).toString(16);
  return  (hex1 + hex2 + hex3).toUpperCase()
}
```

#### Reference
