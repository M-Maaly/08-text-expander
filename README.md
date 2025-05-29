# 📝 React TextExpander Component

**A reusable and customizable **TextExpander** component built with React. It truncates long text and allows users to expand or collapse content dynamically. Useful for displaying previews, blog excerpts, or long paragraphs with toggling.
**

## ✨ Features

- Expand or collapse long text content.
- Customize:
  - Number of visible words when collapsed.
  - Button texts.
  - Button color.
  - Initial expanded state.
  - Additional styling via `className`.
- Fully reusable with any text content.

## 📦 Component Props

| Prop                | Type     | Default       | Description                                               |
|---------------------|----------|----------------|-----------------------------------------------------------|
| `expanded`          | `bool`   | `false`        | Whether the text is expanded initially.                   |
| `collapsedNumWords` | `number` | `10`           | Number of words to show when text is collapsed.           |
| `expandButtonText`  | `string` | `"Show more"`  | Text shown on the button to expand the content.           |
| `collapseButtonText`| `string` | `"Show less"`  | Text shown on the button to collapse the content.         |
| `buttonColor`       | `string` | `"blue"`       | The color of the toggle button text.                      |
| `className`         | `string` | `""`           | Custom class for styling the text container.              |
| `children`          | `string` | _required_     | The text content to be displayed and expanded/collapsed.  |

## 🔧 Example Usage

```jsx
<TextExpander
  collapsedNumWords={20}
  expandButtonText="Read more"
  collapseButtonText="Read less"
  buttonColor="#ff6622"
>
  Long paragraph of text goes here...
</TextExpander>
```

## 🚀 Getting Started

###  Clone the Repository

```bash
git clone https://github.com/yourusername/react-text-expander.git
cd react-text-expander
