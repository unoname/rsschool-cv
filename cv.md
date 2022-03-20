rsschool-cv

# ALEXANDER PANOV

## Junior Frontend Developer

### Contact Me

E-mail: apanov08@gmail.com\
Tel: 89372130416\
Discord: unoname

### About Me

I am a lawyer by training. I have experience in this field. I also worked as a household appliance repairman. In 2020, I took web development courses from the employment center. Since the course program was weak, I left programming for about a year. In 2021, I completed programming courses at Innopolis University. There I learned about RSShool. I really like programming and I think that RSSchool can help me master this profession. That's why I'm here (RSShool).

### Education

2021 - Сourses professional retraining "Innopolis University" (qualification Junior Frontend Developer)

### Skills

Basic

- HTML
- CSS
- JavaScript
- React
- Git
- English (A1)

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

[![Image](./icons/free-icon-github-logo-25231.png)GitHub](https://github.com/unoname)

[![Image](./icons/codewars_button_icon_151901.png)](https://www.codewars.com/users/Alexandr%20Panov)
