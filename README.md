Forms.css
=========
General cross browser styles for forms and buttons. This is a base and does not provide much in the terms of branding. This is meant to be a starting point for all forms and buttons to allow for consisitant structural styling accross all browsers.

Styles tested in: IE7+, Firefox 8, Safari 5, and Chrome 15.

###Basic HTML
Basic HTML structure borrowed from [Twitter Bootstrap](http://twitter.github.com/bootstrap)

```html
<form>
    <div class="spot">
        <label for="input">Label</label>
        <div class="input">
            <input type="text" id="input"/>
        </div>
    </div>
</form>
```

###Button HTML
`.button` can be applied to either button or anchor elements.

```html
<button class="button">Button</button>
<a href="#" class="button">Anchor Button</a>
```

A few basic button styles are provided.

* `.button`: this is the basis for all buttons, and can be used for general button styling
* `.primary`: primary call to action
* `.negative`: negative call to action (e.g. delete)
* `.link`: hyperlink type button with no background or border
* `.full-width`: 100% width button, good for mobile
