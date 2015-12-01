walletname-chrome-extension
=================================================
<center>
**Resolve Blockchain / Bitcoin Wallet Names Automatically in Chrome**

![Wallet Name Resolver Tile](http://i.imgur.com/WZgER2U.png)
</center>

Netki’s *Wallet Name Resolver* works with web based wallets supporting bitcoin and numerous other blockchain based digital currencies and assets.  Now you can quickly and easily move money between wallets by using a **Wallet Name** instead of a complicated wallet address.

Why have:

1CpLXM15vjULK3ZPGUTDMUcGATGR9xGitv

When you can have an *easy to remember*, *easy to share* Wallet Name like:

**batman.tip.me**

You can get a **free** Wallet Name two ways:

1. Contact your wallet provider! We have had Netki Wallet Names installed simply by users asking for this feature. :)
2. Are you on Twitter? Then you already have a Wallet Name via our partner ChangeTip! Go to [www.tip.me](https://www.tip.me) and sign in with your Twitter handle to activate your wallet and automatically get a Wallet Name that you can readily share.

<a style="padding-left:150px;" href="http://www.twitter.com"><img src="http://i.imgur.com/yMAKB4v.png" width="8%"></a>
<a style="padding-left:100px;" href="http://www.changetip.com"><img src="http://i.imgur.com/7m0riSa.png"></a>

If you would like your own custom Wallet Name (TonyStark.bit) you can sign up for one at [www.netki.com](https://www.netki.com) for as low as $1.95.

<img src="http://i.imgur.com/soX3pYS.gif">

How-to: Setup / Development
--------------------
* Clone git repository
* Run ```npm install``` to install required Node modules
* Run ```grunt debug``` to build the debug version of the extension
* Open Chrome
* Go to ```chrome://extensions/```
* Select the **Developer mode** checkbox
* Click **Load unpacked extension...**
* Locate the **app/** directory of this Chrome extension, select it and click the **Select** button

Once installed, the extension's popup menu will look like this:

![Wallet Name Resolver Popup Menu](http://i.imgur.com/8KwhpWW.png)

Use the Production Release on Chrome
-------------------------------------
If you would just like to install the production release of the Chrome extension, please visit the Chrome Web Store [here](https://chrome.google.com/webstore/detail/netki-wallet-name-resolve/kjiedjbpjmhpjghalpicoodcpihblgdl).


FAQ
------------
**Q:** Why is this Chrome extension listed as beta?

**A:** The Chrome extension currently uses the Netki Public API to perform Wallet Name lookups, which requires DNS + DNSSEC. There is currently no DNSSEC library available in Javascript. We are working to create a DNSSEC library in order to have all lookups performed in a completely decentralized way, from within the browser.

-----

**Q:** Will this extension only lookup Wallet Names registered with Netki?

**A:** This extension will resolve **any** Wallet Name that adheres to the Wallet Name *standard*. The standard is published on the Netki Developers page: [https://www.netki.com/#/developers](https://www.netki.com/#/developers)

-----

**Q:** How can I contact Netki?

**A:** Please open an issue directly here in Github or feel free to email us at opensource@netki.com

-----

**Q:** How can I report an Issue with the Chrome extension and a specific website?

**A:** The easiest method is to use the *Report Site Lookup Issue* feature as shown in the screen shot. Feel free to contact us via the other means listed in the FAQ as well. 