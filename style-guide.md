# Essential Stuff

## Html import links

Google font

``` html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link
  href="https://fonts.googleapis.com/css2?family=Poppins:wght@700&family=Roboto:wght@400;700&family=Saira+Stencil+One&display=swap"
  rel="stylesheet">
```

Ionicon

``` html
<script type="module" src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"></script>
<script nomodule src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js"></script>
```

---

## Colors

``` css
--raw-seinna: hsl(24, 74%, 58%);
--sizzling-sunrise: hsl(51, 95%, 54%);
--scarlet: hsl(13, 96%, 47%);
--black: hsl(0, 0%, 0%);
--white: hsl(0, 0%, 100%);
```

## Typography

``` css
--ff-saira-stencil-one: "Saira Stencil One", sans-serif; 
--ff-poppins: 'Poppins', sans-serif;
--ff-roboto: 'Roboto', sans-serif;

--fs-1: 2rem;
--fs-2: calc(1.813rem + 1vw);
--fs-3: calc(1.313rem + 1vw);
--fs-4: 1.4rem;
--fs-5: 1rem;
--fs-6: 0.813rem;
--fs-7: 0.75rem;

--fw-400: 400;
--fw-700: 700;
```

## Transition

``` css
--transition-1: 0.25s ease-in-out;
```

## Spacing

``` css
--section-padding: 80px;
```

## Border radius

``` css
--radius-4: 4px;
--radius-12: 12px;
```

---

## Theme Variables

### Dark Mode

``` css
--bg-primary: hsl(0, 0%, 12%);
--bg-secondary: hsl(0, 0%, 19%);
--color-primary: hsl(0, 0%, 100%);
--color-secondary: hsl(0, 0%, 62%);
--card-shadow: hsla(0, 0%, 0%, 0.4);
--input-bg: hsl(0, 0%, 16%);

--shadow-1: 10px 10px 40px var(--card-shadow);
```

### Light Mode

``` css
--bg-primary: hsl(0, 0%, 90%);
--bg-secondary: hsl(0, 0%, 100%);
--color-primary: hsl(0, 0%, 12%);
--color-secondary: hsl(0, 0%, 37%);
--card-shadow: hsla(0, 0%, 0%, 0.1);
--input-bg: hsl(0, 0%, 93%);

--shadow-1: 10px 10px 40px var(--card-shadow);
```
