Twitter without Twitter
Facebook without Facebook
SoundCloud without SoundCloud

Or: Distributed apps in the browser

---

2 slides: ["Skategirl destroys the universe" promotional shots](https://mermaid.industries/page/presskit/)

---

Store a post history (tweets, blog posts) in a Merkle Tree Accumulator, and store the root hash in a Distributed hash table.

---

Why?: August 2019

> Sunsetting Mercurial support in Bitbucket
> Tue, Aug 20, 2019, 11:44 AM
>
> After much consideration, we've decided to remove Mercurial support from Bitbucket Cloud and the API. Mercurial features and repositories will be officially removed from Bitbucket and its API on June 1, 2020.

> Instaudio
> Instaudio has been shut down.
>
> Instaudio was a website where you could upload audio files, intended for creators to share their works in progress, collaborate, and so forth. It existed from May 2013 until September 2019.
>
> Thank you for everyone who used it as intended, it was a lot of fun. - Mich

> [SoundCloud Users Revolt After Company Announces Plan to Limit Free Uploads](https://www.rollingstone.com/pro/features/soundcloud-users-revolt-after-company-announced-plans-to-limit-free-uploads-922928/)
> December 5, 2019 5:17PM ET
>
> On Monday, the streaming platform emailed its users about an impending cap on uploads. By Thursday, it had reversed course

---

Why?: Mastodon
(Shot of [Mastodon](https://mastodon.social/) front page)

---

Why?: Mastodon
(Shot of a [Mastodon](https://mastodon.social/) profile)

---

Why?: Mastodon
(Shot of a [witches.town](https://witches.town), a defunct Mastodon server, showing an error page.)

---

Three diagrams:
> "Centralized" (Twitter): Many users connected to many users
> "Federated" (Mastodon): Many servers connected to each other, many users who are connected to one server each
> "Decentralized" (?): Many users connected to each other

---

This is not a new idea
(Freenet, diaspora\*, Hypercore/Dat/Beaker)
It has never worked

---

Principles

1. Content addressing
2. Portable accounts
    - "Keys as identities"
3. Must work in a browser tab
    - (Must work behind NAT)

---

Distributed data structures

- Ledgers
    - Various representations
        - Blockchain, Merkle Tree Accumulator (MTA)
    - Various consensus algorithms
        - Proof of work, proof of stake,
          centralized, federated, social,
          Distributed Byzantine Agreement
- Distributed Hash Tables (DHT)

Side note 1: Blockchain and Proof of Work are the *least* interesting things on this slide and they're all anyone talks about.

Side note 2: Bitcoin will kill us all. Proof of Work causes global warming. This cannot be fixed. Cryptocurrency is unsalvageable.

---

4 slides: Merkle Tree Accumulators

(Diagrams showing the Merkle tree in a Merkle Tree Accumulator, and how they change when the underlying content changes.)

---

Handle key rotation
by storing key-change
announcements in a
Distributed Byzantine Agreement*
ledger with high-profile
social network participants
as gateway nodes.

* cf Stellar Consensus Protocol

---

The P2P Network

(Logos for WebRT and libp2p)

---

(Screenshot of the proof of concept. Shows three panes, one of which has "Post" and "Follow" buttons, one of which shows a simplistic post/chat history, and one of which is the Chrome "Inspect" console. The "Inspect" console shows many oblique lines of diagnostics, ending with the message "GOT SENT THING".)

---

Next Steps

- Complete proof-of-concept
- Add caching / content routing
- Merge with Mastodon
- Allow custom CSS, JavaScript (sandboxed) stored in MTA
- Allow arbitrary structured data in MTA
  Custom sites, apps are now possible
- Define convention-standard object formats
  for app data interchange (cf OpenDoc)
- Co-develop app with Foodsters United
- Drive Uber, Foodora, Amazon bankrupt

---

Resources

More about this:
[https://mcclure.github.io/soapbox-2021](https://mcclure.github.io/soapbox-2021)

Try out Mastodon:
[https://joinmastodon.org](https://joinmastodon.org)

My game:
[https://mermaid.industries](https://mermaid.industries)

Thanks to Darius Kazemi and Jason Scott
