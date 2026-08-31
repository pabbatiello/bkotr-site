# bkotr.com

The website for **Blue Kid On The Rock** — dream-pop & electronica, Benevento, Italy.
*the way the ocean waves*

A single static page. No framework, no build step, no dependencies.

## Files

| | |
|---|---|
| `index.html` | The whole site. Markup, styles and the canvas animation are inlined. |
| `hero.jpg` | Social share preview only (`og:image`). Not used in the page design. |

## The background

The warm field is a CSS gradient reading as sky above the horizon and ocean below it.
Over it, a `<canvas>` draws ten undulating lines that work as both an ocean horizon and
an audio waveform, plus a sun that sits behind the wordmark and sets as the page scrolls.
It respects `prefers-reduced-motion` and pauses when the tab is hidden.

## Sign-up form

Posts to [Web3Forms](https://web3forms.com), which emails each submission onward.
No database, no backend. Set `ACCESS_KEY` in the script at the bottom of `index.html`.

## Local preview

```
python3 -m http.server 4173
```
