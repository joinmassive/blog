# Reimagining the internet, without ads<br><sub>Our pitch to stop monetizing users’ personal attention and data

_By [Brian Kennish](https://github.com/oldestlivingboy)_

![The world’s idle processing power](power.png)

Using online apps and websites has turned into an **attention-grabbing**, **emotion-manipulating**,
**privacy-violating** experience that even the web’s creator regrets<sup><a
href="#references">1</a></sup> and the reason is a monolithic business model that incentivizes these
qualities.

What if, rather than being forced by internet advertisers to pay with your brainpower, you could
choose to pay with power of a sort that’s much less personally valuable and that almost everyone in
the world has access to<sup><a href="#references">2</a></sup>: your computer or mobile device’s
**idle processing power**<em>?</em>

Here’s how an alternative business model might work and what my team and I are building as a
possible foundation.

## My backstory

I’ve been an indie developer for most of the last decade and launched or helped launch **more than
30 desktop, mobile, and browser apps** in that time. The majority didn’t get much traction, but **7
of my apps** have gone on to hit **1 million active users**.<sup><a href="#references">3</a></sup>
Among them, **Disconnect** powers built-in privacy features for users of Mozilla Firefox<sup><a
href="#references">4</a></sup>, Samsung Internet<sup><a href="#references">5</a></sup>, and
Microsoft Edge<sup><a href="#references">6</a></sup> and **Adblock Fast** is (as far as I can tell)
the world’s third- or fourth-most popular ad blocker, with more than 10 million users<sup><a
href="#references">7</a></sup>.

I never figured out how to generate sustainable revenue from a lot of these apps, including the
hits, though.

I could’ve made Adblock Fast, for instance, a paid app or made a subset of Adblock Fast’s features
in-app purchases or subscription upgrades, but then **less than 1% of nonpaying users** would’ve
likely converted<sup><a href="#references">8</a></sup>. Alternatively, I could’ve defaulted to the
source of **62% of app revenue** by peddling ads<sup><a href="#references">9</a></sup> (some ad
blockers are ironically paid by advertisers to not block “acceptable ads”<sup><a
href="#references">10</a></sup>).

## Advertising on steroids, on crack

Advertising wasn’t that good for you to begin with.

![A hypothetical billboard](billboard.png)

From 1965 (the year after the Surgeon General linked cigarettes publicly to disease<sup><a
href="#references">11</a></sup>) through 2015, the tobacco industry ran **$254.1 billion of
ads**<sup><a href="#references">12</a>,&nbsp;<a href="#references">13</a></sup> and caused **20.8
million attributable deaths**<sup><a href="#references">14</a></sup> in just the United States.

Sugar, with similar promotional backing and adverse health effects, is fast becoming the next
tobacco. In the US, the sugar industry runs **about $2.4 billion of ads** annually for sweetened
cereal, snacks, and drinks<sup><a href="#references">15</a></sup> (compared with $9.1 billion run by
the tobacco industry<sup><a href="#references">12</a>,&nbsp;<a href="#references">13</a></sup>).
Obesity, meanwhile, is the leading preventable cause of death behind only tobacco use, at **365
thousand attributable deaths** per year (to tobacco use’s 435 thousand deaths).<sup><a
href="#references">16</a></sup>

### Getting personal (info)

Online advertising promised to “enhance” ad targeting and, in turn, performance. Current ad networks
track your web searches, browsing history, app usage, and physical location, along with the rest of
your internet behavior, to profile your interests in clinical detail then predict what ads you’ll
click.

The largest ad network by market share, Google<sup><a href="#references">17</a></sup>, is able to
collect **92% of web searches**<sup><a href="#references">18</a></sup>, **34% of browsing
history**<sup><a href="#references">19</a></sup>, **73% of app usage**<sup><a
href="#references">20</a></sup>, and **72% of geolocation requests**<sup><a
href="#references">21</a></sup>. Google transforms this data into **up to 34 demographic
categories** like whether or not you graduated from high school or have young children, **up to 154
affinity categories** like whether or not you eat fast food or watch reality shows, and **up to 779
purchase intents** like what clothes you’re shopping for or where you’re planning a trip to.<sup><a
href="#references">22</a></sup>

### Paying (with) attention

Social networking raised the stakes to “engage” users. Social apps and sites get you to pay
attention to ads in the first place by perpetuating psychological mechanisms of problem gambling and
other addictions, with infinite scrolling and autoplaying media that trigger your fear of missing
out, like and follower counts that inflate and deflate your self-esteem, and in-product and push
notifications that ply you with intermittent reinforcement.

Facebook, which a fourth of the world’s population uses daily<sup><a
href="#references">23</a>,&nbsp;<a href="#references">24</a></sup>, subjects users to continuous
psychological experiments in service of a **28% higher engagement rate** year over year since
2017<sup><a href="#references">25–28</a></sup>. One of the few of these experiments Facebook data
scientists have published reveals that the platform modifies the sentiment of user news feeds and
that increasing the proportion of positive or, especially, of negative posts results in more engaged
(and emotional) users, measured by number (and type) of words posted.<sup><a
href="#references">29</a></sup>

Despite all that ad and social networks poke and prod you, internet advertising isn’t very
profitable except for the biggest businesses. The average app developer makes just **$0.05 per user
per month** from ads.<sup><a href="#references">30</a></sup>

## A new way to make money and pay online

Instead of loading my under-monetized apps with ads, I decided to try to come up with new business
models for them. Many bad ideas later, I offered Adblock Fast users an often requested feature,
blocking video ads, in exchange for monetizing their leftover processing power:

![An upgrade offer in Adblock Fast](adblockfast.png)

**39% of nonpaying users** opted in to upgrade.

After more of my upgrade offers were as well-received, we founded a company to develop my then-toy
implementation into a real product that every developer could include in their apps. That company
is **Massive** and the product is the **Massive SDK**.

The Massive SDK is a cross-platform app framework, currently available for **Windows 7 and up** and
**macOS 10.10 and up**, that gives users the option to pay for features, content, and services with
a tiny amount of their processing power, storage, and bandwidth.

### Airbnb for your computer

You can think of Massive as Airbnb or Turo for your computer or mobile device.

Your home and, more so, your vehicle and, most of all, your computer or mobile device are
depreciating assets. They’re worth something today and, accounting for maintenance, something less
tomorrow.

However, Airbnb and Turo let you recapture part of your expenses or, perhaps, profit by sharing your
home and vehicle when you’re not using them.

Massive does the same for your computer or mobile device, letting you unlock premium apps and
features with any unused computing resources you have.

Our SDK combines these resources to form a supercomputer that compensates developers by **mining
cryptocurrency**, **running scientific simulations**, **pinging network objects**, and **performing
general distributed tasks** (i.e., we provide “mining [and more] as a service”, which is what our
company name derives from, and we should be carbon neutral doing so by the end of the year). Early
SDK partners are earning **$0.10 to $0.20 per user per month** and we’ve been consistently
optimizing up and to the right:

![Monthly revenue per user on Massive’s partner dashboard](rpu.png)

To make sure users get a fair deal too, we’ve designed Massive based on three principles.

### Opt-in

First, Massive is opt-in only. Users must agree to clear terms of the exchange they’re entering into
then be given tooling to monitor and control the SDK’s resource consumption.

### Imperceptibility

Second, Massive is imperceptible when active. The SDK is trained on anonymous telemetry data to
consume minimal resources in the background and avoid contending with foreground processes.

### Privacy and security

Third, Massive is privacy and security preserving. The SDK doesn’t collect any personally
identifiable info, operates in a sandboxed environment for additional data safety, and is
whitelisted by antivirus engines (as shown by **VirusTotal**):

![VirusTotal results for the Massive SDK](virustotal.png)

We’re compliant, of course, with relevant regulatory regimes worldwide, the **GDPR** (General Data
Protection Regulation) in the EU, the **CCPA** (California Consumer Privacy Act) in the US, the
**LGPD** (Lei Geral de Proteção de Dados) in Brazil, and the **IT Act** (specifically, sections 43A
and 72A) in India.

## Everything old is new again

Yes, you’ve heard this idea somewhere before.

### Distributed computing

**SETI@home** was<sup><a href="#references">31</a></sup> one of the first projects to scale
distributed computing over the internet. Citizen scientists would download data from radio
telescopes to their computers then analyze the data in the “search for extraterrestrial
intelligence” (SETI). Over **almost 20 years of operation**, the project acquired **more than 4
million desktop users**, who identified **more than 7 billion unusual signals** for further
analysis.<sup><a href="#references">32</a></sup>

The project’s core software was also abstracted out as **BOINC** (Berkeley Open Infrastructure for
Network Computing; developers seldom miss an opportunity to coin a TLA<sup><a
href="#references">33</a></sup>) and has spawned **more than 50 related projects**<sup><a
href="#references">34</a></sup>. An example is **Folding@home**, which simulates protein synthesis
to discover “misfoldings” that lead to diseases like cancer, diabetes, and Alzheimer’s and which
Massive donates a portion of processing power to:

![Massive’s Folding@home team](foldingathome.png)

### Two-sided marketplaces

Initial attempts to commercialize distributed computing were less successful.

**Entropia**, **Porivo**, and **Popular Power** were<sup><a href="#references">35–37</a></sup>
computing marketplaces that tried to connect buyers who had arbitrary workloads and sellers who had
spare capacity.

Each marketplace had the chicken-and-egg problem inherent in two-sided markets. Buyers can’t buy
before there are sellers and sellers can’t sell before there are buyers, unless the market
subsidizes the missing supply or demand.

The emergence of mineable cryptocurrency has given Massive a means to synthesize demand when needed
and bootstrap to **more than 100 thousand opted-in users** and their supply of computers (if
compared as a blockchain project, Massive may already have the most computing nodes of any such
project<sup><a href="#references">38</a></sup>).

### Embedded cryptomining

**Coinhive** was<sup><a href="#references">39</a></sup> a mysterious company<sup><a
href="#references">40</a></sup> that solved the chicken-and-egg problem with a clever and likewise
cryptocurrency-adjacent product, a miner miniaturized to execute in-browser (the miniaturization
was accomplished by porting the ASIC-resistant CryptoNote hashing algorithm to the native-speed
WebAssembly binary format). Publishers could install the miner on their sites as an ad or paywall
replacement and **up to 40 thousand publishers** did<sup><a href="#references">41</a></sup>.

The company created a worse problem by failing to require user permission or limit CPU and energy
consumption, though, and most Coinhive-enabled sites ended up being illegitimate or compromised
(Salon was a rare exception<sup><a href="#references">42</a></sup>). These sites were effectively
engaged in drive-by mining, which fueled a new malware classification called “cryptojacking”.

To prevent this problem, Massive enforces prominent user opt-in and usage controls and reasonable
consumption limits, both technically and legally:

![User tooling in Massive](tooling.png)

## Join us

We shipped Windows and macOS versions of Massive initially and have since prototyped SDKs for mobile
and the web. If you’re a desktop developer, you can [start adding Massive to your
apps](https://joinmassive.com/partners) now.

If you’re not but are a mobile or web developer or are interested in topics like **alternative
business models**, **distributed computing**, or **re-decentralizing the internet**, you can
[subscribe to our newsletter](https://joinmassive.com/#newsletter). We’ll announce platform launches
and continue to write about these topics there.

_This post was originally published at
[blog.joinmassive.com](https://blog.joinmassive.com/reimagining-the-internet-without-ads-875395fbcde5)._

----------------------------------------------------------------------------------------------------

### References

1.  [The man who created the World Wide Web has some regrets](https://www.vanityfair.com/news/2018/07/the-man-who-created-the-world-wide-web-has-some-regrets),
    Vanity Fair
2.  [The mobile economy 2020](https://www.gsma.com/mobileeconomy/wp-content/uploads/2020/03/GSMA_MobileEconomy2020_Global.pdf),
    The Global System for Mobile Communications Association
3.  [Bio](https://oldestlivingboy.com/bio), Brian Kennish
4.  [Today’s Firefox blocks third-party tracking cookies and cryptomining by default](https://blog.mozilla.org/blog/2019/09/03/todays-firefox-blocks-third-party-tracking-cookies-and-cryptomining-by-default/),
    The Mozilla Blog
5.  [Introducing our new Tracking Blocker](https://medium.com/samsung-internet-dev/introducing-our-new-tracking-blocker-powered-by-disconnect-c00f118c1151),
    Samsung Internet Developers
6.  [Improving tracking prevention in Microsoft Edge](https://blogs.windows.com/msedgedev/2019/12/03/improving-tracking-prevention-microsoft-edge-79/),
    Microsoft Edge Blog
7.  [About](https://adblockfast.com/#about), Adblock Fast
8.  [The truth about conversion ratios for downloadable software](https://successfulsoftware.net/2009/04/23/the-truth-about-conversion-ratios-for-software/),
    Successful Software
9.  [The kinds of mobile app monetization](https://www.appannie.com/en/academy/monetize/kinds-mobile-app-monetization),
    App Annie
10. [Ad blockers are making money off ads (and tracking, too)](https://www.wired.com/2016/03/heres-how-that-adblocker-youre-using-makes-money/),
    Wired
11. [History of the Surgeon General’s reports on smoking and health](https://www.cdc.gov/tobacco/data_statistics/sgr/history/index.htm),
    The Centers for Disease Control and Prevention
12. [FTC cigarette report for 2018](https://www.ftc.gov/system/files/documents/reports/federal-trade-commission-cigarette-report-2018-smokeless-tobacco-report-2018/p114508cigarettereport2018.pdf),
    The Federal Trade Commission
13. [FTC smokeless tobacco report for 2018](https://www.ftc.gov/system/files/documents/reports/federal-trade-commission-cigarette-report-2018-smokeless-tobacco-report-2018/p114508smokelesstobaccoreport2018.pdf),
    The Federal Trade Commission
14. [The health consequences of smoking](https://www.ncbi.nlm.nih.gov/books/NBK179276/pdf/Bookshelf_NBK179276.pdf),
    The National Center for Biotechnology Information
15. [Food advertising in the United States](https://www.ers.usda.gov/webdocs/publications/42215/5838_aib750i_1_.pdf),
    The Economic Research Service
16. [Actual causes of death in the United States, 2000](https://pubmed.ncbi.nlm.nih.gov/15010446/),
    The National Center for Biotechnology Information
17. [Global digital ad spending 2019](https://www.emarketer.com/content/global-digital-ad-spending-2019),
    eMarketer
18. [Search engine market share worldwide](https://gs.statcounter.com/search-engine-market-share),
    Statcounter
19. [DoubleClick usage statistics](https://trends.builtwith.com/ads/DoubleClick.Net), BuiltWith
20. [Mobile operating system market share worldwide](https://gs.statcounter.com/os-market-share/mobile/worldwide),
    Statcounter
21. <a
    href="https://web.archive.org/web/20210304064540/https://vertoanalytics.com/chart-of-the-week-what-are-the-most-popular-mapping-apps/">What
    are the most popular mapping apps<em>?</em></a>, Verto Analytics (archived)
22. [About audience targeting](https://support.google.com/google-ads/answer/2497941), Google Ads
    Help
23. [Facebook 2020 10-K](https://www.sec.gov/Archives/edgar/data/1326801/000132680121000014/fb-20201231.htm),
    The Securities and Exchange Commission
24. [World population prospects 2019: Highlights](https://population.un.org/wpp/Publications/Files/WPP2019_Highlights.pdf),
    The United Nations
25. [Facebook publishing: Q1 2020](https://newswhip.com/wp-content/uploads/2020/04/Facebook-Publishing-Q1-2020.pdf),
    NewsWhip
26. [Facebook publishing: Q2 2020](https://newswhip.com/wp-content/uploads/2020/07/Facebook-Publishing-Q2-2020-Final.pdf),
    NewsWhip
27. [Facebook publishing: Q3 2020](https://newswhip.com/wp-content/uploads/2020/10/Facebook-Publishing-Q3-2020.pdf),
    NewsWhip
28. [Facebook publishing: Q4 2020](https://newswhip.com/wp-content/uploads/2021/01/Facebook-Publishing-Q4-2020-final.pdf),
    NewsWhip
29. [Experimental evidence of massive-scale emotional contagion through social networks](https://www.pnas.org/content/111/24/8788),
    The Proceedings of the National Academy of Sciences
30. <a
    href="https://www.developereconomics.com/blog/how-much-is-an-active-user-worth">How much is an
    active user worth<em>?</em></a>, SlashData
31. [SETI@home hibernation](https://setiathome.berkeley.edu/forum_thread.php?id=85267), SETI@home
32. [A brief history of SETI@home](https://www.theatlantic.com/science/archive/2017/05/aliens-on-your-packard-bell/527445/),
    The Atlantic
33. [TLA](http://catb.org/jargon/html/T/TLA.html), The Jargon File (non-secure)
34. [Project list](https://boinc.berkeley.edu/wiki/Project_list), Berkeley Open Infrastructure for
    Network Computing
35. [Entropia](http://www.scottkurowski.com/entropia/), Scott Kurowski (non-secure)
36. [Another RTP firm bites the dust](https://www.wraltechwire.com/2002/10/29/another-rtp-firm-bites-the-dust-porivo-technologies-is-sold/),
    WRAL TechWire
37. [Popular Power turns off the lights](https://web.archive.org/web/20161120085932/https://www.openp2p.com/pub/a/p2p/2001/03/19/poppower.html),
    O’Reilly Open P2P (archived)
38. [Cryptos ranked by number of nodes](https://medium.com/coinmonks/cryptos-ranked-by-number-of-nodes-d3ee0b7cad03),
    Coinmonks
39. [Discontinuation of Coinhive](https://web.archive.org/web/20190428191407/https://coinhive.com/blog/en/discontinuation-of-coinhive),
    Coinhive (archived)
40. <a href="https://krebsonsecurity.com/2018/03/who-and-what-is-coinhive/">Who and what is
    Coinhive<em>?</em></a>, Krebs on Security
41. [How to find cryptojacking malware](https://badpackets.net/how-to-find-cryptojacking-malware/),
    Bad Packets
42. <a
    href="https://web.archive.org/web/20200604052723/https://www.salon.com/about/faq-what-happens-when-i-choose-to-suppress-ads-on-salon">What
    happens when I choose to “Suppress Ads” on Salon<em>?</em></a>, Salon (archived)
