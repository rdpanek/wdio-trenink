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

`console.log(window.document.title);`

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

---