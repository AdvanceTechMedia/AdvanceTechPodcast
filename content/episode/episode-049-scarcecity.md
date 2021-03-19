+++

Description = "This episode features Chris Tramount, CEO of Scarce.City a Bitcoin based marketplace enabling Lightning Network auctions for Bitcoin artists. To view the show transcript, complete guest bios and links mentioned in the episode take a look below or go to advancetechmedia.org and click the episode title."

aliases = ["/49"]
author = "Alexandra Moxin"
categories = []
date = "2021-02-12T00:00:01-07:00"
episode = "49"
episode_image = "img/guest/ATP_49.png"
explicit = "no"
guests = ["christramount"]
hosts = ["alexandra"]
#sponsors = [""]
#images = [""]
news_keywords = []
podcast_duration = "49:45:00"
podcast_file = "advance-tech-podcast-049-chris-scarcecity.mp3"
podcast_length = "49:45:00"
podcast_bytes = "35096759"
tags = []
title = "Scarce.City with CEO Chris Tramount"
youtube = "OfOwjf7piiU"
draft = "False"
+++

Written by Alexandra Moxin

<i>"Bitcoin is the hero's journey of money", Chris Tramount</i>

This episode features Chris Tramount, CEO of [Scarce.City](https://scarce.city/) a Bitcoin based marketplace enabling Lightning Network auctions for Bitcoin artists.

We get into Chris' background, how Scarce.City started, the first lightning auction, and upcoming auctions. We discuss a unique upcoming feature that will enable auction participants to use their Twitter reputation as collateral, privacy and so much more.

You can reach Chris on twitter at [ctramount](https://twitter.com/ctramount).

**new feature** Full transcript with timing points is available below.

### Show Links

* [Scarce.City](https://scarce.city/)
* [Scarce.City on Twitter](https://twitter.com/scarcedotcity)
* [Scarce.City on Mastodon](https://bitcoinhackers.org/@scarcecity)
* [Chris Tramount on Twitter](https://twitter.com/ctramount)
* [Scarce.City blog](https://scarce.city/blog)
* [Relentless Optimism a Chiefmonkey & mosaic.rocks collaboration.](https://scarce.city/products/relentless-optimism)
* [Chiefmonkey on Twitter](https://twitter.com/hodlrdotrocks?lang=en)  
* [mosaic.rocks on Twitter](https://twitter.com/MosaicDotRocks)
* [Bull on Fire: An Eppo & Anita Leemburg collaboration](https://scarce.city/products/bull-on-fire)  
* [Bitcoin Full Node Sculpture by FractalEncrypt](https://scarce.city/products/full-node-sculpture)
* [Bitcoin as Money: The Internet We Were Promised by Chris Tramount](https://scarce.city/blog/the-internet-we-were-promised)
  
### Show Transcript
Alexandra933  0:00
Welcome to the Advance Tech Podcast. Joining me today is Chris Tramount, CEO of Scarce.City. Welcome, Chris.

Chris Tramount  0:07
Hey, Alexandra Good to be with you.

Alexandra933  0:09
So let's dig right in, before we get into Scarce.City, let's talk a little bit about your background.

Chris Tramount  0:17
Sure. So I started off as an industrial engineer, and I was basically working with big retail corporations helping them move items from point A to point B cheaper, faster, safer. So I worked with a bunch of Fortune 50 and Fortune 500 Companies. Did that for a few years, great early experience, but got burnt out pretty quickly and somewhere along the way, I caught the entrepreneurship bug, especially related to tech startups. I've been plugging away at different tech startups, whether it's on my own or working for well funded startups or working for corporations trying to foster an entrepreneurial type environment for about 10 years now.

Alexandra933  1:07
So let's talk a little bit about Scarce.City, how it started, and what you're hoping to do with it.

Chris Tramount  1:13
So Scarce.City is a Bitcoin based marketplace that sells Bitcoin goods for Bitcoin using Bitcoin technology. We came up with the idea by just observing the creative space in Bitcoin. After spending a few years in the Bitcoin rabbit hole, it was really the creative space that drew me in taking Bitcoin to its logical conclusion, I felt that the art related to this movement would age to become timeless and iconic of the early stages of what I think is a real Renaissance that we're experiencing here.

So after realizing that, and also noticing that a lot of my favorite creatives in the space struggled to sell their goods in a way that was authentic to Bitcoin, I started looking for an opportunity to help. One of the best ways for anyone to monetize their art in the crypto space generally is through Ethereum based marketplaces, and they certainly have some cool things going for them. But selling Bitcoin related art, by real bitcoiners, doesn't feel right in that type of format.

So I wanted to figure out what we could do using Bitcoin selling for Bitcoin in a way that is consistent with what I saw as Bitcoin’s values. So we tested a few ideas at first, the first MVP was selling face masks that used Bitcoin’s key pair technology, to prove the authenticity and supply of each of the face masks. So kind of a cool gimmick, testing out some of the things that make Bitcoin unique. We partnered with an up and coming Bitcoin time traveler, to brand the face mask with his personal style. We sold some face masks, it went beyond our expectations and some interesting things came out of it.

First of all, we got the attention of some of the bigger names in the Bitcoin creative community, specifically, Chiefmonkey who's gone on to become our MVP Bitcoin artist. We learned something about lightning. It was interesting going into that sale, we weren't sure if we were going to support lightning. It just so happened that this was around the timing of the halving and fees were spiking and it was kind of a last minute call. We were like, okay, well, we have to support lightning at this point. We were shocked to see that about a third of our sales were through the lightning network and that gave us a little bit of a wake up call, we have to understand lightning.

So that was the first time I set up a lightning wallet and it was the first transaction using lightning. It was tough to set up. I won't say it was, it certainly wasn't ready for normal users at that point. But the feeling of having that first transaction go through instantly gave me the feeling of like, okay, this is the future of Bitcoin payments and maybe even beyond. And yeah, we went down our own lightning rabbit hole at that point and realized that lightning was actually much more than just payments, that it enabled an entire infrastructure for app development.

Ryan Gentry, put out a piece when he was at multicoin and I always forget the name of this piece because it is kind of hard to remember, but it's like: Lightning as a Web; 3 Tools for the Heretical Developer. I'm sorry, I'm totally butchering it. But it was a fantastic piece that totally laid out how lightning public nodes could be used as self sovereign digital identity identification, and also laid out how the lightning network could be used as infrastructure for a more private form of the internet.

That kind of started getting our wheels turning, we started talking with our artists community that Chiefmonkey had helped us form and started learning about what their needs were and how we could address them with lightning. It was actually Chiefmonkey who came up with the idea for lightning auctions initially. That's been our first product that we've put our full force and effort behind and that's what our current focus is today.

Alexandra933  5:57
I'd love to dig into the lightning network a little bit more. But first, let's talk about the first lightning auction and what's upcoming for the next next few months.

Chris Tramount  6:06
Sure, so we did our first auction just over a month ago now. Chiefmonkey came up with the idea so he had to be the guinea pig with this thing, and he created an absolutely beautiful piece called Relentless Optimism. It's the iconic memed Bitcoin Phoenix taking off with a physical Bitcoin in its grasp. He partnered with mosaic.rocks, who does fantastic mosaic work.

So it's just has incredible detail with the mosaic within the Phoenix. So super proud to be able to debut the auctions was such an amazing piece and the auction went really well. Maybe I should start by talking about how lightning auctions work. Essentially, it keeps participants accountable for their bids by collateralizing their bids through the instant, low fee, anonymous payments on the lightning network.

So the way it works is if you want to want to bid on an item, you put in how much you want to bid, we ask for an email address just so we can verify the winner doesn't have to be your personal email address. We ask for a display name, which acts as your pseudonymous identification and we prompt you to pay a lightning invoice that represents a small percentage of what you're actually bidding.

This deposit acts as collateral for your bid. So at the end of the auction, the highest bidder has 24 hours to pay the full bid amount. If they do not pay that bid amount, they lose their collateral, and the next highest bidder has their opportunity to pay their highest bid. Once the final bid has been paid, the remaining participants receive their collateral back.

We battle tested this thing with our artists community the best we could before we released it, but you never know how this is going to go until you put it out there. We were blown away by the results. There was a ton of enthusiasm. We had 19 different bidders and 53 unique bids and the winning bid was one bitcoin which was beyond our expectations and beyond the expectations of our artists. So we were thrilled with the results and now we are focused heads down on making it even better and we have a whole lineup of auctions ready to come.

Alexandra933  8:43
One bitcoin is significantly more than it was when this auction first started. It was in December?

Chris Tramount  8:52
Yeah, it was December, I think was early December, maybe even late November. But yeah, the price was around $19K USD at that point. It was shortly after that the Phoenix officially took flight and here we are sitting twice that much. So an even greater result for the artists.

Alexandra933  9:10
That's awesome. That's really nice symbolism too.

Chris Tramount  9:13
It's totally perfect for the timing of this moment.

Alexandra933  9:20
So what can people look forward to in upcoming auctions?

Chris Tramount  9:24
Well, we have our next auction next week. I'm not sure when you'll air this but it would be the second week of January. We have a lineup that's pretty healthy for the first quarter of the year of additional auctions and we're improving the product each step of the way. A couple of the big upgrades that you can look forward to.

We are adjusting the collateral requirement, which does require a bigger upfront collateral but if you want to make additional bids you just have to top off your collateral, instead of having to pay a fresh round. So we feel like that simultaneously keeps bidders more accountable while reducing friction to really engage with the auction. We are adjusting the increments with which you can bid, adjusting a bunch of small user interface type of things, that'll just make things a little bit slicker.

I think one of our biggest upgrades that we haven't started on yet, but we're really excited for is using lightning logins. It's really slick. Essentially, you just scan a QR code, with your lightning wallet and you're signed in, you have all of the benefits of having a traditional account. We're able to maintain your history, whatever information we have that you've given us. While maintaining your privacy, we don't need your email address at that point, we don't need a password, nothing like that.

Once we have that, we'll also be able to implement a reputation system. So if you showed you were trustworthy, and past auctions, maybe your collateral requirement goes down, you'll have the option to to authenticate through Twitter. If you have an established Twitter account, then your Twitter reputation can be on the line rather than collateral payments. So just overall, we think it offers a better experience for users, and hopefully will lead to more participation and higher bids for the artists.

Alexandra933  11:56
So I'm curious to see how, and you probably don't want to announce the inner workings until it's until it's launched, but what was the reasoning around using Twitter reputation as a basis for collateral instead of actual funds?

Chris Tramount  12:12
I think, high level studying different auction systems, the main challenge is keeping bidders accountable for their bids. The two main ways to do that is either through collateral or reputation systems. Now, the trade off with reputation systems is they usually come with giving up personally identifiable information, which doesn't really jive with Bitcoin’s principles. That's why we started with collateral and the lightning network makes that so easy.

However, it is somewhat of a lift for the user to make sure they have a high balance in their lightning wallet, to put their SATs up as collateral. So for the users who are open to it, we want to create an option for them to to basically stake their reputation instead of the collapse in their collateral. We would do it in a way that doesn't leak any information to Twitter, it wouldn't be your traditional Twitter authentication, it would be through a DM type of system.

Imagine being able to participate in an auction without giving up any collateral and it's your Twitter handle that's showing up as a participant in the auction. Not only does that create more of a seamless experience, but it also makes the auction more social. We noticed in the first auction that a lot of users who were prolific on Twitter were putting in their Twitter handles as their display name anyway. So it's obviously a behavior that's already kind of organic. So if we can promote that, while making the auction experience better, as far as not having to give up your stats for even the short term, time period of the auction. It's a better experience all around.

Alexandra933  14:17
Cool. I imagine that would also have deeper privacy trade offs as well, too. So what I'm thinking of is if people are using anonymous Twitter accounts, just their username, do you need more information beyond that?

Chris Tramount  14:33
No, that's all we need. Of course, it depends on the Twitter account. If you just create a Twitter account in the moment and have zero followers you're not getting much reputation for us to work with. But if you have been on Twitter for 10 years and you have even a few 100 followers, your reputation is on the line. If you don't pay that final bit amount, we're going to call you out. It's not going to look good for you.

I think especially the Bitcoin community centers around Twitter and your Twitter profile is, it's important that people’s reputation goes a long way in this space. So in a lot of ways, it's more valuable than putting up short term short term collateral and again creates a better user experience.

Alexandra933  15:22
Totally. My friend Karo wrote something in one of the earlier volumes of Citadel21 on reputation and how it's a bitcoiner's primary currency. It's a really unique thing because you hear in other communities people talking about integrity and reputation and it seems like the more that's brought up, usually, it's correlated to having less.

There's an example, I don't want to go too deep into it because I don't want to call out people, but there was a bet that was recently made. The person that lost reneged on it and he wasn't a bitcoiner. So you can read between the lines and find out who that was. But yeah, I think the idea of reputation as currency is very interesting. We've kind of lost that. And I think that's an intrinsic value and an absolute value at the same time. So it's an interesting concept to explore.

Chris Tramount  16:21
Yeah, I agree. I'm fascinated in general by the concept of the pseudonymous economy, this is something Balaji he's written a lot about and it's something that we feel like we're in position to embrace.

You should be able to use your reputation as identification, and be able to make money with that identification without tethering it directly with who you are in the real world. We think there's a lot of opportunity for that, both for bidders of our auctions as well as the artists. A lot of the artists are pseudonymous as well so there's no reason for us to know their real identity, nor for the participants in the auction.

Alexandra933  17:07
Really interesting. On the surface, it seems like you're exploring a market that has privacy as its first point without going directly into a dark market where it's fully anonymous. Not that there's anything wrong with that. But it seems like you've got a public facing, privacy first, marketplace developing which will be really interesting to watch.

Chris Tramount  17:33
We think it's really important for this space. Users value their privacy as they should and we want to respect that as much as we can. It's part of Bitcoin and we want to align our platform with Bitcoin as much as possible.

Alexandra933  17:49
So let's talk a little bit about the social side of Bitcoin. There's been a long discussion, there is a Bitcoin community, there isn't a Bitcoin community. I think that you can kind of look at it like you're saying, there’s this cultural Renaissance and art Renaissance within the space. It's really such a rich ground for creativity.

It's really interesting to see what's happened in the last couple of years, especially 2020. I think, when we had all the additional time that maybe gave people time to explore that side and maybe spend a little more time working on those nebulous, creative ideas that we never seem to have time for. I'd love to get your thoughts on that. What is the Bitcoin community? Is it maybe a Bitcoin art space; is it just a creative community? Is it something we can even define and should we?

Chris Tramount  18:41
I think it's really fascinating. I noticed it first with my own personal journey in Bitcoin and realize that it's very similar to the journeys of many bitcoiners. When you start looking into Bitcoin, there's kind of a natural path, right? it starts with skepticism, and then at some point, the flip switches for you and you go down the rabbit hole. You invest a little bit of money, you start learning more about it, you invest a little bit more money, probably and before long, for most people, it consumes your attention.

It did for me, and I know it does for many, and it's really interesting to think what it is about Bitcoin that sucks people in. Max Keiser calls it the metaphysical properties of Bitcoin. It could be something about just absolute scarcity, or the absolute truth of the Bitcoin network. More recently, I've been thinking about it as Bitcoin is like the hero's journey of money and we're fascinated by all of these stories.

They follow a similar arc where a hero starts from humble beginnings, goes through trials and tribulations and ultimately prevails. I feel like we're witnessing that with Bitcoin and just watching that story unfold in the real world. People can't help but to watch and root for Bitcoin once they get into it. Whatever it is, it just sucks people in. Whether you are a technical person, someone who focuses on content, a narrator like yourself, or, more drawn to the arts, there is a way for everybody to contribute to the space.

I think the infrastructure for the technology is pretty clear. There's plenty of opportunities to create software using Bitcoin, especially now that the protocol is more mature and the infrastructure layer is more developed. People like us who are more focused on apps we can build on top of BTC pay server, we can build on top of the lightning network, to create new consumer facing experiences.

For narration, I think we're just starting to see the new possibilities that Bitcoin and specifically the lightning network unlocks. Whether it's breaking the paywall model and paying for content on an individual basis, or, paying to stream a podcast like Sphinx chat is starting up now. I think there's a world of possibility that we're going to see unfold within the next couple of years and in the art space.

I mean, the true OG Bitcoin artists have been creating Bitcoin art, for many, many years, and they've been doing it just out of some kind of pure passion, without real effective means for selling their work. Of course, Twitter, in its own way acts as a marketplace and there is Bitcoin Talk Forums. They have been amazing at creating auctions and ways to sell Bitcoin art and Collectibles through kind of a wonderful web 1.0 forum.

We think there's a real opportunity to create an open marketplace that makes it as easy as possible for artists to connect with all potential Bitcoin collectors around the world. By creating this marketplace, we think we can support this part of the Bitcoin space to really grow. In a way, there hasn't really been a market for this yet and we're hoping to help create that market. If we do, we hope to incentivize artists.

I'm sure there are many creatives in the Bitcoin space, who have an idea for an art project, but they just haven't done it because they didn't feel they had a way to make money from it. We are hoping to create that option for them. I think we tend to think of Bitcoin as a financial revolution, which absolutely it is, but it's just as much of a cultural revolution.

Bitcoin stands for something. It's a way of life. For many people. It's changed many people's lives. People are so enthusiastic about it once they get into it and they want to express their enthusiasm for Bitcoin. Whether it's through art, clothing, collectibles, we want to be a marketplace that helps people find the goods that represent their Bitcoin enthusiasm.

Alexandra933  23:34
Awesome. So it sounds like beyond auctions, you're looking at making it a wider marketplace, where people can find all sorts of goods. Is that right?

Chris Tramount  23:43
We are, we are focused on supporting Bitcoin culture and adoption. So at least for the foreseeable future, anything that we sell will have a Bitcoin bent to it, but again, Bitcoin, to me Bitcoin culture is not… it doesn't have to have a Bitcoin logo on it, right? to me Bitcoin symbolizes freedom. Right? Just striving for a better lifestyle. So I think that extends and covers a broad spectrum. 

But yeah, beyond original art through auctions, we have tested limited edition sales, clothing, the face masks that I mentioned, we think there's a lot more that we can do with that. So what we are planning in the pretty near term is bundling, limited edition sales with our auctions. So what this would look like is, if, let's just say, let's use Chiefmonkey as an example, if he were doing another auction, that his original artwork went for one bitcoin. 

Not everybody can participate in that auction. So maybe there's t-shirts with his designs. That are also available or prints of the original artwork that are also available. Maybe there's also sticker packs. So the idea here is anybody who wants who's into Chiefmonkey's artwork, and who Chiefmonkey is, as a Bitcoin artist, they have a way to participate and get a piece of that sale, no matter what, what their preferences are, or what their limitations are, as far as spending money.

Alexandra933  25:29
That's a good idea because there's a lot of people that think, now that bitcoin is $40,000 and trending upward: I've missed it. But people don't realize you can buy fractions of Bitcoin, known as sats or bits, depending where you stand on the issue.

Chris Tramount  25:47
Yeah, it's just a testament to how early we are in this space, you know, we’ve got a long way to go. But certainly the lightning network helps us make micro payments on lightning.

Alexandra933  26:03
So you wanted to talk a little bit about NFTs. Now, NFTs are usually seen as an Ethereum only product but what are your thoughts on that? Because it sounds like that's not the case.

Chris Tramount  26:15
In my opinion, it doesn't have to be the case. Anytime a podcaster asks me what I want to talk about, I always throw out NFTs because I feel like it's the most controversial opinion I have. If we're going to sit here and talk for an hour, I might as well stir the pot a little bit. It's interesting when NFTs hit the Bitcoin Zeitgeist every once in a while, you see the flame wars going back and forth.

It's usually the Ethereum people versus the Bitcoin people and the consensus on the Bitcoin side is that NFTs are just like this silly hype toy. While there's certainly a lot of hype, and I could agree that at times, the current format of NFTs gets saturated and bubbly. I think NFTs as a general concept are here to stay, and not only that, I think they're extremely important.

I've come to believe that NFTs are the infrastructure for what I see is kind of like the next phase of the internet. I'm specifically referring to the metaverse now, a totally nebulous concept. No one really knows what this is going to look like. It's something we read about in sci fi books. But we're already seeing the early beginnings of what a metaverse could be.

Fortnite, Minecraft, Roblox could be considered centralized versions of a metaverse and and Ethereum space, you have projects like Decentraland, Cryptovoxels, and others that are showing what a more decentralized metaverse could look like. So it's unclear what the final version of this is going to be. My guess is, it's going to be a hybrid of these different worlds with these different trade offs and ways to seamlessly move from one to the other.

What I think is going to be really important with the final version of a decentralized metaverse is that there will be ownership of the digital goods, and that metaverse. There will be open marketplaces for those digital goods and that's essentially what NFTs make possible. So while it's easy to look at cryptokitties and say, Okay, I could just copy paste this thing and experience it in the same way that the owner could in the metaverse, you know, I don't think that's going to be the case.

What we're already seeing is there's real demand from buyers to collect NFTs. That is incentivizing artists to create new types of NFTs that use digital art, to create more immersive artistic experiences that just aren't possible in the physical world. Because this is software, it's digital, there's so much more functionality you can add on top of NFT art, that's just not possible with physical art.

You can add commercial rights to an NFT, you can represent a legal contract of some sort, you can tether the experience of the NFT, the aesthetics of the NFT. to real world real world events. There's one NFT that's out there that changes its appearance based on Bitcoin’s price. So a world of possibility there. I think we're just scratching the surface of what's really possible with these things.

Because there already is this growing marketplace of buyers and sellers of NFTs you're seeing the infrastructure level develop. Whether it's these virtual worlds, or, other ways to interact with NFTs, there's going to be new ways to experience NFTs that you own, that you can't just copy and paste and experience. In the same way if you're not the owner of NFTs. So I'm a big believer in the space, I think it does have a long way to go, I think it's going to take five to ten years to figure out what this technology is really capable of.

But with the assumption that it is important, I think it's also important to bring NFTs back to Bitcoin. The metaverse, if this does end up being a social layer of the internet, where we spend a significant amount of our time and invest a significant amount of our assets. Look at the kids playing Fortnite these days, spending 1000s of dollars on skins, they're not going back from that, right?

They're going to continue investing a large chunk of their money in digital goods, especially when there's a way to do it in a more trustless way that doesn't depend on Fortnite. So, the infrastructure of the NFTs and these virtual worlds, we're going to want them on a really secure Foundation, and Ethereum I love a lot of the applications being built on top of it, but I have real concerns with the fundamentals of Ethereum.

We don't know what proof of stake is really going to look like. Eth 2.0 we've been promised that for years. So I don't want to own I don't want my virtual assets with the expectation that it's going to be a significant amount, a significant percentage of my assets. I don't want that on Ethereum. I don't feel good about that. I feel much better if they had Bitcoin as their foundation and I think this is going to be more important over time.

So this is the option we want to create in the space. We're first focused on physical art, but RGB is a third layer protocol that's going to create a new model for Bitcoin NFTs. We want to be pioneers implementing that protocol. And look, we're supporting Bitcoin culture and adoption now but we see this as an entryway to ultimately becoming a marketplace for Bitcoin NFTs for a Bitcoin based metaverse.

Alexandra933  32:50
That's really cool. I like it. I can see a lot of potential VR applications, as this industry matures, having unique tokens. For listeners that aren't familiar with NFTs, they are non fungible tokens, a special type of cryptographic token representing something unique (dollar A is not equal to dollar B). Where would you recommend people go if they were looking to read up a little bit more on NFTs?

Chris Tramount  33:08
Oh, that's a great question. I mean, look, the application layer on Ethereum NFTs is exploding, there's no doubt about it. So the Ethereum marketplaces are probably the best way to get educated and what this is about, whether it's SuperRare, Nifty Gateway, or, just type in NFTs, and you're going to see the latest headlines. People like Trevor Jones are selling their NFTs for hundreds of 1000s of dollars. So, if you start looking, it's pretty easy to find information.

Look at their fundamental core, what they really are, are tokens that are associated with some type of media, whether that's an image or a video and I think we're not going to be limited to those media formats going forward. They use the cryptography of whatever blockchain to prove the creator of that token, and the owner of that token, and through the blockchain, you can see the full provenance of ownership of that token.

When you have these ownership models, you combine that with open marketplaces and it becomes really easy all of a sudden to transact these NFTs, these non fungible tokens, for the cryptocurrency of your choice and it creates an amazing dynamic. I like to think about the traditional Renaissance and being an artist during that time. Even an extremely well recognized artist, the Mona Lisa was commissioned work that was a Venice merchant, paying Leonardo da Vinci to paint his daughter, I believe.

So while Leonardo da Vinci certainly put his heart and soul into the artistic creativity of that work, it wasn't his idea. It's not like he was burning with desire to create the Mona Lisa. When you have these open marketplaces that these token models enable, now, even in this early form, there are probably 1000 artists around the world that are making a living off of being an artist with digital art and they're creating art that they truly want to create.

All they have to do is find one buyer anywhere around the world that identifies with that work of art who values it and is willing to pay for it. Look, that's a beautiful thing for artists and what's good for artists is great for society. We're just in the early beginning. So we think it's a huge opportunity to bring NFTs back to Bitcoin, where we feel like they can have a stronger foundation, and hopefully have a better opportunity to scale into the massive liquidity of Bitcoin holders around the world.

Alexandra933  36:39
It would be cool to see and explore the additional media, a tokenized experience that you could trade between people, or memes and things like that.

Chris Tramount  36:50
I love that you say memes. And this is, again, I love giving Chiefmonkey credit for things, he's always had the best ideas. But yeah, you think about Bitcoin Twitter, the Bitcoin space in general, Bitcoin has the best memes hands down, like you can't even argue with that, if you're familiar with them. So what does it look like if you tokenize these memes?

I know there's a lot of people out there who would love to have digital ownership of these memes. I think they can be considered quite valuable, especially the ones that have aged to be really iconic, and it creates again a dynamic where people are more incentivized to create memes.

Today, it's just amazing that people are creating memes just to be able to share them with people and get some attention around them. Imagine if they could actually make money from it? Imagine the rocket fuel we could add to the already amazing Bitcoin memespace?

Alexandra933  37:52
Yeah, it'd be really cool to see. I really like the idea of this whole new marketplace opening where people can be rewarded for past work. Because a lot of people do things just because they're passionate, and I think at its purest, that's creation. I think, when you start trying to monetize that in an inauthentic way, that's when you start getting... the corporate... you go into any office and you've got ‘Patience’ or ‘Leadership’, and it's a pretty painting but it's really flat and there's nothing to it.

Chris Tramount  38:29
Yeah, no HR in Bitcoin. HR is not allowed Bitcoin. You bring up a really good point. I think we're seeing this, frankly, in the Ethereum space already where talent has started to become commoditized. There's so much talent out there and some of these artists are just cranking out piece after piece on a daily basis. Even creativity feels like it's been somewhat commoditized.

I think the way we're going to look at this space, down the road, I think the same can be said for the different periods of art in the past and, I’m no art history scholar or anything, about the physical art and the contemporary period of art. Banksy and Jeff Koons are just two examples of people. Jeff Koons he has a factory of people working for him to create his artwork.

I don't think history is going to look great on that, while Banksy, his work just screams authenticity. It all has a strong social message that's super relevant to today's society and he continues to do work that is not for profit. While he still makes, I'm sure a great living off of his artwork. So I think it's the authenticity that is really going to stand the test of time in this space, and again, I think that's another advantage that Bitcoin NFTs and Bitcoin art in general can offer.

We are focused on Bitcoin artists and there's obvious that there's subjective definitions for what that is. But look, I love the idea of, don't tie me to this, but people who are artists that sell on scarcity. I want to know that they're Bitcoin artists, and, maybe they can sign a message with their private key showing that they have ownership of Bitcoin, or maybe they can open a lightning channel with us just to prove that they're real bitcoiners.

Some of these artists, I hear them do interviews and they say they just like were introduced to the blockchain space a month ago. They're already creating art that has a Bitcoin logo on it, like, what is that about? So look I think authenticity is more than the artwork. It's so much about the artist and I think it’s the authenticity and the motives of the artist that is going to stand the test of time. Those are the artworks that are going to be considered most valuable in the future, as we mature along this, what I see is the Bitcoin revolution.

Alexandra933  41:33
What's interesting about art is usually you see the most expressive art, I guess in its pure form, when people go through conflict. Whether they're in a war torn nation, people kind of turn inward, and they don't really know where to put that creative spirit and so they conduct it into something that is expressive. I think as we see societies shift toward being more stable, again, you start getting that kind of HR art.

I know in the countries that I've traveled to, some of the most amazing artists come from the poorest places. So I really love the idea if people are struggling right now, maybe they're creating something and they don't have any other avenue other than their art to put that kind of, you know, that angst.

So I love the fact that even if they might be going through tough times now maybe they can benefit from that in the future. I really applaud you on creating that environment and marketplace for them. So that, today's future struggling and starving artists will maybe one day be able to not be in that state.

Chris Tramount  42:36
For sure a lot of these artists just believe in Bitcoin and they want to express their passion for Bitcoin and art is their outlet to do that. So while there's always the risk of over-commercializing a space, some of these artists they're not able to focus as much attention on Bitcoin as they would be able to if they could make a career out of it.

Maybe they're working 40 to 70, 80 hours a week doing something that they just have to sustain their lives with and can only devote a small percentage of their attention towards Bitcoin art. If all of a sudden, they can just focus on Bitcoin art, they can create more Bitcoin art and it can still maintain its authenticity, as long as their passion for Bitcoin is authentic.

Alexandra933  43:23
That's true. If you look at art, going back through history, usually it was the artists that were able to have a patron be able to support their work so they could focus exclusively on that. I often wonder how many more interesting creative works we would have, if people had the ability to be able to take the time out of their lives to be able to explore that. You're kind of either in survival mode, or you're in this unique creative space, and there's not really many avenues between the two.

Chris Tramount  43:53
Well, I think we're going to find out. I see it focusing around Bitcoin. But in general, these open marketplaces with token economics, it's creating an entire primordial soup for new artistic channels and new ways to make money from that. That's just going to create more art over time and I think it's going to be beautiful for the creative space in general.

Alexandra933  44:24
Yeah, it'd be nice to see. People think the digital world, they think it's just it's ones and zeros, and it's very formulaic, but I'm loving this new creative rebirth that we're seeing in this space. I'm curious to see where it goes over the next decade or two.

Chris Tramount  44:38
Yeah, I always think about Marc Andreessen, his quote, that software is eating the world. We've seen it through the different phases of the internet, specifically with media. Digital content enabled by software totally dwarfs physical content now and I think we're going to see the same thing with each industry over time. I think it's time for art to experience that.

I wouldn't be surprised if 10 years from now there's more money spent on, sounds crazy but I believe it, digital clothing than physical clothing. I think this is it starts with art, but you can apply it to any type of asset or good. I even think about real estate, right? Real estate has become so unattainable for so much of the world.

You're going to have digital real estate, you already do have digital real estate, and that is going to be attainable for everybody in the world in a different form. So software eating the world. I think we're going to see that applied to the different applications of goods, whether it's art, clothing, real estate, and just assets in general. It's going to be fascinating to watch.

Alexandra933  46:13
I'm really curious. So you're familiar with the concept of citadels? So for listeners and viewers that aren't the idea that you've got this kind of stronghold, and whether that's an actual physical place, or whether it's an idealistic place, it'd be really interesting to see how digital citadels start. Kind of like how you have the exclusive message boards, only if you go through certain tests you can get into. I'm curious to see what that's going to look like.

Chris Tramount  46:47
Yeah, I agree. I think anytime we have a new technology, the first impulse is to take the physical version of it and try to digitize it, when it usually turns out that the purely digital form is what becomes really important, right? So again, going back to content, just throwing physical newspapers or magazines on the internet was one of the first applications but it turns out that podcasts, or blogs or tweets have become much more important to digital content. I think we're going to see the same thing happen in the NFT space throughout all of its applications.

Alexandra933  47:29
So for newer artists looking to contribute, how would they reach out to you, how can they get involved?

Chris Tramount  47:38
I'm really easy to find on Twitter at scarcedotcity. DMs are open. You can always also reach out to me on my personal Twitter account at ctramount. You can also sign up for our newsletter and stay up to date and get our email there. Reach out to me whichever way you're most comfortable with.

We are always interested in talking with anybody who's passionate about Bitcoin art and the creative space in Bitcoin but we're specifically looking for Bitcoin artists. We do have a founding group of Bitcoin artists that have been involved from the very beginning and we are limiting ourselves to their works right now. Because frankly, we have a lot of kinks to work out in our processes or dealing with sending physical items across the world. It's not as simple as just throwing up an auction and asking people to bid on it.

We want to minimize the risk for buyers and sellers and, something that's important to us also is trying to prove the authenticity of the work. So we have certificates of authenticity that we offer for all artwork that we're selling, that uses the Bitcoin blockchain to prove the true artist and prove ownership of the buyer and prove the value for each transaction. So a lot of this is going to take some time to operationalize and get ready for a larger audience. But in the meantime, we love connecting with artists. We love seeing what they're working on and we hope to onboard them.

Alexandra933  49:22
And if people are just looking to help, how can they get involved?

Chris Tramount  49:27
Again, DM me, email me. Anybody who's passionate about the space, even if you don't know how to contribute, hit me up. I love to chat about these things. At some point, we'll be looking for more developers. We'll be looking for investors at some point. So any way that you want to contribute, we may be able to find a place for you so, happy to explore it.

Alexandra933  49:56
Awesome. I often close some of the shows asking if you have a question for viewers and listeners. So, over to you.

Chris Tramount  50:07
Do I have a question for viewers and listeners? Oh, look, I mean, the NFT space is one of the most misunderstood spaces. So it's less of a question. It's more of a call to action to check this out. try to explore its possibilities. You should be skeptical in the beginning, I certainly was. see the art that's being created, see how it's being experienced.

I think the sooner that you understand its capabilities, you are going to be better prepared to maybe contribute to it or embrace it. And, you know, help us bring it to Bitcoin. I think it's not just important for us, I think it's important for the entire ecosystem to have a solid foundation for what I think is this really important technology. So start talking about it. Let's get all of the technologists in Bitcoin, hopefully thinking about this in a more serious way.

Alexandra933  51:10
Awesome. Thanks again.

Transcribed by https://otter.ai