# COLORS

## 1. Use only one base color

## 2. Create your pallets of colors

Use tools to help you on that (eg. Palleton)

## 3. Psycologic effects

## Some references

- Cool Flat UI colors:  
  http://flatuicolors.com/

- Even more cool colors:  
  http://getuicolors.com/

- Find variations of colors (very good):  
  http://www.0to255.com/

- Adobe Color CC, play around with colors:  
  https://color.adobe.com/create/color-wheel/

- Palettoon, play around with colors:  
  http://paletton.com

- Beautiful gradients for webdesign:  
  http://uigradients.com/

- Learn about colors:  
  http://www.rocket-design.fr/color-template/

- Learn even more about colors:  
  http://webdesign.tutsplus.com/articles/an-introduction-to-color-theory-for-web-designers--webdesign-1437

## Use CSS To Work With Images

To achieve the text-on-image effects I showed you before, you can use CSS for your websites. Here is example CSS code for some of the effects. Please change it according to your needs.

### **Overlay the image**

```CSS
.darken {
  background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url(YOUR IMAGE HERE);
}
```

Example: http://jsfiddle.net/drpak8vy/1/

### **Put text in a box**

```CSS
.text-box {
  background-color: rgba(0, 0, 0, 0.5);
  color: #fff;
  display: inline;
  padding: 10px;
}
```

Example: http://jsfiddle.net/qg83m36p/

### **Floor fade**

```CSS
.floor-fade {
background: linear-gradient(to bottom, rgba(0, 0, 0, 0), rgba(0, 0, 0, 0.6) ), url(YOUR IMAGE HERE);
}
```

Example: http://jsfiddle.net/gRzPF/409/
