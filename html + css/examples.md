# Html && Css

# Способы центровки
#### Размеры контейнера и блока неважены
* transform: translate

##### HTML
```html
<body>
  <div class="center">
    Text
  </div>
</body>
```

##### Css
```css
body, html{
  height:100%;
}

.center {
  position: relative; /* or absolute */
  top: 50%;
  left: 50%;
  transform: translate(-50%,-50%);

  height: 300px;
  width: 300px;
  background-color: red;
}
```

* flex  https://jsfiddle.net/6gwuvtgo/1/
* table: cell http://jsfiddle.net/c1bgfffq/1142/
* Если контент в одну строчку - line-height http://jsfiddle.net/c1bgfffq/12/

#### Размеры контейнера известны
* отрицательный margin-top http://jsfiddle.net/c1bgfffq/13/

#### Размеры блока известны
* absolute top:0 bottom: 0 http://jsfiddle.net/c1bgfffq/4/

#### Размеры контейнера и блока известны
* обычные отступы  http://jsfiddle.net/c1bgfffq/6/