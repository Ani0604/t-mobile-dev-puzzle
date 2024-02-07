# Code Review

## Few Problems Identified in review

- There is no trackBy in HTML for \*ngFor ib book-search.component.html
- There is no implementation for unsubscribing in the book-search.component.ts
- In the SCSS files the variables.scss is being imported in individual component scss file

## Improvement suggestion

- To reduce the budle size we can use gzip or AOT for compilation
- Lazy loading can be implemented which increases the page load performance

## Lighthouse

### Automated Scan Issues

- Enable text compression
- Minify JavaScript
- Largest Contentful Paint element
- Reduce unused JavaScript

### Manual Scan Issues

- Header has no accessibility specs
- The example search link has no accessibility specs
- Search box has not accessibility specs
