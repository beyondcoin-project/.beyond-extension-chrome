# ![BEYOND-DNS:](https://cdn.beyondcoin.io/images/common/dot-beyond.png) Beyondcoin-DNS

BEYOND-DNS addon for Chrome lets you surf **.beyond**, and OpenNIC domains, and other OpenNIC peered domains.

-------

**Attention: Chrome requires `http://` prefix or a pathname**

If you type an address like `bynd.beyond` into the address bar and hit Enter - you will be taken to Google search page. You have to type `http://bynd.beyond` or add a slash at the end: `bynd.beyond/`. See [this issue for details](https://github.com/B-DNS/Chrome/issues/2).

-------

![Chrome screenshot](https://cdn.beyondcoin.io/images/extensions/chrome/ss0.png)

-------

BEYOND-DNS is a public web resolver. Read more at https://beyondname.com (API description is [here](https://docs.byndnic.com)).

For the list of OpenNIC supported domain names see the [full list](https://wiki.opennic.org/opennic/dot).

--------

## Installing Production Version

Download from the Chrome Web Store: [.beyond DNS](https://chrome.google.com/webstore/detail/beyond-dns/nknojokgefebgoblhligboomkonjaidm)

--------

## Installing Debug Version

You can permanently load a debug (unsigned) extension into Chrome, i.e. it will survive restart.

**Disable existing BEYOND-DNS extension, if installed, before installing its debug version!**

1. Open Extensions tab: click on the button with 3 dots, open _More tools_ submenu, then click on _Extensions_ item.
![Step 1](https://cdn.beyondcoin.io/images/extensions/chrome/ss1.png)
2. In the tab that has just opened, tick the checkbox named _Developer mode_, then click on _Load unpacked extension_ button that should have appeared.
![Step 2](https://cdn.beyondcoin.io/images/extensions/chrome/ss2.png)
3. Select the extension's directory. The directory should contain all files from the [Chrome GitHub repository](https://github.com/beyondcoin-project/.beyond-extension-chrome) and all PNG images.
4. Once the open dialog is submitted, a new extension should appear in the Extensions tab. Click on _background page_ link (next to _Inspect views_) - this will open console window.
![Step 3](https://cdn.beyondcoin.io/images/extensions/chrome/ss3.png)
5. In a regular Chrome tab, navigate to a resource in question (e.g. `bynd.beyond/`) - you will notice the console window is populated with lines. Select them and copy to clipboard, or use the context menu's _Save as_ command to produce a log file. Then submit the log along with your [GitHub issue](https://github.com/beyondcoin-project/.beyond-extension-chrome/issues/new).
6. Enjoy surfing .beyond domains!
