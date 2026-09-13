---
title: Chrome Windows Switcher
description: A fast, private window switcher for Google Chrome on Mac.
---

<style>
:root { color-scheme: light; }
body { background: #f5f5f7; }
.cws-hero { max-width: 920px; margin: 3rem auto 4rem; text-align: center; }
.cws-icon { width: 96px; height: 96px; border-radius: 22px; box-shadow: 0 10px 28px #0002; }
.cws-hero h1 { font-size: clamp(2.2rem, 6vw, 4.2rem); letter-spacing: -.04em; margin: 1.3rem 0 .8rem; }
.cws-hero p { color: #5f6368; font-size: 1.25rem; line-height: 1.5; margin: 0 auto 1.5rem; max-width: 650px; }
.cws-buttons { display: flex; gap: .75rem; justify-content: center; flex-wrap: wrap; }
.cws-button { display: inline-block; padding: .75rem 1.15rem; border-radius: 999px; background: #0a84ff; color: white !important; font-weight: 600; text-decoration: none; }
.cws-button.secondary { background: #e8e8ed; color: #1d1d1f !important; }
.cws-card { background: white; border-radius: 22px; padding: 1.5rem; margin: 1.5rem auto; box-shadow: 0 5px 24px #0000000d; }
.cws-card h2 { margin-top: 0; }
.cws-shots { display: grid; grid-template-columns: repeat(auto-fit, minmax(260px, 1fr)); gap: 1rem; }
.cws-shots img { width: 100%; border-radius: 12px; border: 1px solid #ddd; }
.cws-note { color: #5f6368; font-size: .95rem; }
</style>

<div class="cws-hero">
  <img class="cws-icon" src="{{ '/assets/app-icon.png' | relative_url }}" alt="Chrome Windows Switcher icon">
  <h1>Find your Chrome window.</h1>
  <p>A tiny, private Mac utility that puts every open Chrome window one keyboard shortcut away.</p>
  <div class="cws-buttons">
    <a class="cws-button" href="https://apps.apple.com/app/id6811397054">Download on the Mac App Store</a>
    <a class="cws-button secondary" href="https://github.com/viktorkelemen/chrome-windows-switcher-support/releases/latest">Direct download</a>
  </div>
  <p class="cws-note">Requires macOS 14 or later and Apple silicon. Google Chrome must be installed.</p>
</div>

<div class="cws-card">
  <h2>Switch in a beat</h2>
  <p>Press <strong>Control-Shift-Space</strong>, type part of a window title, and press Return. Search works across all your open Chrome windows, with keyboard navigation, recent-window ordering, and a shortcut you can customize.</p>
</div>

<div class="cws-card cws-shots">
  <img src="{{ '/assets/01-find-your-window.jpg' | relative_url }}" alt="Chrome Windows Switcher showing searchable Chrome windows">
  <img src="{{ '/assets/02-search-instantly.jpg' | relative_url }}" alt="Chrome Windows Switcher filtering windows by title">
</div>

<div class="cws-card">
  <h2>Private by design</h2>
  <p>Window titles and searches stay on your Mac. There is no account, analytics, advertising, or cloud service. The App Store version requests permission only to control Google Chrome.</p>
  <p><a href="{{ '/privacy/' | relative_url }}">Read the privacy policy</a> · <a href="https://github.com/viktorkelemen/chrome-windows-switcher-support/issues">Get support</a></p>
</div>
