# xiaolongbytes.github.io
[Link to Figma file](https://www.figma.com/file/zfkwEcGIBBs7vR97tzkndb/April's-Personal-Website?type=design&node-id=0%3A1&mode=design&t=CfYblM5eLAY2hOoo-1)

Website URL: https://xiaolongbytes.github.io/

Personal/portfolio website for myself.

## Skills Learned
1. UI Design
2. Figma to prototype website design and content
3. Making website behave correctly on different window sizes/mobile

## Tools Used
- [Realtime Colors](https://realtimecolors.com/?colors=040201-FBEEEA-853619-f2c9ba-bc4d24) to choose color palette and to check contrast for readability and color accessibility
- [unDraw Illustrations](https://undraw.co/illustrations) for illustrations that match my color palette
- [Google Fonts](https://fonts.google.com/specimen/Monoton?query=monoton) to find fonts such as Monoton and Railway used in my design
- [Font Awesome v4.7](https://fontawesome.com/v4/icons/) for icons
- [Normalize.css](https://necolas.github.io/normalize.css/) to normalize website behavior on all browsers.

## Lessons Learned
- Buttons are for in-page actions, anchors are for navigation. Anchors can be styled to look/act like buttons.
- CSS:  ``` * {
    box-sizing: border-box;
}```
Always. Makes CSS and box model easier.
- Friends will laugh at you if you don't have a gitignore and commit node modules

## TO-DO
- [ ] Finalize prototype design in Figma
- [ ] Set up gitignore 
- [ ] Create page using HTML and CSS
    - [X] Implement normalize.css
    - [X] Research ul vs nav element (a11y)
        - Wrap my ul with nav
        - https://stackoverflow.com/a/69513936
    - [ ] webp vs jpeg
    - [X] Figure out how to add icon to button
    - [X] ~~Figure out alignment of text in Home section (not aligned with right edge of resume button, is that ok?)~~ It's fine
    - [ ] ~~Make nav bar functional with links~~
        - Anchor tags scrolled page such that nav bar obscured content.
        - Behavior for sections at the bottom of the page was also poor (would not scroll so section was at top of screen)
        - Page is so short that nav bar had minimal benefit.
        - Removed for MVP.
    - [ ] ~~Flex grow/shrink on navbar rather than set width~~
    - [ ] Add degree progress/courses?
- [ ] Custom URL/github url
- [X] Ensure it looks good on different window sizes
    - [X] How to keep left and right margins when window is less than max body width?
- [X] Make mobile friendly
    - ~~[ ] Change nav bar into hamburger menu on small screens~~
    - shrink text?
    - ensure images and buttons are displayed correctly
- [ ] Add click tracking

