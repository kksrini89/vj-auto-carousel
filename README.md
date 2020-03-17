# vj-auto-carousel

> To generate carousel based on container element count.

## Install

```
 npm install vj-auto-carousel -S
```

## Usage
```html
<vj-auto-carousel length="5">
    <div slot="default">
        Hello this is default text.
    </div>
</vj-auto-carousel>
```
```css
<style>
 :root {
    --default-carousel-bg-color: #fff;
    --selected-carousel-bg-color: #fdabe9;
 }
</style>
```

## Attributes

### length
Accepts elements count value residing within a container html element.

### default slot
For custom message to be displayed.


## License
MIT &copy; [Srinivasan K K](https://srinivasankk.com)