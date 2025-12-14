# TailwindCSS Smooth Shadow Plugin

Utilities that extend Tailwind's shadow scale with a multi-layer, soft “smooth” shadow.

## Usage

Install and import the plugin stylesheet:

```
npm install shadow-plugin
```

```css
@import "tailwindcss";
@import "shadow-plugin";
```

Apply a shadow using the provided utilities:

```html
<div class="smooth-shadow"></div>
<div class="smooth-shadow-sm"></div>
<div class="smooth-shadow-xl"></div>
```

You can also set the shadow color via tokens or current color:

```html
<div class="smooth-shadow-xl shadow-red-500"></div>
<div class="text-neutral-900 smooth-shadow-lg"></div>
```

## License

MIT
