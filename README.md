# Creating a webapp for an Electronic music event.

## [Figma Link](https://www.figma.com/file/4Y7QwEMBxB7xLZquJrUdoC/jon-merila-grafik-fend23?type=design&node-id=9%3A2&mode=design&t=2ZtcKdFq8E8F9vPb-1)

Fonts used:

- Inter

- Cherry bomb one

- Font Awesome 6

---

I did try to use FontAwesome but I had some issues, I've included svg's of the icons that I used in the "icons" folder and in the fonts list for future use.

---

Link to paste in HTML head to get both of the fonts:

```HTML
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Cherry+Bomb+One&family=Inter:wght@100..900&display=swap" rel="stylesheet">
```

### If you want to link FontAwesome & are also using Bootstrap:

```HTML
<link href="//netdna.bootstrapcdn.com/twitter-bootstrap/2.3.2/css/bootstrap-combined.no-icons.min.css" rel="stylesheet">
<link href="//netdna.bootstrapcdn.com/font-awesome/3.2.1/css/font-awesome.css" rel="stylesheet">

```

**If you only want Fontawesome without Bootstrap, don't include the first link.**

---

### CSS for the Fonts:

```CSS
.cherry-bomb one-regular {
font-family: "Cherry Bomb One", system-ui;
font-weight: 400;
font-style: normal;
}

```

#### Font-weight for Cherry bomb is set to 400.

---

```CSS
.inter {
font-family: "Inter", sans-serif;
font-optical-sizing: auto;
font-weight: <weight>;
font-style: normal;
font-variation-settings:
"slnt" 0;
}
```

// `<weight>`: Use a value from 100 to 900 to set font-weight.

---

### Motivation

I took a picture from a festival, not originally my picture.
I used squoosh.app to "squash" the image size down and also formatted it to a .webp file. If fallback is needed, I decided do use a .jpg because JPEG is a lossy format that works well with photographs that has alot of color gradients.
