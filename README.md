# Adam Voice — AI Voiceover Studio

A free, public text-to-speech website. Paste a script, pick a voice, and download a natural AI voiceover as MP3 or WAV.

**Live site:** https://euriskoediting-web.github.io/

## How it works
- Voice generation runs **100% in the visitor's browser** using the open-source [Kokoro-82M](https://huggingface.co/onnx-community/Kokoro-82M-v1.0-ONNX) model via `kokoro-js` — so hosting costs $0 (GitHub Pages) and there is no server to pay for.
- The model (~90 MB, q8) downloads once on a visitor's first generation and is cached by their browser.

## Credits & pricing
- 1 credit = 1 character of voiceover.
- **$1 = 10,000 credits.** Bigger packs include bonus credits (Creator $5 = 55,000 · Pro $10 = 120,000 · Studio $25 = 325,000 · Empire $50 = 700,000).
- Guests get 300 trial credits; free accounts get 1,000 welcome credits.
- Accounts and credit balances are stored in the visitor's browser (localStorage) in this free edition.

## Owner: activating card checkout
In `index.html`, find `PAYMENT_LINKS` near the top of the script and paste the product/checkout link for each pack (e.g. from Gumroad or Lemon Squeezy). The Buy buttons then send customers straight to secure checkout. Until links are added, the Buy dialog tells visitors checkout is being activated and points them to the free credits.

## Voices
Adam (signature), Michael, Onyx, Eric, Liam, Daniel, George, Lewis, Heart, Bella, Emma — US & UK, male & female.
