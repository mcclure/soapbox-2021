I gave a five-minute talk at GDC 2021 about a prototype I was working on.

## Talk content

* [Text version of talk slides](slides.md)

## Demos

The talk mentions a demo. Unfortunately, this demo isn't ready yet! However, I do have some LibP2P examples that contain some of the same code:

* [Minimal LibP2P+Preact sample program](https://github.com/mcclure/ts-hello/tree/libp2p-preact-unstable): Connects to peers and lists them
* [LibP2P+Preact DHT test](https://github.com/mcclure/ts-hello-bug/tree/43f70ade7425d7e91adfb834c8004251879c9c04): This OUGHT to be a demo demonstrating looking someone up on the DHT by their public key, and sending some data back and forth. Unfortunately it doesn't work because when the stream opens, random garbage inserts itself in the stream and I'm not sure why! Uh... I'm filing a bug on libp2p. Actually using this bug may require watching console.log.

I have a third demo, which actually contains an MTA implementation and a little social media UI, but I can't fix that demo until the second one works. Watch this space?

## Similar projects

* [Mastodon](https://joinmastodon.org) (link goes to signup site)
* [BeakerBrowser](https://beakerbrowser.com/)
* [WebTorrent](https://webtorrent.io/)
* [IPFS](https://ipfs.io/)

## General resources

* [LibP2P](https://libp2p.io/): Site for the project

* [Kademlia](https://pdos.csail.mit.edu/~petar/papers/maymounkov-kademlia-lncs.pdf): Probably the most popular protocol for creating a DHT

* [Merkle Tree Accumulators](https://www.usenix.org/legacy/events/sec09/tech/full_papers/crosby.pdf): A neat data structure for representing a temper-resistant log

## Unrelated

[Here's my video game, check it out, it's neat, there's a video.](https://mermaid.industries)
