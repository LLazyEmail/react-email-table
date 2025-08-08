


This repository provides a set of  components to easily compose email-compatible tables with flexible layout and styling. Below are the core components available, including the newly integrated ones:

## Components Overview

---

### BasicTable

Creates a basic, customizable table layout compatible with email clients. Supports defining headers, rows, and cell styles.

**Usage:**
```jsx
<BasicTable>
  {/* your table content */}
</BasicTable>
```

**Features:**
- Simple table structure.
- Supports nested rows and cells.
- Customizable styles via props.

**Example HTML output:**

```html
<table style="width: 100%; border-collapse: collapse;">
  <tr>
    <td style="padding: 10px; border: 1px solid #ccc;">Cell 1</td>
    <td style="padding: 10px; border: 1px solid #ccc;">Cell 2</td>
  </tr>
</table>
```

---

### Rows

Represents a collection of table rows. Used to generate multiple rows dynamically within `BasicTable`.

**Usage:**
```jsx
<Rows data={yourDataArray} renderRow={renderRowFunction} />
```

**Features:**
- Accepts data array and custom render function.
- Facilitates dynamic creation of rows.

**Example HTML output:**

```html
<tr>
  <td style="padding: 10px;">Data 1</td>
</tr>
<tr>
  <td style="padding: 10px;">Data 2</td>
</tr>
```

---

### TableLeft

A specialized component for creating left-aligned layout sections, e.g., sidebars or labels.

**Usage:**
```jsx
<TableLeft>
  {/* Content for the left side */}
</TableLeft>
```

**Features:**
- Content aligned to the left.
- Can be used within table cells for layout.

**Example HTML output:**

```html
<td style="text-align: left; padding: 10px;">
  Left-aligned content
</td>
```

---

### Sector

Represents a distinct section or segment within the email layout, useful for grouping or visual separation.

**Usage:**
```jsx
<Sector>
  {/* Content within the sector */}
</Sector>
```

**Features:**
- Encapsulates content visually.
- Supports custom styles.

**Example HTML output:**

```html
<div style="padding: 15px; border: 1px solid #ccc;">
  Sector content
</div>
```

---

## Summary

This set of React components enables building flexible, email-safe tables and layouts with clear, customizable structures. The included examples show how components translate into final HTML, giving you a preview of the output when rendering.

---
