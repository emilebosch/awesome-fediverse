# Awesome Fediverse 🛰✨😎

A curated, collaborative list of awesome Fediverse resources for getting ramped up in the Fediverse.

## What's the fediverse?

The Fediverse is a network of social networking [applications](#applications) that communicate with each other via a set of [protocols](#protocols). The servers hosting an application are called an _node_ or instance and can host multiple users.

Here are some resources to get you started:

- [A friendly introduction to the fediverse](https://medium.com/@VirtualAdept/a-friendly-introduction-to-the-fediverse-5b4ef3f8ed0e)
- [Wikipedia](https://en.wikipedia.org/wiki/Fediverse)

## Applications

These products rule the fediverse.

- [Mastodon](https://joinmastodon.org) - Ruby based twitter clone - Follow friends and discover new ones among more than 2M people. Publish anything you want: links, pictures, text, video. All on a platform that is community-owned and ad-free.
- [PixelFed](https://pixelfed.org/) - PHP based instagram clone. A free and ethical photo sharing platform.
- [Peertube](https://joinpeertube.org/) - Javascript based youtube clone. A decentralized video hosting network, based on free/libre software
- [Matrix](https://matrix.org/)
- [Lemmy](https://join-lemmy.org/) - Link aggregator, reddit clone. 
- [Movim](https://movim.eu/) - Social Network based on XMPP
- [Soundstorm](https://github.com/weathermen/soundstorm.git) Soundstorm is an audio-oriented federated social network that speaks ActivityPub. Users can upload their own music, comment on others' tracks, and like/follow/mention just as in a regular social network. Since it speaks the same language as federated platforms like Mastodon, Soundstorm can send new track upload posts to users' followers on the fediverse, allowing them to gain a greater reach than a conventional social audio service.
- [Prismo](https://gitlab.com/prismosuite/prismo) - A ruby based reddit clone. Federated link aggregation powered by ActivityPub.
- [Pleroma](https://pleroma.social/) - Elixir based Twitter clone. The server side is more lightweight than Mastodon, and the UI is more customizable too.
- [Diaspora](https://diasporafoundation.org/) - Ruby based Facebook clone.
- [WriteFriendly](https://writefreely.org/) - Go based publishing platform. WriteFreely is free and open source software for starting a minimalist, federated blog — or an entire community.
- [Friendica](http://friendi.ca/) - PHP based facebook clone. Friendica is a decentralised communications platform that integrates social communication. Our platform links to independent social projects and corporate services.
- [Hubzilla](https://hubzilla.org/)
- [FunkWhale](https://funkwhale.audio/) - Python based Grooveshark. A self-hosted tribute to Grooveshark.com.
- [Cobalt](https://github.com/Gargron/cobalt) - Ruby Video platform by same owner as Mastodon (hasnt' been updated in at least 5 years)
- [ActivityPub for WordPress](https://wordpress.org/plugins/activitypub/) - An ActivityPub plugin for WordPress.
- [Cactus Comments](https://cactus.chat/) - Federated comment system for the open web built on Matrix.

## Protocols

The fediverse is made up of a bunch of protocols. Below are the most used ones.

- [ActivityPub](https://www.w3.org/TR/2018/REC-activitypub-20180123/) - The ActivityPub protocol is a decentralized social networking protocol based upon the [ActivityStreams] 2.0 data format. It provides a client to server API for creating, updating and deleting content, as well as a federated server to server API for delivering notifications and content.
- [Litepub](https://litepub.social/litepub/) - LitePub is a suite of protocols which provide a federated social network. They constitute various profiles of the ActivityPub specification. It is intended that LitePub implementations provide compatibility with ActivityPub, but there are some core behavioral differences.
- [Diaspora](https://diaspora.github.io/diaspora_federation/index.html) - The purpose of this document is to specify the communications that go on between diaspora* servers (and other servers supporting this protocol)
- [WebMention](https://indieweb.org/Webmention) - Webmention is a web standard for mentions and conversations across the web, a powerful building block that is used for a growing federated network of comments, likes, reposts, and other rich interactions across the decentralized social web.
- [Zot](https://zotlabs.org/help/en-gb/developer/zot_protocol) - Zot is the revolutionary protocol that powers Hubzilla, providing communications, identity management, and access control across a fully decentralised network of independent websites, often called "the grid". The resulting platform is a robust system that supports privacy and security while enabling the kind of rich web services typically seen only in centralized, proprietary solutions.
- [OStatus](http://ostatus.github.io/spec/OStatus%201.0%20Draft%202.html) - OStatus is a minimal specification for distributed status updates or microblogging. Many social applications can be modelled with status updates, however. Practically any software that generates RSS or Atom feeds could be OStatus-enabled. Travel networks, event invitation systems, wikis, photo-sharing systems, social news sites, social music sites, podcasting servers, blogs, version control systems, and general purpose social networks would all be candidates for OStatus use.
- [Friendica](https://github.com/friendica/friendica/wiki/Protocol) - The Portable Contacts specification is designed to make it easier for developers to give their users a secure way to access the address books and friends lists they have built up all over the web.
- [Portable Contacts](https://web.archive.org/web/20160426223008/http://portablecontacts.net/draft-spec.html) - The Portable Contacts specification is designed to make it easier for developers to give their users a secure way to access the address books and friends lists they have built up all over the web. Specifically, it seeks to create a common access pattern and contact schema that any site can provide, well-specified authentication and access rules, standard libraries that can work with any site, and absolutely minimal complexity, with the lightest possible toolchain requirements for developers.
- [WebFinger](https://github.com/webfinger/) - WebFinger is used to discover information about people or other entities on the Internet that are identified by a URI using standard Hypertext Transfer Protocol (HTTP) methods over a secure transport. A WebFinger resource returns a JavaScript Object Notation (JSON) object describing the entity that is queried. The JSON object is referred to as the JSON Resource Descriptor (JRD).
- [Salmon](https://en.wikipedia.org/wiki/Salmon_%28protocol%29) - The Salmon Protocol is a message exchange protocol running over HTTP designed to decentralize commentary and annotations made against newsfeed articles such as blog posts. It allows a single discussion thread to be established between the article's origin and any feed reader or "aggregator" which is subscribing to the content. Put simply, that if an article appeared on 3 sites: A (the source), B and C (the aggregates), that members of all 3 sites could see and contribute to a single thread of conversation regardless of site they were viewing from.
- [ActivityStreams](http://activitystrea.ms/specs/json/1.0/) - This specification details the serialization of a stream of social activities using the JSON format. Activities are important in that they allow individuals to process the latest news of people and things they care about.
- [Magic Signatures](https://cdn.rawgit.com/salmon-protocol/salmon-protocol/master/draft-panzer-magicsig-01.html) - This document defines a lightweight, robust mechanism for digitally signing nearly arbitrary messages, along with a simple public key infrastructure.
- [DFRN](https://github.com/friendica/friendica/blob/master/spec/dfrn2.pdf)  - The DFRN (pronounced dee-fern) framework provides the communication basis for a decentralised social network - where cooperating servers share information on your behalf while operating in a web of trust relationships you control. It can provide a “Facebook-like” experience without requiring a central company or server.
- [WebSub](https://w3c.github.io/websub/) - WebSub provides a common mechanism for communication between publishers of any kind of Web content and their subscribers, based on HTTP web hooks. Subscription requests are relayed through hubs, which validate and verify the request. Hubs then distribute new and updated content to subscribers when it becomes available. WebSub was previously known as PubSubHubbub.
- [PubSubHubbub](https://github.com/pubsubhubbub/PubSubHubbub) - PubSubHubbub is an open protocol for distributed publish/subscribe communication on the Internet. It generalizes the concept of webhooks and allows data producers and data consumers to work in a decoupled way.
- [Pubcast](https://github.com/pubcast/pubcast) - An experimental ActivityPub based podcasting platform
- [Pubgate](https://github.com/autogestion/pubgate) - Lightweight (Gotta Go Fast) ActivityPub federator

## Sites

- [WeDistribute](https://wedistribute.org/)
- [Fediverse.party](http://fediverse.party/)
- [The federation instance stats](https://the-federation.info)
- [Fediverse network stats](https://fediverse.network)
- [Fediverse.space](https://www.fediverse.space)
- [Fediverse glossary](https://tilde.town/~petegozz/Fediverse_Glossary/)
- [Mastodon Instance Picker](https://instances.social)

### Resources

#### Activitypub

##### Talk

- [Federation in social networks - Lwn.net](https://lwn.net/Articles/741218/)
- [Wikipedia Article](https://en.wikipedia.org/wiki/ActivityPub)
- [What is ActivityPub, and how will it change the internet?](https://jeremydormitzer.com/blog/what-is-activitypub-and-how-will-it-change-the-internet/)
- [ActivityPub - one protocol to rule them all?](https://schub.io/blog/2018/02/01/activitypub-one-protocol-to-rule-them-all.html)
- [An ActivityPub Philosophy](https://cjslep.com/c/blog/an-activitypub-philosophy)
- [On standards divisions and collaboration (or: Why can't the decentralized social web people just get along?)](http://dustycloud.org/blog/on-standards-divisions-collaboration/)
- [ActivityPub - Final thoughts, one year later.](https://schub.io/blog/2019/01/13/activitypub-final-thoughts-one-year-later.html)
- [From GNU social to Mastodon](https://thomask.sdf.org/blog/2018/08/19/from-gnu-social-to-mastodon.html)

##### Developers

- [How to verify requests - Implementing an activity inbox - Mastodon](http://blog.joinmastodon.org/2018/07/how-to-make-friends-and-verify-requests/)
- [How to implement a basic ActivityPub server - Mastodon](https://blog.joinmastodon.org/2018/06/how-to-implement-a-basic-activitypub-server/)

#### Misc

- [Identity proof of mastodon with keybase](https://keybase.io/blog/keybase-proofs-for-mastodon-and-everyone)

## Videos

- [Lets chat about ActivityPub](https://www.youtube.com/watch?v=g-Fiku7KKBU)
- [ActivityPub and the federated social networks](https://www.youtube.com/watch?v=li_usG-RmnY)
- [Easterhegg 2019 - ActivityPub, the Fediverse, and Everything](https://www.youtube.com/watch?v=kbUEIxSN4aU)

## Meetups

TODO

## Slides

TODO
