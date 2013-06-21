iCSSCheckBox
============

CSS3 iPhone style checkbox. [Live demo](http://youssefkababe.com/iCSSCheckBox/)

![iCSSCheckbox](http://i.imgur.com/KVDW2vB.png)

### How to use:

First add the icsscheckbox.css file to your project's files then add a link to the page you want to use the checkbox in:

```html
<link rel="stylesheet" href="icsscheckbox.css">
```

Use the following html code to place the checkbox in your page:

```html
<label class="icheckwraper">
    <span class="icheckbox">
      <input type="checkbox" id="icheckbox1">
      <label class="ihandle" for="icheckbox1"></label>
    </span>
    <label class="ichecklabel" for="icheckbox1">I'm a cool iCSSCheckBox!</label>
</label>
```

Don't forget to replace "icheckbox1" for other checkboxes if you are using multiple ones in your page.

You can also change the Yes/No to something else by adding a custom styling before closing the head tag:

```html
<style type="text/css">
    .icheckbox .ihandle:before {
      content: "On";
    }
    
    .icheckbox .ihandle:after {
      content: "Off";
    }
</style>
```
