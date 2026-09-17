# Meg Kendall — Personal Site

Personal portfolio site for [Meg Kendall](https://github.com/megkendall) — writer and analyst working at
the intersection of climate communications, public administration, and data. The site covers her
background (botany, orientation & mobility, public administration), her work at The Climate Hub,
selected clients, portfolio pieces, and ongoing coursework in data analysis and GIS.

**Live site:** [megkendall.com](https://www.megkendall.com/)

## Built AI-assisted

This site is also a portfolio piece in its own right: it was designed and built collaboratively with
Claude, from page structure and copy through to layout and responsive styling. It's included here as a
working example of AI-assisted front-end development — plain, dependency-free HTML/CSS, iterated on
through conversation rather than a design tool or framework.

## Stack

- Static HTML + CSS, no build step or framework
- Google Fonts (Cormorant Garamond, Poppins, Lora)
- A small inline script for the mobile nav toggle

## Structure

```
index.html      Page markup, organized into commented sections (hero, journey, portfolio, etc.)
style.css       Styles, organized to mirror the HTML sections, with a design-tokens block up top
uploads/        Images (photos, client logos, poem graphics)
```

## Running locally

No build tooling required — open `index.html` directly in a browser, or serve the directory:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.
