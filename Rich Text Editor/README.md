# Project2: Rich Text Editor

## 複習
* Box-sizing的值有兩個： content-box(預設值) 以及 border-box，簡單來說就是border-box包含了content、padding、border的所有值，而content-box只有content的width跟height。
* transform有以下常用的屬性： translate(x, y)、rotate(angle)、scale(x, y)，分別是用於平移、選轉、縮放

## 新東西
* vmin/vmax (viewport minimum/maximum):min 指的是 vw 和 vh 中較小的一邊；max 則是 vm 和 vh 中較大的一邊。舉例來說，1280px * 1600px 的長寬視窗比，vmin 指的就是 1280px；vmax 則是 1600px。
* place-items: center，指的是CSS Grid 布局中 align-items 和 justify-items屬性的簡寫。