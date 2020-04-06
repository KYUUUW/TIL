# Double tap zoom disable
* hybrid app 제작 시 double tap zoom 이 UX 에 방해 되는 경우 많음.
```html
<!--add meta tag-->
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1,user-scalable=0"/>
```
```css
body{
    touch-action: manipulation;
}
```
[stack overflow link](https://stackoverflow.com/questions/59732074/disable-double-tap-zoom-on-safari-ios-13)