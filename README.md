# CSS-Only Interactive Image
I wanted to create an interactive image using pure CSS - the idea was to have a different image depending on where the user clicked. 

## How it works
Using buttons and their active and focus states, we can set the image content to another path/url.

```css
img {
  content: url("image.jpg")
}

button:active ~ img,
button:focus ~ img {
  content: url("new-image.jpg")
}
```

## Preview
![ezgif-3-7c7f7c0ab8](https://github.com/yilverdeja/interactive-image-css/assets/29952939/a1f871d3-bc5f-4502-ba3a-b65660d89203)
