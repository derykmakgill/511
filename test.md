---
layout: post
title: Gavin Andresen quotes
author: Deryk Makgill
---

> The problem people are worried about if the maximum block size is too high:  That big miners with high-bandwidth, high-CPU machines will drive out either small miners or I-want-to-run-a-full-node-at-home people by producing blocks too large for them to download or verify quickly
>
> An adaptive limit could be set so that some minority of miners can 'veto' block size increases; that'd be fine with me.
>
> But it wouldn't help with "I want to be able to run a full node from my home computer / network connection." Does anybody actually care about that? Satoshi didn't, his vision was home users running SPV nodes and full nodes being hosted in datacenters.
>[Re: Bitcoin 20MB Fork](https://bitcointalk.org/index.php?topic=941331.msg10803460#msg10803460)



> Very Bad Things will happen if we get to 100% full 1MB blocks.

https://bitcointalk.org/index.php?topic=941331.msg10801226#msg10801226

> I spent last week talking to some of the largest Bitcoin businesses (much bigger than Paymium/Bitcoin-Central or anything anybody in #bitcoin-assets is involved with), and they all want the maximum block size to increase.

https://bitcointalk.org/index.php?topic=941331.msg10801226#msg10801226

> Why do you want miners to have an incentive to make smaller blocks?
>
>Smaller blocks means fewer transactions, so fewer opportunities to collect fees, so less profit.
>
>Miner profit in fiat currency = number of transactions * average transaction fee * btc-to-fiat exchange rate
>
>Experience (and common sense) says that more usage of Bitcoin means a higher btc-to-fiat exchange rate, so if you want to >maximize miner's fee revenue then increasing the number of transactions is the obvious way to do it.
>
>If you think that putting an artificial cap on the number of transactions will increase overall miner profit, then I urge >you to find a Real Economist and talk to them about the wisdom of trying to use production quotas to keep prices
artificially high.

https://bitcointalk.org/index.php?topic=975447.msg10673166#msg10673166


>There is no tragedy-of-the-commons race to zero transaction fees, because miners do not have infinite bandwidth, memory or >CPU to accept and validate transactions.
>
>Assuming network bandwidth is the eventual bottleneck, and assuming there is demand for transactions to fill the available network-wide bandwidth (even if that demand is transaction spammers), nodes will start dropping transactions before they
relay them. Prioritizing them based on fee paid and dropping the lowest fee/kb transactions will result naturally in a
working market for fee-paying transactions.

https://bitcointalk.org/index.php?topic=956442.msg10493565#msg10493565


>I see one big problem that need solving:
>
>Supporting lots (millions, eventually billions) of people transacting in Bitcoin.
>Ideally at as low a cost as possible, as secure as possible, and in the most decentralized and censorship-resistant way possible.
>
>It is hard to get consensus on HOW to solve that problem, because no solution is obviously lowest cost, most secure, and most decentralized all at the same time, and different people assign different weights to the importance of those three things.
>
>My bias is to "get big fast" -- I think the only way Bitcoin thrives is for lots of people to use it and to be happy using it. If it is a tiny little niche thing then it is much easier for politicians or banks to smother it, paint it as "criminal money", etc. They probably can't kill it, but they sure could make life miserable enough to slow down adoption by a decade or three.
>
>"Get big fast" has been the strategy for a few years now, ever since the project became too famous to fly under the radar of regulators or the mainstream press.
>
>The simplest path to "get big fast" is allowing the chain to grow. All the other solutions take longer or compromise decentralization (e.g. off-chain transactions require one or more semi-trusted entities to validate those off-chain transactions). I'm listening very carefully to anybody who argues that a bigger chain will compromise security, and those concerns are why I am NOT proposing an infinite maximum block size.

https://bitcointalk.org/index.php?topic=941331.msg10492729#msg10492729

I will remind everybody again of Satoshi's second public post where he talked about scalability:

If you didn't do your homework and thought that Bitcoin == 1MB blocks forever, well, that's your fault.

I signed up for a Bitcoin that would scale.

https://bitcointalk.org/index.php?topic=941331.msg10371991#msg10371991

Quote from: davout on February 01, 2015, 09:05:16 PM
What's the problem with paying 10 bucks instead of 10 cents to securely transfer a million dollars?

What's wrong?

Lets say those million dollar transactions are 250 bytes.  That is 4,000 of them in a 1MB block.

So $40,000 total reward to the miner -- about eight times current block reward.

BUT YOU ARE SECURING TRANSACTIONS WORTH SOMETHING LIKE 2,000 TIMES MORE VALUABLE THAN TODAY'S TRANSACTIONS (estimated average transaction USD value for today's average transaction is about $380). And I GUARANTEE that attackers would have a much easier time pulling off a double-spend of one million-dollar transaction than 1,000 $1,000 transactions.

The math for "large value transactions will generate enough fees to secure the chain" just doesn't work.
The math for "lots of small transactions will generate enough fees to secure the chain" might.

https://bitcointalk.org/index.php?topic=941331.msg10330613#msg10330613

When I first heard about Bitcoin, it was small enough I could read everything, and I did, including all of those mailing list posts. The promise of a system that could scale up to rival Visa is part of the vision that sold me on Bitcoin.


https://bitcointalk.org/index.php?topic=941331.msg10315826#msg10315826

Bitcoin.

if y’all are interested in keeping Bitcoin an exclusive little club… then okey dokey, we have a fundamental difference of opinion on where the project should go.

https://bitstein.org/blog/pierre-rochard-and-gavin-andresen-discuss-the-block-size-limit/

with absolutely no artificial limits to supply (like a maximum block size), transaction fees would drop to the marginal cost miners pay for hardware, electricity and bandwidth, plus enough net income to motivate them to keep on mining rather than investing their time and money in something else. Fees would be very small, but not zero.

https://web.archive.org/web/20150214091209/http://blog.bitcoinfoundation.org/blocksize-economics/

If the number of transactions waiting gets large enough, the end result will be an over-saturated network, busy doing nothing productive. I don’t think that is likely– it is more likely people just stop using Bitcoin because transaction confirmation becomes increasingly unreliable.

http://gavinandresen.ninja/why-increasing-the-max-block-size-is-urgent

I believe that if people want a secure network, they will figure out a way of getting it. My justification is the same as my belief that if people want clean, cheap, safe drinking water they will figure out a way of getting it.

I don't claim to know how, and it is very possible the how will offend the sensibilities of either (or both) of the "PRIVACY AT ANY COST!!!!" or "DECENTRALIZATION AT ANY COST!!!!" factions. Just like government regulations and institutions around clean water offend the "INDIVIDUAL LIBERTY AT ANY COST!!!!" faction.

I can imagine a lot of possible futures, from big merchants and exchanges investing in mining to save themselves on transaction fees and ensure that their transactions are confirmed securely, to assurance contracts, to a cartel of miners regulated and funded and licensed as a global public utility.

I hope that last one doesn't happen…
https://bitcointalk.org/index.php?topic=176684.msg9357473#msg9357473

There is a small minority of people who believe that it would be BETTER if transactions moved to fiat currency, an altcoin, or some more-centralized off-blockchain solution. I strongly disagree.
https://bitcointalk.org/index.php?topic=816298.msg9254725#msg9254725


Because network bandwidth, CPU, main memory, and disk storage (the potential bottlenecks) are all growing exponentially right now, and are projected to continue growing exponentially for the next couple decades.

Why would we choose linear growth when the trend is exponential growth?

Unless you think we should artificially limit Bitcoin itself to linear growth for some reason. Exponential growth in number of users and usage is what we want, yes?

https://bitcointalk.org/index.php?topic=815712.msg9203315#msg9203315


I don't believe that even an infinite blocksize would drive fees to zero forever.

Commodity prices never drop to zero, no matter how abundant they are (assuming a reasonably free market-- government can, of course supply "free" goods, but the results are never pretty). The suppliers of the commodities have to make a profit, or they'll find something else to do.

https://bitcointalk.org/index.php?topic=815712.msg9188675#msg9188675

individual miners (or sub-majority cartels) can unilaterally create smaller blocks containing just higher-fee transactions, if they think it is in their long-term interest to put upward pressure on transaction fees.
https://bitcointalk.org/index.php?topic=813324.msg9131431#msg9131431

 raise the block size too slowly and you discourage transactions and increase their price. The danger is Bitcoin becomes irrelevant for anything besides huge transactions, and is used only by big corporations and is too expensive for individuals. Hurray, we just reinvented the SWIFT or ACH systems.
https://bitcointalk.org/index.php?topic=813324.msg9106557#msg9106557


I am much more worried about transaction fees right now than "selfish mining".
https://bitcointalk.org/index.php?topic=324972.msg3514227#msg3514227

D

miners have a natural incentive to want to be closely connected to as many other miners as possible (to reduce orphan costs).
https://bitcointalk.org/index.php?topic=324413.msg3477481#msg3477481

DConsensus is the block size limit will have to rise.

Us geeks were/will/are arguing over how and when, not if...
https://bitcointalk.org/index.php?topic=322748.msg3455719#msg3455719

D

That seems plausible to me-- set an arbitrary constraint ("bids must be in multiples of a tenth of a penny" -- or whatever it is these days) and you often get unintended consequences.

I still plan on writing up why I disagree with the idea that a larger block size will lead to centralization, but I'm working on some higher priority things first. I really don't understand why you would think that our current, arbitrary 1MB limit is the Best Size For All Time. I think that arbitrary constraint will have bad unintended consequences.
https://bitcointalk.org/index.php?topic=288298.msg3111910#msg3111910

'Yes, let's eliminate the limit.

Nothing bad will happen if we do.

And if I'm wrong, the bad things would be mild annoyances, not existential risks, much less risky than operating a network near 100% capacity.'https://np.reddit.com/r/btc/comments/4oadyh/i_believe_the_network_will_eventually_have_so/d4bggvk/

DIf you mean "Peter Todd has convinced some big mining pool operators not to increase the size of the blocks they create" -- then great!  That's the free market at work, big mining pools should be free to create blocks that are as large or as small as they like, and to accept or reject other's blocks for whatever reason they like.https://bitcointalk.org/index.php?topic=221111.msg2360913#msg2360913

The block size will be raised, that is the overwhelming consensus among the people who are actually writing code and using Bitcoin for products and services that it needs to happen.

And there is a tiny minority of people who will loudly proclaim that isn't true and that the core developer are going to destroy Bitcoin if the block size is raised.
https://bitcointalk.org/index.php?topic=221111.msg2359724#msg2359724

central planning is why I would like to eliminate the hard, upper blocksize limit entirely, and let the network decide "how big is too big."

RE: "the plan"  :   The plan from the beginning was to support huge blocks.  The 1MB hard limit was always a temporary denial-of-service prevention measure.
D

"small mining pools will go out of business" -- give me a break! My back-of-the-envelope calculations say that anybody willing to spend a few hundred dollars a year on a dedicated server with a high-bandwidth connection can support a MUCH, MUCH larger block size.https://bitcointalk.org/index.php?topic=189792.msg1967890#msg1967890

DWe can speculate all we want about what is going to happen in the future, but we don't really know.

So, what should we do if we don't know? My default answer is "do the simplest thing that could possibly work, but make sure there is a Plan B just in case it doesn't work."

In the case of the block size debate, what is the simplest thing that just might possibly work?

That's easy!  Eliminate the block size limit as a network rule entirely, and trust that miners and merchants and users will reject blocks that are "obviously too big." Where what is "obviously too big" will change over time as technology changes.https://bitcointalk.org/index.php?topic=157141.msg1758131#msg1758131

D
Nothing stops a merchant who wants more network security from either subsidizing miners (maybe in exchange for a promise to prioritize transactions to them) or mining themselves.https://bitcointalk.org/index.php?topic=167646.msg1745634#msg1745634

D

If you think that the block size should stay at 1 megabyte forever, then you're saying the network will never support more than 7 transactions per second, and each transaction will need to be for a fairly large number of bitcoins (otherwise transaction fees will eat up the value of the transaction).

If transactions are all pretty big, why the heck do we have 8 decimal places for the transaction amount?

Don't get me wrong, I still think the bitcoin network is the wrong solution for sub-US-penny payments. But I see no reason why it can't continue to work well for small-amount (between a US $1 and $0.01) payments.https://bitcointalk.org/index.php?topic=144895.msg1539692#msg1539692


DI start from "more transactions == more success"

I strongly feel that we shouldn't aim for Bitcoin topping out as a "high power money" system that can process only 7 transactions per second.

I agree with Stephen Pair-- THAT would be a highly centralized system.

Oh, sure, mining might be decentralized.  But who cares if you either have to be a gazillionaire to participate directly on the network as an ordinary transaction-creating customer, or have to have your transactions processed via some centralized, trusted, off-the-chain transaction processing service?https://bitcointalk.org/index.php?topic=144895.msg1537055#msg1537055

For the record:

I'm on the "let there be no fixed maximum block size" side of the debate right now.

I think we should let miners decide on the maximum size of blocks that they'll build on.
https://bitcointalk.org/index.php?topic=140233.msg1496306#msg1496306 
Once upon a time bitcoin.org called Bitcoin "anonymous" but that was a mistake, and for at least two years "we" (core developers) have tried to be careful to say that, at best, Bitcoin is pseudanonymous.

I tell reporters that Bitcoin is more private than using any other online payment method, but less private than cash (unless you know a lot about how it works under the covers and jump through several hoops to keep your identity secret).
https://bitcointalk.org/index.php?topic=87045.msg956238#msg956238

The Bitcoin ecosystem consists of more that just miners, and even if miners decided to try to form a cabal to increase inflation merchants, users, and exchanges could all veto their block-chain by simply refusing to recognize it.https://bitcointalk.org/index.php?topic=67739.msg848210#msg848210

D
