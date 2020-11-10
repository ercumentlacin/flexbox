# Flexbox

---

## Flexbox Neden Çıktı ?

Daha önceden iki kutuyu yan yana getirebilmek için için 

```css
float: left;
```

yapıp, ardından clear fix yani

```css
clear: both;
```

yapıyorduk.

## Flexbox Ne Yapıyor ?

Belli bir container içindeki elemanları istediğimiz gibi yerleştirme imkanı sunuyor. 

---

## Nasıl Kullanırız ?

```css
.container{
	display: flex;
}
```

dediğimiz anda container sınıfına flex çzelliğini katmış oluyoruz.

## Özellikleri



| Kapsayıcı         | Eleman        |
| ----------------- | ------------- |
| - flex-direction  | - align-self  |
| -flex-wrap        | - flex-grow   |
| - justify-content | - flex-shrink |
| - align-content   | - order       |



---



### flex-wrap

yani sarmala, içindeki itemler birden fazla satır olsun mu veya tek satırda kalsın mı ? bunu belirlemize yarıyor.

```css
flex-wrap: nowrap; /* default, satır atlama demek*/
flex-wrap: wrap;
flex-wrap: wrap-reverse;
```

---

### flex-direction

```css
.container{
	flex-direction: row | row-reverse | column | column-reverse;
}
```

- row (default): soldan sağa dizilir
- row-reverse: sağdan sola dizilir
- column: sütüna dizilir
- column-reverse: sütüna ters

---

### justify-content

![justify-content](https://github.com/ercumentlacin/flexbox/blob/main/justify-content.svg)

---

### align-items

![align-items](https://github.com/ercumentlacin/flexbox/blob/main/align-items.png)

---

### align-content

![align-content](https://github.com/ercumentlacin/flexbox/blob/main/align-content.png)

---

### align-self

bağımsız dikeyde konumlanma

---



### flex-grow

yayılma diyebiliriz 

---

### flex-shrink

growun tam tersi

---

### order

sıralama
