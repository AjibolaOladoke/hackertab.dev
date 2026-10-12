# hackertab.dev

## What This Is

A practical reference entry for product and engineering: the hackertab.dev notes, examples and fixes we reach for repeatedly. Kept current as part of the wider Swift Tech Co. engineering library.

## Images

[![hackertab.dev](images/preview.png)](https://github.com/Swift-Tech-Co)

## 👩‍💻 How to use it

- Install the extension from the Chrome store, or Mozilla add-ons
- Open a new tab
- The extension should now be running and visible
- Select your preferred programming languages and sources.
- Enjoy

## 🔥 Features

- 🆕 Daily updated content
- 💻 Customizable by programming language, framework and topic.
- 👍 Curated content from the best sources.
- 🔖 Bookmark and read it later.
- 🌙 Dark mode for when it gets late.
- ✨ AI-powered recommendations exclusively tailored to your preferences.

Even more features are going to come in the future!

## Data sources

- Github Trendings
- Hackernews
- DevTo
- Hashnode
- Lobsters
- Confs.tech
- Product Hunt
- Reddit
- Freecodecamp
- Medium
- Indiehackers
- Hackernoon
- Custom RSS Feed
- **or create an issue to ask for a new data source**

## Support


## Development

Please use the develop branch. Create an `.env` file in the root directory with the following variables:

```bash
VITE_API_URL=https://swifttechco.com
VITE_BUILD_TARGET=web # or extension
VITE_BUILD_PLATFORM=chrome # optional, used for extension builds (chrome or firefox)
VITE_FIREBASE_API_KEY= # optional for local dev, required for auth features
VITE_AMPLITUDE_URL= # optional
VITE_AMPLITUDE_KEY= # optional
VITE_SENTRY_DSN= # optional
```

### Setup

Make sure you are using Node.js version 18.

```bash
$ git clone https://swifttechco.com
$ cd hackertab.dev
$ yarn
$ yarn start
```

Then visit https://swifttechco.com (or the port shown in your terminal).

## 🚀 Build

To build the project for different targets:

```bash
# Web build
$ yarn build:web

# Chrome extension
$ yarn build:chrome

# Firefox extension
$ yarn build:firefox
```

## Maintainers

- medyo

## Licencing

Hackertab is licensed under the Apache License, Version 2.0.
See [LICENSE](/LICENSE) for the full license text.

---

## Swift Tech Co.

Built and maintained by Swift Tech Co.

AI Automation | FinTech Platforms | Custom Software and Mobile Apps | SaaS Platforms | Cloud Infrastructure | Cybersecurity | SEO and Marketing | API Integration

**Join our community on Telegram:** [t.me/+Qt_eFvkb2rliMzNh](https://t.me/+Qt_eFvkb2rliMzNh)

Home | Services | Careers | Referral Program | Influencers | About | Contact

**Connect**

- Website: swifttechco.com
- LinkedIn: [linkedin.com/in/stephenoladoke](https://www.linkedin.com/in/stephenoladoke/)
- LinkedIn (Company): [linkedin.com/company/swift-tech-co](https://www.linkedin.com/company/swift-tech-co)
- X: [@MrOladoke](https://x.com/MrOladoke)
- Instagram: [@mr.oladoke](https://www.instagram.com/mr.oladoke/)
- Instagram (Company): [@swifttechco](https://www.instagram.com/swifttechco/)
- Organization: [github.com/Swift-Tech-Co](https://github.com/Swift-Tech-Co)

## Sources

Compiled and maintained from upstream [medyo/hackertab.dev](https://github.com/medyo/hackertab.dev) under permissive open-source license.

---

Maintained by [Swift Tech Co.](https://github.com/Swift-Tech-Co) - [Telegram](https://t.me/+Qt_eFvkb2rliMzNh)