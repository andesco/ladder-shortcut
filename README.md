<img src="share-sheet.webp" width="50%">

# Shortcut for Apple Shortcuts

**[Open with Ladder](https://www.icloud.com/shortcuts/f596e509ca644429bacb395002716326)** for Apple Shortcuts allows a user to easily use the share sheet to redirect a blocked URL to their instance of Ladder.

When a URL is shared, the shortcut generates a new URL to open it in Ladder: \
`https://[domain name for Ladder]/[original URL]`

When the shortcut is run with a URL, a <nobr>[URL in ladder-rules][search]</nobr> is randomly selected: \
`https://[domain name for Ladder]/test`

## Add Shortcut

### [Get Shortcut][iCloud] `icloud.com`

### [Download Shortcut][file] `.shortcut`

[iCloud]: //www.icloud.com/shortcuts/f596e509ca644429bacb395002716326 "open shared iCloud link"
[file]: <./Open with Ladder.shortcut> "download .shortcut file"

> [!NOTE]
> You will be asked to enter the fully qualified domain name of your Ladder instance. <nobr>Edit the default example provided:</nobr> `ladder.account.workers.dev`

[search]: //github.com/search?q=repo%3Aeverywall%2Fladder-rules+url%3A&type=code

<!--<a href="https://www.icloud.com/shortcuts/f596e509ca644429bacb395002716326">
  <img src="https://img.shields.io/badge/-Get%20Shortcut-4076D6?style=for-the-badge&logo=icloud&logoColor=white" alt="Get Shortcut" width="200">
</a>-->

## Source Code

source code: [Open with Ladder.plist](<./Open with Ladder.plist>) `PLIST` `XML`

Apple Shortcuts nolonger directly supports importing unsigned shortcuts or shorcut source code. Use these shortcuts to manage and sign source code.

1. [Shortcut Source Tool](https://routinehub.co/shortcut/5256/)
2. [Shortcut Source Helper](https://routinehub.co/shortcut/10060) \
   macOS: signs shortcuts locally \
   iOS: signs shortcuts with [Remote Sign][worker] (service run by shortcut develoepr [gluebyte][profile])

[worker]: http://shortcuts.gluebyte.workers.dev 
[profile]: https://routinehub.co/user/gluebyte 





