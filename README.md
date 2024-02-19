# astro-inline-svg

Icon component to inline svg files. Meant to be copy pasted into your project, it's just two files.

Dedupes multiple svg file imports using symbols.

Doesn't require a specific folder structure, just import any svg file from anywhere.

Do whatever you want with it.

## Usage

```astro
---
import Icon from '@components/Icon.astro'
---

<Icon 
    src={import('@icons/heroicons/24/solid/chevron-down.svg')}
    class='h-5 w-5 fill-current'
    />
```

## Install

```
npm install -D cheerio fast-xml-parser debug
```

## Credit

Credit to https://github.com/natemoo-re/astro-icon for implementing svg symbols