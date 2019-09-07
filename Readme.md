# Slack contrast

https://aopal.github.io/slack-contrast/contrast.html

Web tool to help determine the best text colours for slack emoji for readability in both light and dark theme.

## Usage

TLDR: get those contrast numbers above 4.5 at minimum, or 7 if possible

The tool has two boxes, one in each of the default dark and light mode colours, with sample text. Text colour (and background colours, if deisred) can be chosen via a colour picker at top.

The tool helps one decide the proper colours on either theme via the Web Content Accessibility Guidelines (WCAG) 2.0 contrast guidelines [(see here for a more complete explanation)](https://medium.muz.li/the-science-of-color-contrast-an-expert-designers-guide-33e84c41d156?gi=bf148f5c59c3). Per the guidelines, colour contrast  between regular text and its background (which the tool calculates for you) should be at least 4.5 at minimum, and preferably higher than 7. For reference, the maximum contrast is 21 (white on black), and the minimum is 1, a colour on itself.