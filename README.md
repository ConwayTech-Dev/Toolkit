
# Toolkit

Welcome to a curated list of my favorite pieces of software for macOS and Windows! I've been exploring interesting software for years, and I've finally gotten to a stage where almost every aspect of my macOS and Windows experience is decently optimized. This list will include exhaustive information about software, including alternatives to my solutions, amazing features in certain pieces of software, and how to make my solutions even better with the power of customization.

This symbol (<img src="/opensource.png" height="17">) represents free, open-source software. Not everything on this list is FOSS, but everything is free and widely available for download.

# Tweaks

- Disable all crypto features on Brave
- Raycast plugins
- VSCode plugins and hsortcut
- Block spotify ads (software section)?

# Browsers

### My primary browser recommendation: Zen Browser <img src="/opensource.png" height="17">

### My primary browser alternative recommendation: Microsoft Edge

### My secondary browser recommendations: Microsoft Edge or Zen Browser

Most of the time I spend on a computer involves browsing the web. As such, finding an excellent web browser is an important task, but it's also an extremely difficult one, especially given the wide variety of options.

A secondary browser is a browser that you can always depend on. It's not the browser that you'd use to browse the web normally, but if your primary browser isn't working, you gravitate towards your secondary browser. A browser might be an excellent primary browser, but might not be a good secondary browser.

I need to talk about Brave. Choosing Brave has always seemed extremely unnecessary. It's literally a worse version of Chrome, designed for people who are overly neurotic about privacy. On first launch, it's an unusable browser, thanks to the crypto features. Then, once you disable all of the crypto garbage, it upgrades from being unusable to being pretty bad. The "privacy" features that the Brave team has implemented are great for privacy, but they break numerous websites and make life difficult for web developers. The adblocking features, on the other hand, are effective, but they don't incentivize me whatsoever to choose Brave over other browsers. In other browsers, uBlock Origin can replicate the functionality, and I don't even use Brave's adblocking features. Since I install uBlock Origin in Brave as well, I usually disable the Brave adblocking features so that they don't combat the uBO ones; uBlock Origin has always worked well (better than Brave's built-in ones) for privacy and for adblocking, and in my eyes, there's no need for the extra privacy given by Brave. It's also important to note that Brave doesn't even have that much better performance than Chrome, and in my experience, Chrome's Memory Saver feature has been far superior to Brave's alternative. This is especially important for people who regularly have hundreds of tabs open. Simply put, the only reason anyone would choose Brave over Chrome is if they're overly neurotic about security. Aside from the adblocking, privacy, crypto, and AI features, Brave also has some other unique features that Chrome doesn't have (like vertical tabs), but there are better alternatives, so I don't think these are good incentives to use Brave (more on this later). The last nail in the coffin is that I find Brave rather unpleasant to look at. These are two excellent articles that talk about why Brave's crypto breaches the company's whole privacy mission and how Brave - the company - is going in the completely wrong direction: [(A)](https://www.xda-developers.com/brave-most-overrated-browser-dont-recommend/) [(B)](https://www.spacebar.news/stop-using-brave-browser/).

Zen Browser is my primary browser recommendation, but because it's Firefox-based, I can see why people might gravitate towards other solutions. Zen is FOSS, and it fills more boxes than any other browser out there. Zen is an Arc-inspired, Firefox-based browser, and apart from the fact that it uses Gecko, it's great. Even though I don't use a lot of Zen's coolest features, I have had no problems whatsoever with the ones that I use - Glance has come in handy, especially for links I'm clicking in Gmail, and I love the Arc-inspired design of Zen. Zen is highly customizable - the Discord and Reddit communities have created thousands of interesting themes that anyone can install, and there's also a community-made collection of plugins and themes called Zen Mods that anyone can install into their browser. And because this is Firefox, it's also incredibly easy to use about:config to personalize the browser. There are two understandable concerns when it comes to Zen. The first concern is that the vast majority of the development on the browser is done by one person - an extremely talented developer named Mauro Baladés. The work he does on Zen is amazing, but there are concerns about what would happen to the browser if Mauro took a hiatus or went on vacation, for example. There are other contributors to the project, though, and Mauro, who's extremely dedicated, seems to be doing an excellent job, so this hasn't been an issue. The second issue is that Zen uses Gecko. This poses two problems: general UX and DevTools. Firefox is notorious for having a poor UX; many, many gradient issues occur with Gecko, and a lot of websites just don't work. If you're an avid YouTube watcher, you may want to stay away from Zen. Furthermore, Gecko DevTools are horrible, which is a huge disadvantage for software developers. Thus, alongside Zen, I have a secondary browser that I can use if a) a page isn't working correctly or b) I need better DevTools or Chrome extension support. Edge is my recommendation for a secondary Windows browser, and Chrome is my recommendation for a secondary macOS browser. (Chrome also works as a secondary browser for Windows.)

Mozilla Firefox is okay, aside from all the Gecko problems. But if you're okay with Gecko, why not choose Zen instead? It's objectively better.

Microsoft Edge used to be terrible, but it's my recommendation for a Windows secondary browser. It has all of the benefits of Chrome while also being a) the most optimized, fastest Windows browser and b) installed on Windows 11 by default. You could use Chrome as a secondary browser on Windows, but why bother? Edge works so well as a secondary browser. After you disable all of the Microsoft Shopping and AI features, Edge works well for a browser that you open on occasion. It has some cool stuff, like the sidebar and vertical tabs, and though I'd likely never use it as my primary browser because I prefer Zen, you could probably use it as one.

Google Chrome is just solid. You can always depend on Chrome and the Chromium team, and the DevTools are great. It integrates with the mobile apps well, it integrates with your Google Account, and Chrome just works. I wouldn't recommend Chrome as a primary browser, due to the lack of vertical tabs and a few other essential features, but it's an extremely dependable secondary browser. I get that a lot of people want to use Chrome as their primary browser, though. So if you're okay with normal tabs and plan to use Chrome as your primary browser, make sure to set these flags to "Enabled" for a better experience: #enable-parallel-downloading & #scrollable-tabstrip.

Arc was a great browser for macOS. As for Windows, well, not so much. Either way, it's not a suitable choice in the status quo because The Browser Company has completely stopped development on Arc in favor of their AI-garbage browser, Dia. The vision for Arc is still great, and it inspires Zen, but I see no world where Arc is an acceptable browser, especially given the macOS battery issues.



# Browser Extensions

### My recommendations for Chromium-based browsers:

### My recommendations for Firefox-based browsers:

Using the right extensions is really important for a good browsing experience, and my recommendations in the Browsers section assume that you're using certain extensions - otherwise, the list would likely be different.

For Chromium-based browsers, understanding that Manifest v2 is being deprecated is extremely important. The Chromium team has rolled out the decision to prevent Manifest v2 extensions from being utilized, meaning that many of our favorite extensions (most notably, uBlock Origin) no longer work on Chrome. Some Chromium forks, like Edge and Brave, plan to roll out this change "on a future date," whatever that means.

- Raycast - Incredible Spotlight alternative
- IINA - Fluent media player for macOS <img src="/opensource.png" height="17">
- Latest - Modern macOS app updater <img src="/opensource.png" height="17">
- Keka - macOS file archiver and archive extractor <img src="/opensource.png" height="17">
- OCAuxilaryTools - Intuitive Hackintosh config editor <img src="/opensource.png" height="17">
- Proton VPN - Free VPN with limited locations
- Warp - AI-powered Rust terminal with autocomplete (Alternative: Hyper or iTerm)
- Figma - Popular graphic design tool
- Cursor - AI-powered code editor
- Visual Studio Code - Excellent code editor by Microsoft <img src="/opensource.png" height="17"> (Alternative: Zed)
- Ice - Menu bar management tool <img src="/opensource.png" height="17"> (Alternative: Vanilla)
- Microsoft Edge - Chromium-based browser with a variety of surprisingly good features (Alternative: Arc, Brave, Zen, or Chrome)
- Discord - Chat app
- Vencord - Software that modifies Discord to improve experience <img src="/opensource.png" height="17">
- Spotify - Music software
- Stats - Menu bar hardware monitor <img src="/opensource.png" height="17">
- Bluesnooze - Disable Bluetooth when macOS is asleep <img src="/opensource.png" height="17">
- Dropzone - asdfasdlkfjalksdjf;laksjdf
- Zoom Workplace - Chatting and video calling software
- Onyx - macOS maintenance utility
- TinkerTool - macOS modification utility <img src="/opensource.png" height="17">
- Parsec - Low-latency remote desktop software
- AppCleaner - App uninstaller
- OBS Studio - Recording and streaming software
- Calibre - Ebook metadata management software and editor
- Maccy - Efficient clipboard manager for macOS <img src="/opensource.png" height="17">
- BetterDisplay - macOS display manager
- Rectangle - macOS window management <img src="/opensource.png" height="17">
- AltTab - macOS alt-tab software <img src="/opensource.png" height="17">
- MiddleClick - add three-finger click gesture to macOS trackpad <img src="/opensource.png" height="17">
