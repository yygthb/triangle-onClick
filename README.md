### Задача:

Событие: Click внутри красных границ (не по треугольнику) в области зеленого прямоугольника

Результат: "click on Rectangle" в консоли

![](https://sun9-68.userapi.com/impg/NIkW9ZY2m0eQLfwNYuYOMJK8nI_HbWjFyqOscA/uLeixprroI4.jpg?size=287x179&quality=96&proxy=1&sign=66dfbdcfcc870f48a393ac9d4783e0a4&type=album)

---

<details>
  <summary>Решение</summary>
  
  <br/>
  HTML:<br/>
  &nbsp; &lt;svg&gt; <br/>
  &nbsp;&nbsp; &lt;polygon&gt;&lt;/polygon&gt; <br/>
  &nbsp; &lt;/svg&gt;
  
  <br/>
  <br/>
  CSS:<br/>
  &nbsp;&nbsp; svg {pointer-events: none}<br/>
  &nbsp;&nbsp; poligon {pointer-events: all}<br/>
</details>
