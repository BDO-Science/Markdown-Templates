---
title: "Presentation" # The title of the presentation
subtitle: "Exploring Quarto and PowerPoint Integration" # An optional subtitle for the presentation
author: "Your Name" # The name of the author(s) of the presentation
date: "December 04, 2024" # Automatically inserts the current date in "Month Day, Year" format
format: # Specifies the output format options for the presentation
  pptx: # Indicates that the output will be a PowerPoint (.pptx) file
    reference-doc: "template.pptx" # Path to a custom PowerPoint template for consistent branding/styling
    slide-level: 2 # Sets the heading level (##) at which new slides are created
    toc: true # Adds a table of contents slide at the beginning of the presentation
    toc-depth: 1 # Only include top-level headings
    slide-number: true # Enables slide numbers on each slide
    aspect-ratio: 16:9 # Sets the aspect ratio for the slides (e.g., widescreen)
    fig-width: 5 # Default width (in inches) for figures included in the presentation
    fig-height: 4 # Default height (in inches) for figures included in the presentation
    fig-dpi: 300 # Sets the resolution (dots per inch) for figures to ensure clarity
    keep-md: true # Retains the intermediate Markdown file generated during rendering
    keep-source: true # Keeps the source file for debugging or re-rendering
    highlight-style: "breezedark" # Specifies the syntax highlighting style for code chunks
    output-file: "Presentation.pptx" # The name of the generated PowerPoint file
metadata: # Allows custom metadata fields for additional information
  department: "Bureau of Reclamation" # Custom metadata: department name
  project: "Quarto Templates" # Custom metadata: project title
---




## Introduction

- **Overview**: This presentation demonstrates how to create a PowerPoint presentation using Quarto and R.
- **Objectives**:
  - Learn how to structure a presentation.
  - Use code, figures, and tables within slides.

## Code Example

Here is an example of R code:


::: {.cell}
::: {.cell-output .cell-output-stdout}
```
[1] 30
```
:::
:::


## Figure Example


::: {.cell}
::: {.cell-output-display}
![](Presentation_files/figure-pptx/unnamed-chunk-2-1.png)
:::
:::


## Table Example


::: {.cell}
::: {.cell-output-display}
|Category | Value|
|:--------|-----:|
|A        |   100|
|B        |   200|
|C        |   300|
:::
:::


## Formatting Examples: Text Styles

- **Bold Text Example**: **This text is bold** for emphasis.
- *Italicized Text Example*: *This text is italicized* for a softer emphasis.
- ***Bold and Italicized Text Example***: ***Combine bold and italics*** for stronger emphasis.
- __Underlined Text Example__: <u>This text is underlined</u> (use sparingly).

---

## Formatting Examples: More Styles

- Strikethrough Example: ~~This text is crossed out~~.
- **Font Color Example**: <span style="color:blue">This text is blue</span>.
- **Font Size Example**: <span style="font-size:18px">This text is larger</span>.
- **Highlight Example**: <mark>This text is highlighted</mark>.

---

### List Formatting Examples

- **Ordered List Example:**
  1. First item
  2. Second item
  3. Third item

- **Unordered List Example:**
  - First bullet
  - Second bullet
  - Third bullet

---

### More Formatting Examples

- **Nested List Example:**
  - Parent Item
    - Child Item 1
    - Child Item 2

---

### Inline Code and Monospace Font

- **Inline Code Example**: Use `inline code` for technical terms or file paths.
- **Monospace Font Example**: <span style="font-family:Courier;">This text is in monospace font.</span>

---

### Alignment and Spacing

- **Left-Aligned Text** (default)
  - Example of left-aligned text.
- **Center-Aligned Text**:
  <div style="text-align: center;">This text is centered.</div>
- **Right-Aligned Text**:
  <div style="text-align: right;">This text is right-aligned.</div>

---

### Advanced Manipulations

- **Hyperlinks**: [Visit Quarto Documentation](https://quarto.org)
- **Images with Captions**:
  ![Example Image](https://via.placeholder.com/300x150 "Placeholder Image"){width=60%}
  - *Caption*: A placeholder image with a caption.
- **Blockquotes**: 
  > "This is an example of a blockquote for emphasizing important quotes or ideas."

