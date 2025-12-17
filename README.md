# Core Web Vitals – Cumulative Layout Shift (CLS) Notes

Cumulative Layout Shift (CLS) is a Core Web Vitals metric that measures visual
stability during page load. It tracks how often visible elements on a page move
unexpectedly while content is loading.

This repository contains simple notes and references to help understand CLS and
common causes of layout shifts on websites.

## What Is Cumulative Layout Shift (CLS)?
CLS measures how much the layout of a page shifts during its lifecycle. Layout
shifts often occur when images, ads, embeds, or fonts load without reserved space.

## Why CLS Matters
Unexpected layout movement can lead to poor user experience, misclicks, and
frustration. Improving CLS helps create more stable pages and smoother browsing
experiences across devices.

## Common Causes of Layout Shifts
- Images without defined width
- Ads or embeds injected after page load
- Late-loading web fonts
- Dynamic content added above existing elements

## Further Reading
- https://websitespeedy.com/blog/cumulative-layout-shift-cls-guide/

## Related Topics
- Core Web Vitals
- Page experience signals
- Web performance optimization
- User experience (UX)
