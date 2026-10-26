# Her Dream — her dream ltd

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `herdreamltd.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/herdreamltd.mjs`).
> To change the content, edit that file and run `node build.mjs herdreamltd` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@herdreamltd.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($Agreed / $Agreed / $Never) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
Her Dream Ltd is a London music company working in sound recording and music publishing since 2015. We record and produce, publish songs and register them properly so royalties actually reach the writer, handle release and distribution, and work with artists on developing a catalogue rather than chasing one release. The thing we explain before anything is signed is that a recording carries two separate copyrights: the song itself and the recording of it. They are owned separately, licensed separately and collected by different societies, and an artist registered with one but not the other is losing money without knowing it. We also never charge an artist a fee to find them work, because the law restricts that and because a company that profits from signing people has no reason to be honest about their prospects. No release is promised an outcome. Site: herdreamltd.shop
```

## Structure

```
index.html            Home: hero, programs, method, pricing, approach, FAQ
programs.html         The four programs in detail
about.html            How we work, principles
contact.html          Contact form
legal.html            Business info, privacy policy, terms of service
404.html              Error page (absolute paths)
assets/css/style.css  Brand colors at the top, shared styles below
assets/js/main.js     Menu, theme, animations, form
```

## DNS (Namecheap → Advanced DNS)

Delete the parking records, then add:

| Type | Host | Value |
|---|---|---|
| A Record | `@` | `185.199.108.153` |
| A Record | `@` | `185.199.109.153` |
| A Record | `@` | `185.199.110.153` |
| A Record | `@` | `185.199.111.153` |
| CNAME Record | `www` | `hamzaniceguy99-glitch.github.io.` |
