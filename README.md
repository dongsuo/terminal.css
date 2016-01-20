## Terminal

Want a cool terminal window on your webiste like [consul.io](https://www.consul.io)? Add termial.css and see markup below or example.html.

![terminal](https://raw.github.com/isabellatromba/css/master/terminal.png)

The width of the terminal class is 100% so it will resize depending on its parent container. The cursor class has an animation causing it to blink every 1s.

```html
<div class="terminal">
  <div class="header">
    <h4>Terminal</h4>
      <ul class="shell-dots">
        <li class="red"></li>
        <li class="yellow"></li>
        <li class="green"></li>
      </ul>
    </div>
    <div class="terminal-window">
      <p>
        <span class="prompt">$</span><span class="cmd">cd code</span>
      </p>
      <p>
        <span class="prompt">$</span><span class="cmd">git clone https://github.com/isabellatromba/css.git</span>
      </p>
      <p>
        <span class="prompt">$</span><span class="cursor">&nbsp</span>
      </p>
    </div>
  </div>
</div>
```
