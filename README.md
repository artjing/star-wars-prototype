# Star Wars Prototype

A standalone, bilingual, clickable NaturalHealing interface prototype.
The project title is **Star Wars Prototype**. The product branding remains **NaturalHealing / 太一脉**.

## Local demo

1. Open `index.html` in Chrome, Safari, or Edge. Double-clicking the file in Finder is sufficient.
2. English is the default language. Use **中文 / English** to switch.
3. Use **Try prototype**, **All screens**, or **Flow map** to explore all 26 screens.
4. Follow **Start measurement → Connect → Fit guide → Left → Switch → Right**. The simulated report-generation step automatically opens the full report.

No npm installation, backend, account, or API key is required. Images and prototype runtime are included in the HTML file. Device readings and Coach replies are simulated. Fit illustrations still need to be checked against the device manual. The supplied report screenshot retains its source language.

To give someone else a local demo, send the ZIP archive. They can extract it and open `index.html` on their own computer. A local file address is not an Internet link.

## Optional localhost preview

Run this command from this folder:

```sh
python3 -m http.server 8080 --bind 127.0.0.1
```

Then open http://127.0.0.1:8080/ in your browser. Keep the terminal running while using this preview. Press Control-C to stop it. This address only works on the same computer.

## Optional GitHub Pages publication

This folder is ready for static hosting. Upload its contents to a repository named `star-wars-prototype`, with `index.html` at the repository root.

In the repository, choose **Settings → Pages → Deploy from a branch → main → / (root) → Save**.

The expected project URL format is:

```text
https://YOUR-GITHUB-USERNAME.github.io/star-wars-prototype/
```

Project URL: https://artjing.github.io/star-wars-prototype/

Repository: https://github.com/artjing/star-wars-prototype

The same files can be opened locally or hosted with GitHub Pages.

Official documentation: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

## Scope

This is an interface demonstration, not a working medical device application. It does not connect to hardware, submit health data, or call a live AI service. Published as a standalone demo under the Star Wars Prototype project name. Production device services and a live AI backend are not included.
