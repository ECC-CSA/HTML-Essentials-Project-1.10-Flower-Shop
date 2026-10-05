# 1.10.1 Designing a Simple Page for a Flower Shop

## Scenario

**Bloom & Petal Haven** is a neighborhood flower shop known for beautiful flower arrangements and indoor plants. The shop wants to begin selling products online, including flowers, plants, and plant accessories for people decorating their homes or purchasing gifts.

As part of an interview for a Front End Developer position at Bloom & Petal Haven, you will demonstrate your HTML skills by creating a simple, minimal webpage.

Your webpage will feature two popular indoor plants:

- Peace Lily
- Zanzibar Gem

The page should provide a description, price, and image for each plant.

## Learning Goals

By completing this activity, you will practice how to:

- Build a complete HTML5 document.
- Use the `<head>` and `<body>` sections correctly.
- Add a webpage title and metadata.
- Set UTF-8 character encoding.
- Use headings and paragraphs to organize content.
- Add images with meaningful alternative text.
- Test a webpage in a browser.

## Your Task

Create or edit the `index.html` file in this project.

Build a webpage titled **Indoor Plants** for Bloom & Petal Haven. Your webpage must include information about a Peace Lily and a Zanzibar Gem.

Keep the page simple, readable, and organized. Focus on using correct HTML structure and elements.

## Required HTML Structure

Your `index.html` file must include the following foundational HTML5 structure:

```html
<!doctype html>
<html lang="en">
<head>
  <!-- Page information goes here -->
</head>
<body>
  <!-- Visible page content goes here -->
</body>
</html>
```

## Requirements

### 1. Document Setup

Your file must:

- Begin with the HTML5 `<!doctype html>` declaration.
- Use opening and closing `<html>` tags.
- Include both a `<head>` section and a `<body>` section.
- Set the language of the page to English using `lang="en"` on the `<html>` element.

### 2. Head Section

Inside the `<head>` section, include all of the following:

| Element | Required Value |
|---|---|
| Page title | `<title>Indoor Plants</title>` |
| Character encoding | `<meta charset="UTF-8">` |
| Meta description | `name="description"` |
| Description content | `Explore a variety of indoor plants for your home or office.` |

Your metadata should look similar to this:

```html
<head>
  <meta charset="UTF-8">
  <meta
    name="description"
    content="Explore a variety of indoor plants for your home or office."
  >
  <title>Indoor Plants</title>
</head>
```

### 3. Body Content

Inside the `<body>` section, include:

- One `<h1>` heading with the text `Indoor Plants`.
- One `<h2>` heading with the text `Peace Lily`.
- One `<h2>` heading with the text `Zanzibar Gem`.
- A description paragraph and price paragraph for each plant.
- An image for each plant.
- Alternative text for each image.

## Plant Content

Use the following required content on your webpage.

| Plant | Description | Price |
|---|---|---|
| Peace Lily | The Peace Lily, known for its elegant white flowers, is a popular choice for indoor spaces. | Price: $15 |
| Zanzibar Gem | The Zanzibar Gem, with its glossy green foliage, is a low-maintenance indoor plant perfect for beginners. | Price: $20 |

## Required Images

Use the image URLs and alternative text below.

| Plant | Image Source | Alternative Text |
|---|---|---|
| Peace Lily | `https://edube.org/uploads/media/default/0001/04/spathiphyllum-peace-lily.jpg` | `Peace Lily` |
| Zanzibar Gem | `https://edube.org/uploads/media/default/0001/04/zamioculcas-zanzibar-gem.jpg` | `Zanzibar Gem` |

Example image syntax:

```html
<img
  src="[https://edube.org/uploads/media/default/0001/04/spathiphyllum-peace-lily.jpg](https://edube.org/uploads/media/default/0001/04/spathiphyllum-peace-lily.jpg)"
  alt="Peace Lily"
>
```

## Suggested Page Outline

Use this outline to organize your webpage:

```html
<body>
  <h1>Indoor Plants</h1>

  <h2>Peace Lily</h2>
  <p>The Peace Lily, known for its elegant white flowers, is a popular choice for indoor spaces.</p>
  <p>Price: $15</p>
  <img
    src="[https://edube.org/uploads/media/default/0001/04/spathiphyllum-peace-lily.jpg](https://edube.org/uploads/media/default/0001/04/spathiphyllum-peace-lily.jpg)"
    alt="Peace Lily"
  >

  <h2>Zanzibar Gem</h2>
  <p>The Zanzibar Gem, with its glossy green foliage, is a low-maintenance indoor plant perfect for beginners.</p>
  <p>Price: $20</p>
  <img
    src="[https://edube.org/uploads/media/default/0001/04/zamioculcas-zanzibar-gem.jpg](https://edube.org/uploads/media/default/0001/04/zamioculcas-zanzibar-gem.jpg)"
    alt="Zanzibar Gem"
  >
</body>
```

## Quality Checklist

Before submitting, review your webpage and verify the following:

- [ ] The file is named `index.html`.
- [ ] The page begins with `<!doctype html>`.
- [ ] The page includes `<html>`, `<head>`, and `<body>` elements.
- [ ] The `<html>` element uses `lang="en"`.
- [ ] The character encoding is set to UTF-8.
- [ ] The page title is `Indoor Plants`.
- [ ] The meta description uses the required text.
- [ ] The body includes an `<h1>` heading titled `Indoor Plants`.
- [ ] The page includes an `<h2>` for `Peace Lily`.
- [ ] The page includes an `<h2>` for `Zanzibar Gem`.
- [ ] Each plant has a description paragraph.
- [ ] Each plant has a price paragraph.
- [ ] Each plant has an image.
- [ ] Each image includes the required `alt` text.
- [ ] Both images load correctly in the browser.
- [ ] Your code is indented and easy to read.

## Assessment Criteria

| Criteria | Meets Expectation |
|---|---|
| HTML document structure | Uses a complete HTML5 document structure with `<!doctype html>`, `<html>`, `<head>`, and `<body>`. |
| Metadata | Includes UTF-8 character encoding, the required meta description, and the title `Indoor Plants`. |
| Headings and text | Includes the required `<h1>`, two `<h2>` elements, descriptions, and prices. |
| Images and accessibility | Includes both required images and meaningful `alt` text. |
| Code quality | HTML is organized, readable, and displays correctly in a browser. |

## Extension Challenge

After completing every required item, you may improve the page by adding one or more of the following:

- Add another indoor plant with a heading, description, price, and image.
- Add a short introduction paragraph below the main heading.
- Add a `<header>` or `<main>` element to improve page organization.
- Add a list of basic plant-care tips.
- Add image `width` or `height` attributes to make the images fit more neatly on the page.
- Add a footer with Bloom & Petal Haven contact information.

The extension challenge is optional unless your instructor provides different directions.