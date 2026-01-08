# Cinematic Recipes - Semantic HTML Showcase

A pure HTML project demonstrating the power of **Semantic HTML** without any CSS or JavaScript. This project showcases famous dishes from films and TV series, built entirely with semantic HTML5 elements to achieve perfect accessibility, SEO, and structure.

## 🏆 Perfect Lighthouse Score

<img width="768" height="261" alt="Lighthouse Score - 99 Performance, 100 Accessibility, 100 Best Practices, 100 SEO" src="https://github.com/user-attachments/assets/8d5cb906-7770-490b-be8a-025ce7285e2a" />

This project achieves near-perfect scores across all Lighthouse metrics:
- **Performance**: 99/100
- **Accessibility**: 100/100
- **Best Practices**: 100/100
- **SEO**: 100/100

## 🎯 Project Overview

**Cinematic Recipes** is a recipe website featuring three iconic dishes from popular films and TV shows:

1. **Tony's "Panic Attack" Gabagool Special** - From *The Sopranos*
2. **The Big Kahuna Burger** - From *Pulp Fiction*
3. **Dorsia's Sea Urchin Ceviche** - From *American Psycho*

Each recipe includes ingredients, step-by-step instructions, trivia, and memorable quotes from the source material.

## 🏗️ Project Structure

```
mini-project1/
├── index.html              # Main HTML file (pure semantic HTML)
├── assets/
│   └── dorsia_favicon.png  # Favicon
└── README.md               # This file
```

## ✨ Key Features

### Pure Semantic HTML
- **No CSS**: Zero styling - relies entirely on browser default styles
- **No JavaScript**: Pure HTML functionality
- **100% Semantic**: Every element chosen for its semantic meaning

### Semantic Elements Used

#### Document Structure
- `<header>` - Page and article headers
- `<main>` - Main content wrapper
- `<section>` - Thematic grouping of content
- `<article>` - Self-contained recipe content
- `<aside>` - Supplementary trivia and quotes
- `<footer>` - Page and article footers
- `<nav>` - Navigation menu

#### Content Elements
- `<h1>` to `<h4>` - Hierarchical headings
- `<p>` - Paragraphs
- `<ul>` - Unordered lists (ingredients, navigation)
- `<ol>` - Ordered lists (recipe steps)
- `<figure>` and `<figcaption>` - Images with captions
- `<blockquote>` and `<cite>` - Quotations with attribution
- `<hr>` - Thematic breaks between sections

#### Form Elements
- `<form>` - Newsletter subscription
- `<fieldset>` and `<legend>` - Form grouping
- `<label>` and `<input>` - Form controls
- `<button>` - Submit button

#### Navigation
- `<a>` with `href="#id"` - Internal anchor links
- Jump links to recipes and subscription section

## 🎨 Content Highlights

### Recipe 1: Tony's "Panic Attack" Gabagool Special
- **Source**: *The Sopranos*
- **Dish**: Italian-American sandwich with capicola and provolone
- **Quote**: "Gabagool? Over here!" — Silvio Dante
- **Trivia**: References *The Office* mispronunciation scene

### Recipe 2: The Big Kahuna Burger
- **Source**: *Pulp Fiction*
- **Dish**: Hawaiian-style teriyaki burger with grilled pineapple
- **Quote**: "Mmm-hmm! This is a tasty burger!" — Jules Winnfield
- **Trivia**: Appears across multiple Tarantino films

### Recipe 3: Dorsia's Sea Urchin Ceviche
- **Source**: *American Psycho*
- **Dish**: Luxury appetizer with Hokkaido uni and gold leaf
- **Quote**: "I have to return some videotapes." — Patrick Bateman
- **Trivia**: Dorsia represents the ultimate unreachable status symbol

## 📋 HTML Best Practices Demonstrated

### 1. **Proper Document Structure**
```html
<!DOCTYPE html>
<html lang="en-US">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width,initial-scale=1.0,user-scalable=yes">
    <title>Cinematic Recipes</title>
    <meta name="description" content="Famous dishes from films and TV series">
  </head>
```

### 2. **Semantic Hierarchy**
- Logical heading structure (h1 → h2 → h3 → h4)
- Proper nesting of sections and articles
- Meaningful use of header/footer elements

### 3. **Accessibility Features**
- Descriptive `alt` text for all images
- Proper form labels with `for` attributes
- Required fields marked with `required` attribute
- Semantic navigation with `<nav>` element

### 4. **SEO Optimization**
- Descriptive meta description
- Proper heading hierarchy
- Semantic HTML5 elements
- Meaningful anchor text

### 5. **Image Accessibility**
Each image includes detailed alt text describing:
- Visual appearance
- Context
- Relevant details for screen readers

Example:
```html
<img src="..." alt="A rustic Italian sandwich piled high with cured capicola meat
and provolone cheese, sitting on a wooden cutting board next to a jar of red peppers.">
```

## 🎓 Learning Outcomes

This project demonstrates:

1. **Semantic HTML Mastery**: Proper use of HTML5 semantic elements
2. **Accessibility First**: Building accessible content from the ground up
3. **SEO Best Practices**: Optimizing for search engines with semantic markup
4. **Content Structure**: Organizing complex content hierarchically
5. **Form Design**: Creating accessible, semantic forms
6. **Progressive Enhancement**: Starting with solid HTML foundation

## 🚀 Usage

1. Open `index.html` in any modern web browser
2. Navigate using the menu links at the top
3. Scroll through the three recipes
4. Fill out the newsletter subscription form (non-functional)

## 🌟 Why Pure Semantic HTML?

This project proves that:
- **Accessibility doesn't require CSS**: Semantic HTML is inherently accessible
- **SEO loves structure**: Search engines prioritize well-structured content
- **Performance is built-in**: No CSS/JS means instant load times
- **Maintainability**: Clear, semantic markup is easy to understand and modify
- **Progressive enhancement**: Start with solid HTML, enhance with CSS/JS

## 📱 Browser Compatibility

Works in all modern browsers:
- Chrome/Edge
- Firefox
- Safari
- Opera

No polyfills or fallbacks needed - it's just HTML!

## 🎯 Use Cases

This approach is ideal for:
- Learning HTML fundamentals
- Building accessible prototypes
- Creating content for screen readers
- SEO-focused content pages
- Email templates (where CSS support varies)
- Documentation sites
- RSS feeds and content syndication

## 📝 Technical Details

### Meta Tags
- **Charset**: UTF-8 for universal character support
- **Viewport**: Responsive viewport configuration
- **Description**: SEO-optimized meta description
- **Favicon**: Custom PNG favicon

### Form Attributes
- `action="/subscribe"` - Form submission endpoint
- `required` - Client-side validation
- `type="email"` - Email input validation
- `placeholder` - Example input values

### Navigation
- Internal anchor links (`#recipe-1`, `#recipe-2`, etc.)
- Semantic `<nav>` element with descriptive heading
- Accessible link text

## 🎬 Pop Culture References

The project includes references to:
- **The Sopranos** (HBO)
- **Pulp Fiction** (Quentin Tarantino)
- **American Psycho** (Mary Harron)
- **The Office** (NBC)
- **Blade Runner** (Tyrell Corp in footer)

## 🏅 Achievements

- ✅ 100% Accessibility Score
- ✅ 100% SEO Score
- ✅ 100% Best Practices Score
- ✅ 99% Performance Score
- ✅ Zero CSS
- ✅ Zero JavaScript
- ✅ Fully semantic markup
- ✅ Screen reader friendly

## 📚 Resources

To learn more about semantic HTML:
- [MDN Web Docs - HTML Elements Reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)
- [W3C HTML5 Specification](https://www.w3.org/TR/html52/)
- [WebAIM - Semantic Structure](https://webaim.org/techniques/semanticstructure/)

---

**© 2025 Tyrell Corp. All Rights Reserved**
