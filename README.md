stack: [VS Code] + [Firefox] + [iTerm2] + [micro-editor]

directory:
```
	htmlcss-w3/
		index.html
		css/
			styles.css
		imgs/
```
task – create with [bash]

**Note:** 
- `linear-gradient` creates a smooth color blend, 
- `box-shadow` adds a soft shadow under each section,
- `<a href="https://memosynth.net/" target="_blank" class="">memosynth.net</a>

## Fonts

Option (⌥) key + Finder’s Go: `Library > Fonts

Embed code in the `<head>` of your html
```
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Syne+Mono&display=swap" rel="stylesheet">
```

Syne Mono: CSS class
```
.syne-mono-regular {
  font-family: "Syne Mono", monospace;
  font-weight: 400;
  font-style: normal;
}
```
## Reusable components

As your site grows, extract repeated markup into reusable chunks:

- Create partial HTML files (header, footer, nav) and include them server-side, or copy/paste carefully for static sites.
- Group utility classes (e.g., `.text-center`, `.mt-2`) in a separate stylesheet to keep designs consistent.
