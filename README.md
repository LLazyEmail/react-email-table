# yarn add react-email-components-table

[![Greenkeeper badge](https://badges.greenkeeper.io/jaebradley/example-rollup-react-component-npm-package.svg)](https://greenkeeper.io/)
![Example Rollup React Component NPM Package](https://github.com/jaebradley/example-rollup-react-component-npm-package/workflows/Example%20Rollup%20React%20Component%20NPM%20Package/badge.svg)
[![codecov](https://codecov.io/gh/jaebradley/example-rollup-react-component-npm-package/branch/master/graph/badge.svg)](https://codecov.io/gh/jaebradley/example-rollup-react-component-npm-package)
[![npm](https://img.shields.io/npm/dt/@jaebradley/example-rollup-react-component-npm-package.svg)](https://www.npmjs.com/package/@jaebradley/example-rollup-react-component-npm-package)
[![npm](https://img.shields.io/npm/v/@jaebradley/example-rollup-react-component-npm-package.svg)](https://www.npmjs.com/package/@jaebradley/example-rollup-react-component-npm-package)

Example `React` component "library" using [`rollup`](https://github.com/rollup/rollup) that is published to `npm`.


My requirements for this package were

1. Use `babel`
2. Use `semantic-release`
3. Use `sass`
4. Support `umd` and `es` modules
5. Use `storybook`
6. Make the exported components really simple

---


```bash
├── xxx
│   ├── xxx
│   │   ├── **/*.xxx
│   ├── xxx
│   ├── images
│   ├── xxx
│   ├── js
│   │   ├── **/*.js
│   └── xxx
├── dist (or build)
├── 
├── 
├── 
├── 
├── README.md
├── package.json
├── 
└── .gitignore
```


# Components inside
- Table
- BasicTable
- Row
- Rows
- Section
- TableLeft


### Table

Main Table component, aka Raw table

### BasicTable

this is a simple wrapper around table, with just a set of basic attributes

```
<table 
    border="0" 
    cellpadding="0" 
    cellspacing="0" 
    role="presentation" 
    width="100%">
    <tbody>
      ...
    </tbody>
  </table>
```

### Row

Row should help a little bit to remove a number of lines.
Can be with or without `<tbody>`
```
 <table
    className={className}
    dir={reverse && 'rtl'}
>
    <tbody className={bodyClassName}>
    <tr>
        {children}
    </tr>
    </tbody>
</table>
```

### Rows

Rows is my interpretation of a previous component.
I just want to have a support for a few TR`s if it will be necessary

like:
```
<tbody>
    <tr>
        <td align="center" valign="top" class="big-title" style="-webkit-text-size-adjust: 100%; ...">...</td>
    </tr>
    <tr>
        <td align="center" valign="top" style="padding-bottom: 30px; ...">
            ...
        </td>
    </tr>
    <tr>
        <td align="center" valign="top" class="board-pic" style="padding-bottom: 40px; ...">...</td>
    </tr>
```

### Section

### TableLeft




#### Arthur Tkachenko articles

* [https://hackernoon.com/5-reasons-why-newsletters-should-be-part-of-your-business-strategy](https://hackernoon.com/5-reasons-why-newsletters-should-be-part-of-your-business-strategy)
* [https://hackernoon.com/organizing-an-advanced-structure-for-html-email-template](https://hackernoon.com/organizing-an-advanced-structure-for-html-email-template)
* [https://hackernoon.com/how-i-started-to-build-react-components-for-email-templates](https://hackernoon.com/how-i-started-to-build-react-components-for-email-templates)
* [https://hackernoon.com/introducing-a-simple-npm-module-with-email-templates](https://hackernoon.com/introducing-a-simple-npm-module-with-email-templates)
* [https://hackernoon.com/glossary-for-non-technies](https://hackernoon.com/glossary-for-non-technies)
* [https://hackernoon.com/email-marketing-and-how-to-curate-an-effective-business-newsletter](https://hackernoon.com/email-marketing-and-how-to-curate-an-effective-business-newsletter)
* [https://hackernoon.com/exploring-substack-for-building-your-newsletter](https://hackernoon.com/exploring-substack-for-building-your-newsletter)
* [https://hackernoon.com/building-a-design-system-for-email-templates-react](https://hackernoon.com/building-a-design-system-for-email-templates-react)
* [https://hackernoon.com/together4victory-list-of-email-marketing-tools](https://hackernoon.com/together4victory-list-of-email-marketing-tools)
* [https://hackernoon.com/cool-newsletters-for-developers-part-1](https://hackernoon.com/cool-newsletters-for-developers-part-1)
* [https://hackernoon.com/cool-resources-for-sending-emails](https://hackernoon.com/cool-resources-for-sending-emails)

## React Design System
- [React Design System](https://llazyemail.github.io/documentation/docs/React-Design-System)
- [React-section](https://llazyemail.github.io/documentation/docs/React-Design-System/React-section)
- [React tasks](https://llazyemail.github.io/documentation/docs/React-Design-System/react-tasks)
