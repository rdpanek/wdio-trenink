# DevTools Console

## window

`window.document.defaultView`
- globalni objekt, pro kazdy tab

---

`window.open('http://www.seznam.cz', 'dataWindow')`

---

```
let promena = 'Ahoj'
console.log(promena);
```

---

`let objekt = {a:10}; console.log(objekt)`

---

## Document
- je objekt, ktery referencuje dokument ve window

`document`

`console.log(window.document.title);`

`console.error('Mas tam chybu: ${new Date()}');`

---

```
document.location

document.location.protocol

window.isSecureContext
```

---

`document.isConnected`

---

`document.getElementById('tesla-logo')`

---

```

document.head

document.body

document.images

document.links

document.readyState

```

---

```
window.scrollBy({
  top: 100,
  left: 0,
  behavior: 'smooth'
});
```
---

```document.querySelectorAll('*')```

---

```$x('//a')```

---

```window.addEventListener('click', function() {alert("TAB")})```

```
document.getElementById("tesla-logo").addEventListener("click", function(){
  document.getElementById("tesla-logo").innerHTML = "VW Caravelle";
});
```

---

```
history.forward()

history.back();

history.length

```

---

```
let cars = ["Saab", "Volvo", "BMW"];
cars.length
cars.forEach(car => { console.log(car)})

```

---

```
Math.floor(Math.random() * 10);
```

---

```
localStorage.setItem('myCat', 'Tom');
const cat = localStorage.getItem('myCat');
localStorage.removeItem('myCat');
localStorage.clear();

```

---

```
window.setInterval(vypis, 500, 'Teslicku');
let i = 0
function vypis(auto) {
    console.log(`Ja chci ${auto} ${i}`)
    i++
}
```

