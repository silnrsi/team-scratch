```css
html, body {
	margin: 0;
	padding: 0;
}

#main {
	color: #000;
	font-family: Arial, sans-serif;
}

.red {
	color: #900 !important;
}

@media screen and (min-width: 480px) {
    body {
        background-color: lightgreen;
    }
}

@media print {

    .printOnly {
        display: block !important;
    }

    .desktopOnly, .mobileOnly {
        display: none !important;
    }

}
```
