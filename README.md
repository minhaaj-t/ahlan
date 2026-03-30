# ahlan

Simple static redirect for **Ahlan Rawabi**:

- **Android** → [Google Play](https://play.google.com/store/apps/details?id=com.nipuna.loyalty&hl=en)
- **iPhone / iPad / iPod** → [App Store](https://apps.apple.com/qa/app/ahlan-rawabi/id6449727046)
- **Other** → [Ahlan Rewards (web)](https://rawabihypermarket.com/ahlan_reward)

Routes: `/` and `/app` both run the same client-side redirect (with a meta refresh fallback to the web URL when JavaScript is off).

Deploy on [Vercel](https://vercel.com/new): import this repo, set **Framework Preset** to **Other** (static HTML, no build command or output directory).
