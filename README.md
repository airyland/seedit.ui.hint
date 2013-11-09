# hint

---

CSS3 文字提示

---

## 演示

<link type="text/css" rel="stylesheet" media="screen" href="src/hint.css">

### 默认

方向可选：`hint--top`, `hint--bottom`, `hint--left`, `hint--right`
````html
Hello Sir, <span class="hint--bottom" data-hint="Thank you!">hover me.</span>
````

````html
<a href="javascript:void(0)" class="hint--top" data-hint="Yeah, I am >:D">Look, there is something over me.</a>
````

````html
 <a href="javascript:void(0)" class="hint--right" data-hint="Are you sure you are?">I am always right!</a>
````

````html
 <a href="javascript:void(0)" class="hint--bottom" data-hint="Sure. Cheers!">How about a bottoms up?</a>
````

````html
 <a href="javascript:void(0)" class="hint--left" data-hint="LEFT-over Sir...">What do we get now?</a>
````

### 不同类型

可选类型：
 `hint--error`
 `hint--info`
 `hint--warning`
 `hint--success`
 `hint--always`
 `hint--rounded`
 `hint--bounce`

````html
<p>
                    <a href="javascript:void(0)" class="hint--top  hint--error" data-hint="This is an error tooltip">Oh man! You are gonna self-destruct in 5 sec.</a>
                </p>
                
                <p>
                    <a href="javascript:void(0)" class="hint--left  hint--warning" data-hint="This is a warning tooltip">You did something wrong!</a>
                </p>
                
                <p>
                    <a href="javascript:void(0)" class="hint--bottom  hint--info" data-hint="This is an info tooltip">You can use different classes for different types of tooltips.</a>
                </p>

                <p>
                    <a href="javascript:void(0)" class="hint--left  hint--success" data-hint="This is a success tooltip">Hurray! You have seen all 4 context types.</a>
                </p>

        <h3>Extra</h3>

                <p>
                    <a href="javascript:void(0)" class="hint--right  hint--always" data-hint="...which always keep showing">You can also make tooltips...</a>
                </p>

        <p>
          <a class="hint--right  hint--success  hint--rounded" data-hint="We have rounded corners for you">Hmm...So you don't like sharp edges?</a>
        </p>

        <h3>Effects</h3>

        <p>
          <a href="javascript:void(0)" class="hint--right  hint--bounce" data-hint="Bounce">Adding a <code>hint--bounce</code> class gives you that...</a>
        </p>

````


### 浏览器支持
**hint.css** works on all latest browsers, though the transition effect is supported only on IE10+, Chrome 26+ and FF4+ at present.

- Chrome - basic + transition effects
- Firefox - basic + transition effects
- Opera - basic
- Safari - basic
- IE 10+ - basic + transition effects
- IE 8 & 9 - basic


