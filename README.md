# Flexbox and Grid
 
![](https://user-images.githubusercontent.com/57969961/80440247-bc361680-88de-11ea-9a9e-ba91d46e9fec.png) 
 
## To do this section I used flexbox in HTML, CSS, like this:


***html***
```HTML
 <section class="flex">
    <div>
      <img src="img/lobo1.jpg" alt="Wolf">
      <p>Legenda</p>
    </div>
    <div>
      <img src="img/lobo2.jpg" alt="Wolf">
      <p>Legenda</p>
    </div>
    <div>
      <img src="img/lobo3.jpg" alt="Wolf">
      <p>Legenda</p>
    </div>
    <div>
      <img src="img/lobo2.jpg" alt="Wolf">
      <p>Legenda</p>
    </div>
    <div>
      <img src="img/lobo1.jpg" alt="Wolf">
      <p>Legenda</p>
    </div>
    <div>
      <img src="img/lobo3.jpg" alt="Wolf">
      <p>Legenda</p>
    </div>
  </section>
```
#
***css***
```CSS
.flex {
    display: flex;
    flex-wrap: wrap;
    max-width: 800px;
    margin: 0 auto;
}

.flex > div {
    flex: 1 1 200px;
    margin: 0 10px;
}
```
# 
![](https://user-images.githubusercontent.com/57969961/80441129-a295ce80-88e0-11ea-8768-61fb36d6ef1b.png)

## To do this section I used flexbox in HTML, CSS, like this:


***html***
```html
<section class="grid1">
  <div>
      <img src="img/lobo1.jpg" alt="Lobo">
      <p>Legenda</p>
  </div>
  <div>
      <img src="img/lobo2.jpg" alt="Lobo">
      <p>Legenda</p>
  </div>
  <div>
      <img src="img/lobo3.jpg" alt="Lobo">
      <p>Legenda</p>
  </div>
  <div>
      <img src="img/lobo2.jpg" alt="Lobo">
      <p>Legenda</p>
  </div>
  <div>
      <img src="img/lobo1.jpg" alt="Lobo">
      <p>Legenda</p>
  </div>
  <div>
      <img src="img/lobo3.jpg" alt="Lobo">
      <p>Legenda</p>
  </div>
  <div>
      <img src="img/lobo2.jpg" alt="Lobo">
      <p>Legenda</p>
  </div>
  <div>
      <img src="img/lobo1.jpg" alt="Lobo">
      <p>Legenda</p>
  </div>
  <div>
      <img src="img/lobo3.jpg" alt="Lobo">
      <p>Legenda</p>
  </div>
  <div class="anuncio">
      <img src="img/lobo1.jpg">
      <p>Anúncio</p>
  </div>
</section>
```
#
***css***
```css
.grid1 {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    max-width: 800px;
    padding: 10px;
    margin: 0 auto;
    grid-gap: 20px;
}

.grid1 > div:nth-child(n + 4) {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    grid-gap: 10px;
    align-items: center;
}

.grid > div.anuncio {
    grid-column: 1;
    grid-row: 2 / 5;
}

```
# 
![](https://user-images.githubusercontent.com/57969961/80441790-02d94000-88e2-11ea-99ba-d00da24f8ccb.png)

## To do this section I used flexbox in HTML, CSS, like this:


***html***
```html
<section class="grid2">
  <div class="video">
      <img src="img/lobo1.jpg">
      <h2>Como criar sites.</h2>
  </div>
  <div class="sidebar">
      <div>
          <img src="img/lobo2.jpg">
          <p>Legenda</p>
      </div>
      <div>
          <img src="img/lobo3.jpg">
          <p>Legenda</p>
      </div>
      <div>
          <img src="img/lobo1.jpg">
          <p>Legenda</p>
      </div>
      <div>
          <img src="img/lobo3.jpg">
          <p>Legenda</p>
      </div>
  </div>
</section>
```
#

***css***
```css
.grid2 {
    display: grid;
    grid-template-columns: 1fr 200px;
    grid-gap: 20px;
    max-width: 800px;
    padding: 10px;
    margin: 0 auto;
}

.sidebar > div {
    margin-bottom: 10px;
}
```
#
![](https://user-images.githubusercontent.com/57969961/80442198-d245d600-88e2-11ea-91d5-d12858b2fc49.png)

## To do this section I used flexbox in HTML, CSS, like this:

***html***
```html
<section class="grid3"> 
    <div class="grid3item">
        <img src="img/lobo4.jpg">
        <p>Legenda</p>
    </div>
    <div class="grid3item">
        <img src="img/lobo1.jpg">
        <p>Legenda</p>
    </div>
    <div class="grid3item">
        <img src="img/lobo2.jpg">
        <p>Legenda</p>
    </div>
</section>
```
#

***css***
```css
.grid3 {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    grid-gap: 20px;
    margin: 0 auto;
    max-width: 800px;
    padding: 10px;
}

.grid3item:nth-child(1){
    grid-row: 1 / 3;
}

.grid3item {
    display: grid;
}

.grid3item img {
    grid-column: 1;
    grid-row: 1 / 3;
    align-self: end;
}

.grid3item p {
    background: rgba(0, 0, 0, 0.6);
    padding: 10px;
    color: #fff;
    grid-column: 1;
    grid-row: 2  ;
    align-self: end;
}
```

## I learned Flexbox and Grid from this [video](https://youtu.be/x-4z_u8LcGc): https://youtu.be/x-4z_u8LcGc. 

# *Thanks for Read*
