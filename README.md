# 🎨 CSS Pseudo-Classes & Pseudo-Elements Cheat Sheet

A categorized list of commonly used **CSS pseudo-classes** and **pseudo-elements**, including browser-specific ones like `::-webkit-*` to help you style built-in form controls and interactive elements.

---

## 📌 Pseudo-Elements (Standard)

These let you style parts of elements or insert virtual content.

| Pseudo-Element     | Description |
|--------------------|-------------|
| `::before`         | Inserts content before an element. |
| `::after`          | Inserts content after an element. |
| `::placeholder`    | Styles the placeholder text in input fields. |
| `::selection`      | Styles text selected by the user. |
| `::first-letter`   | Styles the first letter of a block of text. |
| `::first-line`     | Styles the first line of a block of text. |
| `::marker`         | Styles the bullet or number in lists. |

---

## 💡 Pseudo-Classes (Standard)

These apply styles based on element states or positions.

| Pseudo-Class       | Description |
|--------------------|-------------|
| `:hover`           | When the user hovers over an element. |
| `:focus`           | When an element receives focus. |
| `:active`          | While an element is being clicked. |
| `:checked`         | For checked checkboxes or radio buttons. |
| `:disabled`        | Targets disabled form elements. |
| `:enabled`         | Targets enabled form elements. |
| `:required`        | Inputs with the `required` attribute. |
| `:optional`        | Inputs without the `required` attribute. |
| `:valid`           | Form elements that pass validation. |
| `:invalid`         | Form elements that fail validation. |
| `:first-child`     | The first child of a parent element. |
| `:last-child`      | The last child of a parent element. |
| `:nth-child(n)`    | Selects the nth child of a parent. |
| `:not(selector)`   | Selects elements not matching a selector. |
| `:is(selector)`    | Matches elements against a list of selectors. |

---

## 🧪 Browser-Specific Pseudo-Elements (`::-webkit-*`)

These apply mainly in WebKit-based browsers (Chrome, Safari, Edge).

| Pseudo-Element                        | Description |
|--------------------------------------|-------------|
| `::-webkit-calendar-picker-indicator` | The dropdown icon in date/time inputs. |
| `::-webkit-inner-spin-button`         | The spinner inside number inputs. |
| `::-webkit-outer-spin-button`         | The outer spinner in number inputs. |
| `::-webkit-search-cancel-button`      | The clear "×" button in search inputs. |
| `::-webkit-search-decoration`         | Decoration in search inputs (rare). |
| `::-webkit-slider-runnable-track`     | The track part of a range slider. |
| `::-webkit-slider-thumb`              | The draggable thumb of a range slider. |
| `::-webkit-progress-bar`              | The background of a `<progress>` bar. |
| `::-webkit-progress-value`            | The filled part of a `<progress>` bar. |
| `::-webkit-scrollbar`                 | Styles the whole scrollbar. |
| `::-webkit-scrollbar-thumb`           | Styles the draggable scrollbar handle. |
| `::-webkit-scrollbar-track`           | Styles the scrollbar track area. |

> ⚠️ Note: These are not standardized across all browsers. Always test in multiple environments.

---

## 🚫 Limitations

- **`<datalist>` styling is not fully supported** — you cannot style the dropdown box or remove the dropdown arrow in most browsers.
- **Browser-specific pseudo-elements** (e.g., `::-webkit-*`) may not work in Firefox or legacy browsers.
- For full design control, consider using custom dropdowns or JavaScript-based components.

---

## 📚 Resources

- [MDN Web Docs: Pseudo-classes](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes)
- [MDN Web Docs: Pseudo-elements](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-elements)
- [Can I Use: WebKit pseudo-elements](https://caniuse.com/)

---

`If you know other, feel free to contribute!`
