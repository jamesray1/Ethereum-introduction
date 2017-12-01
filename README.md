# Ethereum introduction

<!--Note that you can edit this document visually instead of in HTML e.g. in a Wordpress draft post-->
Note that due to the lightning-fast pace of development in the Ethereum space, certain parts of this article may be outdated.

<a href="https://www.ethereum.org/" target="_blank" rel="nofollow noopener noreferrer">Ethereum</a> is a decentralized blockchain platform for "building unstoppable applications", while Ether is the cryptocurrency used on this platform. Ethereum has been described in several ways, such as:
<ul>
	<li><a href="https://github.com/ethereum/wiki/wiki/White-Paper" target="_blank" rel="noopener">"A Next-Generation Smart Contract and Decentralized Application Platform"—Ethereum White Paper</a></li>
	<li><a href="https://ethereum.github.io/yellowpaper/paper.pdf" target="_blank" rel="noopener">"A secure decentralised generalised transaction ledger" and a generalised "transactional singleton machine with shared-state". Also described as crypto-law—Ethereum Yellow Paper</a></li>
	<li><a href="http://ethdocs.org/en/latest/introduction/what-is-ethereum.html" target="_blank" rel="noopener">an open source "programmable blockchain"—Ethdocs</a></li>
</ul>
Let's briefly breakdown what those terms mean, or at at least my understanding of them.

Decentralized technology is not subject to the whims of a central authority such as a government or server administrator (like Google or Facebook) which can help to achieve better decision making for public good. Blockchain means that the currency is built and secured by adding and verifying blocks of transactions to blocks made previously, thus forming a "chain". Blocks added to the chain become harder and harder to crack over time, as they are verified by more nodes in the blockchain <a href="https://en.wikipedia.org/wiki/Peer-to-peer" target="_blank" rel="noopener">peer-to-peer network</a>. Blockchain technology has been referred to as the Web 3.0. The world wide web (retroactively the Web 1.0) consisted of websites publishing content and users passively reading/viewing it. The Web 2.0 used user interaction, such as forums (with upvoting and commenting), reaction buttons (e.g. the Facebook reactions: likes 👍, love ❤️ , laughter 😆, wow 😲, sad 😢, angry 😠), sharing (republishing). The Web 3.0 is starting to be defined as the movement away from centralisation of computation power in servers which provide services to clients (known as the <a href="https://en.wikipedia.org/wiki/Client%E2%80%93server_model" target="_blank" rel="noopener">client-server network model</a>) to peer-to-peer networks and blockchains, and <a href="https://github.com/DemocracyEarth/paper/blob/master/README.mediawiki" target="_blank" rel="noopener">from centralisation of authority and sovereignty from nation-states and corporations to the networked individual</a>.

Cryptocurrency refers to cryptographic code used to secure transactions with a digital currency, which is solved through hardware computational power (known as mining or proof of work) or other less energy-intensive ways such as proof-of-stake. (There are more details on that below.) Zero knowledge proofs like <a href="https://crypto.stackexchange.com/questions/19884/what-are-snarks" target="_blank" rel="noopener">ZK SNARKS</a> can also be used to make cryptocurrency transactions more private 🕵️ or secret 🤐 (which is different to being secure 🔒), such as the Zerocoin protocol which is demonstrated by <a href="https://zcoin.io/" target="_blank" rel="nofollow noopener noreferrer">Zcoin</a> (which plans to integrate Ethereum).

The platform part of Ethereum makes it much more useful than just a cryptocurrency. With it, you can create any decentralized application (known as a dapp, which works over a peer-to- peer network rather than a centralized client-server network 💻🕸️), so the functionality is only limited by what programs could potentially do and not do, and by consequence, what programmers develop. 👨‍💻

 

[gallery ids="4126,4127" type="rectangular"]

Any asset can be tokenized with Ethereum. The token represents the app while it uses the Ethereum blockchain, but the price of the token is different. Activity that has any economic or governance aspect, conceived or as of yet inconceived, can be done via Ethereum, provided that the right code is written and the necessary hardware is used (such as computers running an Ethereum node, and in some special cases, a measurement device to measure a resource flow for additional verification/auditable purposes, like a meter for electricity ⚡🔌, water 🚰 or gas 🔥; or a waste 🗑️ volume detector). Here's a challenge: keep an eye out for activity that has not been implemented on Ethereum (or could be implemented in a better way) and then:
<ul>
	<li>develop a dapp for the idea yourself (after learning <a href="https://solidity.readthedocs.io/en/develop/" target="_blank" rel="noopener">Solidity</a>, if you don't already know it); or</li>
	<li>sign an NDA with someone who is interested in developing dapps, share the idea, and form some agreement if they want to proceed with it (which could be proposed in the NDA itself), e.g. a founder's stake in an ICO, a salary, equity in the venture (although I think a community model more like Ethereum's non-profit foundation, is better for a more equitable solution), royalties, a fee for every transaction, etc.</li>
</ul>
I have come up with some ideas 💡 myself. 😉

This platform aspect of Ethereum has been referred to as a 'fat protocol' <a href="http://www.usv.com/blog/fat-protocols" target="_blank" rel="noopener">here</a>, as opposed to the 'thin protocols' of Web 1.0 and 2.0 with HTTP, SMTP, etc., with the take home point (in bold) being:
<blockquote><strong>the market cap of the protocol always</strong> <strong>grows faster than the combined value of the applications built on top, since the success of the application layer drives further speculation at the protocol layer.</strong></blockquote>
One kind of application that is particularly intriguing is decentralized autononous organisations (DAOs, this includes entities as large as, or even larger than nation-states 🇦🇺🇺🇸🇮🇳🇬🇧🇨🇳🇧🇷🇷🇺🇯🇵, social networks, multinational public companies, etc.). Note that having complete autonomy is probably not a good idea, since code may not be able to handle new issues that arise, so human intervention should probably always be an option, but preferably in the hands of a small, non-profit entity or some decentralized solution (perhaps similar to the <a href="https://aragon.one/network/" target="_blank" rel="noopener">Aragon Network</a>). By analogy, you wouldn't want a nuclear power plant to be completely automated with no possible means of human intervention. As a precaution, you'd want several safeguards including, for example, an off button 😉. As explained in this Ethereum Wiki <a href="https://en.wikipedia.org/wiki/Ethereum" target="_blank" rel="noopener">here</a>, the first DAO, known as The DAO, resulted in many funds being stolen, and Ethereum hard forking into Ethereum and Ethereum Classic.

Other examples that have been implemented, or are under development, or have been publicly conceptualised include:
<ul>
	<li>storage, e.g. <a href="https://github.com/ethersphere/swarm" target="_blank" rel="noopener">Swarm</a>;</li>
	<li>communication protocols, e.g. <a href="https://github.com/ethereum/wiki/wiki/Whisper" target="_blank" rel="noopener">Whisper</a> (also see <a href="https://github.com/ethereum/wiki/wiki/Whisper-Overview" target="_blank" rel="noopener">here</a> for code), which allows dapps (I don't capitalize this since it is an abbreviation of decentralized applications) to communicate with each other.;</li>
	<li><a href="https://ens.domains/" target="_blank" rel="noopener">Ethereum Name Service</a> (names like <a href="https://etherscan.io/enslookup?q=jamesray.eth" target="_blank" rel="noopener">jamesray.eth</a> map to an address)</li>
	<li><a href="http://mesh networking" target="_blank" rel="noopener">mesh networking</a> e.g. implemented <a href="http://altheamesh.com/">here</a> and as voted for <a href="https://twitter.com/VitalikButerin/status/933273431469993987">here</a> on Twitter (which also has other ideas posted in the comments);</li>
	<li>social networks e.g. <a href="https://akasha.world/" target="_blank" rel="noopener">Akasha</a> (news <a href="https://www.cryptocoinsnews.com/can-ethereum-based-akasha-revolutionize-social-networks/" target="_blank" rel="noopener">here</a>),</li>
	<li><a href="https://status.im/" target="_blank" rel="noopener">Status</a>: "A Mobile Ethereum OS: Browse, chat and make payments securely on the decentralized web.";</li>
	<li>decentralized search engines, e.g. <a href="https://www.weipoint.com/" target="_blank" rel="noopener">Weipoint</a> (a news post is <a href="https://www.cryptocoinsnews.com/now-ethereum-search-engine-decentralized-web/" target="_blank" rel="noopener">here</a>);</li>
	<li>reputation, ratings, identity (e.g. as provided by <a href="https://www.uport.me/" target="_blank" rel="noopener">uPort</a>), etc.;</li>
	<li>decentralized electricity trading and other decentralized energy economic applications, which would allow renewable energy to be more economical and accelerate the transition to a clean, renewable energy and safe climate future, and is something that I have a particular interest in due to my background in renewable energy.
<span class="emoji"><img src="https://emojipedia-us.s3.amazonaws.com/thumbs/120/twitter/103/black-sun-with-rays_2600.png" alt="Sun on Twitter Twemoji 2.3" width="120" height="120" /><img src="https://emojipedia-us.s3.amazonaws.com/thumbs/120/twitter/103/wind-blowing-face_1f32c.png" alt="Wind Face on Twitter Twemoji 2.3" width="120" height="120" /><img src="https://emojipedia-us.s3.amazonaws.com/thumbs/120/twitter/103/deciduous-tree_1f333.png" alt="Deciduous Tree on Twitter Twemoji 2.3" width="120" height="120" /><img src="https://emojipedia-us.s3.amazonaws.com/thumbs/120/twitter/103/water-wave_1f30a.png" alt="Water Wave on Twitter Twemoji 2.3" width="120" height="120" /></span>
Examples of<strong> local electricity trading</strong> include: <a href="https://gridplus.io/" target="_blank" rel="noopener">Grid+</a>, <a href="http://lo3energy.com/" target="_blank" rel="noopener">LO3</a>/<a href="http://lo3energy.com/transactive-grid/" target="_blank" rel="noopener">Transactive Grid</a>, <a href="https://powerledger.io/" target="_blank" rel="noopener">Power Ledger</a>, <a href="http://www.nexergy.co/" target="_blank" rel="noopener">Nexergy</a>, <a href="https://localvolts.com/" target="_blank" rel="noopener">Local Volts</a> and <a href="https://divvi.xyz" target="_blank" rel="noopener">Divvi</a>. Grid+ uses Ethereum and <a href="https://github.com/gridplus" target="_blank" rel="noopener">they have open source code</a>. Power Ledger has closed source code and runs on the Ethereum Enterprise Alliance, rather than the public Ethereum blockchain. <a href="https://twitter.com/PowerLedger_io/status/916792824623923201" target="_blank" rel="noopener">They had a token sale in early October</a>. <a href="https://www.newscientist.com/article/2079334-blockchain-based-microgrid-gives-power-to-consumers-in-new-york/" target="_blank" rel="noopener">Transactive Grid uses Ethereum</a> and it has been rolled out in <a href="http://brooklynmicrogrid.com/" target="_blank" rel="noopener">Brooklyn with a microgrid</a>, however LO3 hasn't released any code or details for its Transactive Grid application. The others are still all under development (as of the last time I checked in August), and they have been scant on the details of how they would implement their application, at the least not releasing their code. Divvi say on its website that they will use the blockchain. Local Volts and Nexergy do not.</li>
	<li>electricity tokenization: e.g. <a href="https://solarcoin.org/en/front-page/" target="_blank" rel="noopener">SolarCoin</a>, <a href="https://energycoin.eu/" target="_blank" rel="noopener">EnergyCoin</a>, although both are altcoins rather than Ethereum tokens;</li>
	<li>governance of any organisation, e.g. <a href="http://Democracy.Earth" target="_blank" rel="noopener">Democracy.Earth</a>; and also governance of DAOs, e.g. <a href="https://aragon.one/network/" target="_blank" rel="noopener">Aragon</a>;</li>
	<li>the <a href="https://brave.com/" target="_blank" rel="noopener">Brave browser</a> (which I use) which uses the <a href="https://basicattentiontoken.org/">Basic Attention Token</a>, which provides a better solution for users, publishers and advertisers;</li>
	<li>wallets like <a href="https://www.myetherwallet.com/" target="_blank" rel="noopener">MyEtherWallet</a> or hardware wallets <a href="https://trezor.io/" target="_blank" rel="noopener">Trezor</a> or <a href="https://ledger.zendesk.com/hc/en-us" target="_blank" rel="noopener">Ledger</a>;</li>
	<li>decentralized exchanges to buy and sell cryptos and fiat, e.g. <a href="https://localethereum.com" target="_blank" rel="noopener">localethereum</a>; for cryptos only there is <a href="https://decentrex.com/" target="_blank" rel="noopener">Decentrex</a>, <a href="https://omega.one/" target="_blank" rel="noopener">Omega One</a> and <a href="http://nvo.io" target="_blank" rel="noopener">NVO</a>, where the latter two have not been launched as of November 30.</li>
	<li>non-decentralized exchanges such as Coinbase (US) and BTCmarkets (Australia), while more are below, or ones that only exchange cryptos like <a href="https://www.poloniex.com/" target="_blank" rel="noopener">Poloniex</a>,</li>
	<li>decentralized media;</li>
	<li>asset titles (such as land titles). Read more on that <a href="https://www.forbes.com/sites/laurashin/2017/02/07/the-first-government-to-secure-land-titles-on-the-bitcoin-blockchain-expands-project/#11558e984dcd" target="_blank" rel="noopener">here</a>:
<blockquote>Having so far built the software and tested it with a couple dozen land title registrations, Bitfury and the Georgian National Agency of Public Registry have now signed a new memorandum of understanding to expand the service to purchases and sales of land titles, registration of new land titles, demolition of property, mortgages and rentals, as well as notary services;</blockquote>
</li>
	<li>debit card 💳 transactions 🤝 (done on several exchanges 💱, e.g. <a href="https://www.coinjar.com.au/" target="_blank" rel="noopener">Coinjar Swipe</a>)</li>
	<li>crowdsales, e.g. an <a href="https://en.wikipedia.org/wiki/Initial_coin_offering" target="_blank" rel="noopener">Initial Coin Offering (ICO)</a> as compared with an <a href="https://en.wikipedia.org/wiki/Initial_public_offering" target="_blank" rel="noopener">Intial Public Offering (IPO)</a>, or for tokens with Ethereum: an Initial Token Offering (ITO). Note that this is not so much a business model in itself, per se, rather it is more of a fundraising method (which has also led to scams, e.g. <a href="https://motherboard.vice.com/en_us/article/j5j34x/ethereum-startup-confido-vanished-after-people-invested-374k-ico" target="_blank" rel="noopener">here</a>);</li>
	<li>crowd development (but not as part of the blockchain, e.g. <a href="http://developmentcrowd.com/" target="_blank" rel="noopener">here</a>), e.g. for infrastructure and other public assets;</li>
	<li>think of public companies being remodelled into communities with tokens instead of shares, governance using a platform like <a href="http://Democracy.Earth" target="_blank" rel="noopener">Democracy.Earth</a> (which can be tailored to have voting anywhere between one vote one person like direct democracy, or conventionally more hierarchical like a board of directors and tokenholders instead of or in addition to—and probably eventually superceding—shareholders),</li>
	<li>prediction 🔮 🦉 markets like <a href="https://gnosis.pm/" target="_blank" rel="noopener">GNOSIS</a> or <a href="https://augur.net/" target="_blank" rel="noopener">Augur</a>;</li>
	<li>labour/recruitment/freelance markets like <a href="http://blockchain-finance.com/2017/01/20/blockchain-solution-for-recruitment-sector/" target="_blank" rel="noopener">Chronobank</a>;</li>
	<li>Secure distributed computing, e.g. <a href="https://golem.network/" target="_blank" rel="noopener">Golem</a>. Ethereum needs to be faster e.g. with <a href="https://github.com/ewasm/design" target="_blank" rel="noopener">EWASM</a> and parallelizability.</li>
	<li>games like <a href="https://www.cryptokitties.co/" target="_blank" rel="noopener">CryptoKitties</a> (I'm not a fan of games, I prefer to meditate for leisure time),</li>
	<li>accountability, e.g. for <a href="https://bitcoinist.com/bitgive-addresses-non-profit-accountability-bitcoin-technology/" target="_blank" rel="noopener">non-profits</a> (e.g. how do I know how badly you need a donation unless I can see your net liabilities, net assets, and balance sheet, and how you plan to use the funds) and <a href="https://www.ethnews.com/united-nations-world-food-programme-uses-ethereum-to-aid-syrian-refugees" target="_blank" rel="noopener">aid</a> (also see <a href="https://cointelegraph.com/news/ethereum-blockchain-used-by-united-nations-for-sending-aid-to-syria" target="_blank" rel="noopener">here</a>)</li>
	<li>Self Learning, Autonomous, Decentralized Artificial Intelligence (this could be used for many things such as self-driving cars, robots, or anything else that is owned by a contract; bots; and art);</li>
	<li>too many to list and keep up-to-date here, so click <a href="https://dapps.ethercasts.com/" target="_blank" rel="noopener">here</a> instead to go to State of the Dapps for more! Other examples are also mentioned in the Ethereum whitepaper in the <a href="https://github.com/ethereum/wiki/wiki/White-Paper#a-next-generation-smart-contract-and-decentralized-application-platform" target="_blank" rel="noopener">introduction</a> and <a href="https://github.com/ethereum/wiki/wiki/White-Paper#applications" target="_blank" rel="noopener">applications section</a>. Other ones that look particularly useful include <a href="https://omega.one/" target="_blank" rel="noopener">Omega One</a>.</li>
</ul>
Examples that have been conceptualized, but not implemented (at least as far as I am aware of) include:
<ul>
	<li>reducing transaction costs for existing business models (<a href="https://bravenewcoin.com/news/tokenize-the-enterprise-and-melt-it-into-the-community-rinse-repeat/" target="_blank" rel="noopener">here</a> is a good read about that). However, to tokenize online centric business models like Facebook, Amazon, Google, etc., the network model should change from client-server to peer-to-peer, to avoid a conflict of interest. This is more difficult to achieve since a server is a piece of infrastructure, and transferring to a peer-to-peer model would cause it to be a sunk cost.</li>
	<li>making economically viable other business models that have seen low uptake or aren't economically viable without blockchain tech. So called sharing economy business models like Airbnb and AirTasker are particularly ripe for transformation (I prefer the term transformation to disruption, since it should be a positive change), since no trusted third party for a transaction is needed, such as banks 🏦, credit card 💳 companies or PayPal, just a smart contract; and</li>
	<li>More examples are <a href="https://medium.com/startup-grind/jack-the-giant-joint-stock-pepe-the-history-future-of-the-corporation-f17d30aff411" target="_blank" rel="noopener">here</a>—scroll to the examples—they have bold headings and are about two thirds of the way down, or search for "Dank meme trading". Note that I have already mentioned the Basic Attention Token, and I am skeptical that AI will create truly beautiful art, since no AI can have any feeling.</li>
</ul>
As of the 5th of June 2017, the market capitalisation of Ethereum is $22.9 billion USD [1], and has been in circulation possibly since 30 July 2015 (although I have not been able to verify this date), with the first transaction using Ethereum on 8 August 2015 [2]. Compare this with the next largest and the current largest cryptocurrency, Bitcoin, with a market cap of $41.0 b. US [1], and has been in circulation since January 2009 [3]. Technically, Ethereum has had a much faster growth rate, while more importantly for long term investment (I do not encourage speculation as that only causes volatility as has been seen) the fundamentals are much better than Bitcoin. While it is true that Bitcoin has more of a market and currency, e.g. in terms of more entities that will accept it as a form of payment, I expect that time will change that (indeed the <a href="https://seekingalpha.com/article/4077679-ethereum-blasts-20-billion-market-cap-half-bitcoin" target="_blank" rel="noopener">market cap of Ethereum recently surpassed half that of Bitcoin, around May 2017</a>).
<h2>Issues</h2>
There also several issues with Ethereum, such as not being scalable enough, not being full decentralized, energy consumption with mining, if quantum computing advances it would be insecure (but this is being fixed), and privacy. As of Ethereum Homestead in October 2017, it can only process about 25 transactions per second, but it will need to process millions or billions of transactions per second to become a "<a href="https://www.youtube.com/watch?v=j23HnORQXvs" target="_blank" rel="noopener">world computer</a>". With its large storage database, mining and architecture requiring to run a full node to mine or validate transactions, it is not decentralized enough. Note that for privacy, Ethereum <a href="https://blog.ethereum.org/2017/01/19/update-integrating-zcash-ethereum/">integrated Zcash</a> and Zero Knowledge SNARKs on its test network, successfully completing a transaction on its test network with Zcash in late December 2016 or early January 2017.
<h3>Proof of work / proof of stake / other proving methods</h3>
The mining process to crack cryptographic code (specifically to discover the nonce, a very large number, for each block by trial and error) requires a lot of computation power. Nevertheless, I'm guessing that the computation power should be less when you consider the <strong>energy consumption</strong> of incumbent financial systems. (Think of extracting and processing resources to make coins and notes, minting and printing, energy consumption of banks and tiers of related energy consumption in the life cycle of fiat money.) Still, developers of some cryptocurrencies such as Ethereum are transitioning to (as is the case for Ethereum), or already using, a different way of maintaining and creating blocks, known as proof of stake. For more information, you can see this Proof of Stake Wikipedia article <a href="https://en.wikipedia.org/wiki/Proof-of-stake" target="_blank" rel="nofollow noopener noreferrer">here</a> (although note the header warning about the article potentially not being verifiable or neutral due to relying heavily on sources too closely associated to the subject). The tricky part is in getting proof methods to work better than proof of work, as outlined <a href="https://en.wikipedia.org/wiki/Proof-of-stake" target="_blank" rel="noopener">here</a> in the criticism section of the PoS Wiki.

Running on top of the public Ethereum blockchain (with a token) is better than using a private blockchain, or worse, not running on a blockchain at all (thus requiring a trusted third party which increases transaction costs). Running on the public Ethereum blockchain is more secure than a private chain, since the public chain is much longer and has many nodes mining and verifying it. A private chain is more prone to different kinds of attacks, particularly a <a href="https://learncryptography.com/cryptocurrency/51-attack" target="_blank" rel="noopener">51% attack</a>. Having open-source code is important to verify the security and performance of the software, as well as being able to innovate, e.g. with enhancements.

Disclaimer: I have put most of my funds in Ether, the currency of Ethereum. Does that shock you? 😲 Yep, it's risky, but I've done due diligence 🔍 with fundamental analysis, and a little bit of sentiment and technical analysis, and I think that the market cap of Ether will continue to grow 🌱🌳 and increase, albeit with some volatility 📈. I consider it a digital currency that is in a pioneering, rapid growth stage of development (fuelled by a lot of genuine uptake of the currency as well as speculation about its future value, if not its current value), not just an asset. I hope my post will outline why investing in Ether is a good idea (and not just investing a small percentage of your cash, unless you are tied up with a mortgage 🏠 or have other monetary or non-monetary ties or circumstances that limit your investable capital).

 
<h2>How do you buy Ether, the currency of Ethereum?</h2>
Based on my research below, <strong>if you're in Australia</strong> 🇦🇺 (otherwise skip to the next paragraph), I recommend creating an account with BTCmarkets.net, verifying your ID, setting up a bank account with BOQ (or <a href="https://www.polipayments.com/Banks" target="_blank" rel="noopener">any other bank that supports POLi Payments</a>, <a href="https://www.marketforces.org.au/banks/compare" target="_blank" rel="noopener">doesn't invest in fossil fuels</a> and <a href="https://www.choice.com.au/money/banking/savings-options/articles/top-fee-free-bank-accounts" target="_blank" rel="noopener">has no fees for transaction and savings accounts</a> [note that Bendigo doesn't have an Ultimate Everyday account any more]. You can probably ignore the interest rate since it is so marginal compared to other bank's rates and the gains that you are likely to make by holding funds with Ether instead. However, when I did research for interest rates I found that ME Bank savings rates were second only to UBank, which invests in fossil fuels indirectly as it is owned by NAB. However, as I note below, ME doesn't support POLi Payments), depositing AUD, then buying Ether.

<strong>If you're not in Australia 🇦🇺</strong>, then here's a comparison of exchange rates 💱 for fiat to crypto- and crypto- to crypto- currencies (not that there is still a focus on Australia, but you can click on the links to get more information of the fees):
<table border="1" width="643" cellspacing="0" cellpadding="4"><colgroup> <col width="314" /> <col width="311" /> </colgroup>
<tbody>
<tr valign="TOP">
<td width="314"> Exchange link (may go to a fees page)</td>
<td width="311">Fiat to crypto exchange fee buy/sell spread</td>
</tr>
<tr valign="TOP">
<td width="314" height="10"><a href="https://btcmarkets.net/fees" target="_blank" rel="noopener">BTCmarkets</a></td>
<td width="311">AUD is the only fiat currency. 0.85% trading fee. Funds available to deposit, withdraw, buy and sell are: AUD, ETH, ETC, BTC and LTC. To deposit AUD, you need to verify your account and then use POLi Payments (available banks are <a href="https://www.polipayments.com/Banks" target="_blank" rel="noopener">here</a>. My bank is ME Bank, which doesn't support POLi Payments. I applied with BOQ because they do support POLi Payments, they <a href="https://www.marketforces.org.au/banks/compare" target="_blank" rel="noopener">don't invest in fossil fuels</a> [like ME Bank] and they have <a href="http://www.boq.com.au/day2day.htm" target="_blank" rel="noopener">transaction and savings accounts with no fees</a> [like ME Bank].)</td>
</tr>
<tr valign="TOP">
<td width="314" height="10"><a href="http://gdax.com/fees/" target="_blank" rel="noopener">GDAX</a></td>
<td width="311">0.25/.3% maker fee low volume, 0% taker fee BTC for USD/EUR/GBP, ETH/LTC for USD/BTC/EUR</td>
</tr>
<tr valign="TOP">
<td width="314" height="10"><a href="https://www.coinjar.com.au/">Coinjar</a></td>
<td width="311">1.00% AUD/BTC (and only AUD/BTC)</td>
</tr>
<tr valign="TOP">
<td width="314" height="10"><a href="https://support.coinbase.com/customer/en/portal/articles/2109597">Coinbase</a></td>
<td width="311">In Aus: 3.99% credit/debit card only (no other transaction method accepted). Other fiat and crypto currencies are available.</td>
</tr>
<tr valign="TOP">
<td width="314"><a href="https://cex.io/" target="_blank" rel="noopener">CEX</a></td>
<td width="311">7% BTC/ETH for USD/EUR/GBP/RUB</td>
</tr>
<tr valign="TOP">
<td width="314"><a href="https://ice3x.com/" target="_blank" rel="noopener">ice3x</a></td>
<td width="311">1% ZAR/BTC</td>
</tr>
<tr valign="TOP">
<td width="314"><a href="https://www.luno.com/trade/XBTZAR" target="_blank" rel="noopener">Luno</a></td>
<td width="311">ZAR/BTC fee not easy to find</td>
</tr>
<tr valign="TOP">
<td width="314"><a href="https://www.okcoin.cn/" target="_blank" rel="noopener">okcoin</a></td>
<td width="311">CNY/USD for BTC/LTC, fee not easy to find</td>
</tr>
<tr valign="TOP">
<td width="314"><a href="https://www.maicoin.com/">Maicoin</a></td>
<td width="311">TN/BTC Fee not shown, claimed none</td>
</tr>
</tbody>
</table>
<table border="1" width="100%" cellspacing="0" cellpadding="4"><colgroup> <col width="128*" /> <col width="128*" /> </colgroup>
<tbody>
<tr valign="TOP">
<td width="50%"></td>
<td width="50%">Crypto to crypto exchange fee / buy/sell spread</td>
</tr>
<tr valign="TOP">
<td width="50%" height="21"><a href="https://poloniex.com/">Poloniex</a></td>
<td width="50%">0.15/.25% BTC/ETH “maker-taker” (presumably the same as buy-sell)</td>
</tr>
<tr valign="TOP">
<td width="50%"><a href="http://gdax.com/fees/">gdax.com/fees/</a></td>
<td width="50%">0.25/.3% maker fee low volume, 0% taker fee ETH/LTC for BTC</td>
</tr>
<tr valign="TOP">
<td width="50%"><a href="https://www.exodus.io/">Exodus</a></td>
<td width="50%">~0.4720–.528% BTC/ETH variable. Desktop app. Sometimes currencies are not available for exchange!</td>
</tr>
<tr valign="TOP">
<td width="50%"><a href="https://nvo.io/">NVO</a></td>
<td width="50%">Decentralised. ICO 05/27/17 02:00 UTC to 06/27/17 02:00 UTC</td>
</tr>
</tbody>
</table>
<h3>More details about what I've tried (not very necessary to know)</h3>
I bought BTC in a different way. Step 2 worked for me. I will try step 1 next time I buy more BTC.

I created an account on btcmarkets.net, verified my email address, tried to login, but couldn't. I tried to disable two factor authentication, but it asked for my mobile number, which I didn't enter when I created my account. I tried to reset my password and log in again, but that didn't work. I entered my email address correctly. I sent a message to support to ask for help. I figured out that my password was too long, and have notified btcmarkets.net. After creating a password of 23 characters, I was able to log in. I created another password of 56 characters using Chinese characters, emojis and ASCII characters, and was able to log in. (Incidentally, it is a hassle to do this, so a decentralised, private password generator would be wonderful.)

The following steps are what I have tried so far, in detail.
<ol>
	<li>Convert AUD to Bitcoin (BTC) via an exchange like <a href="https://www.coinjar.com/" target="_blank" rel="nofollow noopener noreferrer">Coinjar</a>. I left a review of Coinjar <a href="https://au.trustpilot.com/reviews/59391a3d20b79f0b9c73a629" target="_blank" rel="noopener">here</a>. Fee: 1%. While this step is tailored for Australia, it can be adapted to any country that has a bitcoin exchange.</li>
	<li>I created a <a href="https://poloniex.com/" target="_blank" rel="noopener">Poloniex</a> account, sent funds from got the Bitcoin deposit address, then sent my BitGo funds to that address. Once the transaction completed, I then used Poloniex Exchange to convert to Eth, with a maker-taker fee of: <a class="standard" href="https://poloniex.com/feeTier"><span class="makerFee">0.15</span>/<span class="takerFee">0.25</span>%</a>.</li>
</ol>
Before step 2 above, I tried the following:
<ol>
	<li>Create an Ethereum Wallet 👛 like <a href="https://www.myetherwallet.com/" target="_blank" rel="nofollow noopener noreferrer">MyEtherWallet</a>. Unfortunately <a href="https://github.com/ethereum/mist" target="_blank" rel="noopener">Mist</a>, a program being developed by Ethereum that has a browser and a wallet is <a href="https://github.com/ethereum/mist/releases" target="_blank" rel="noopener">still a pre-release</a>, so it may not be very suitable for end users just yet.</li>
	<li>Convert BTC to Ether (ETH) via a cryptocurrency exchange like <a href="https://shapeshift.io/" target="_blank" rel="nofollow noopener noreferrer">Shapeshift</a>. Use a precise transaction, make sure the amount is within the min. and max. deposit. Copy and paste the bitcoin address in Coinjar by signing in (if you aren't already) and going to Accounts > Everyday Bitcoin > View address. Put this address as the refundable address. Copy and paste the address from <a href="https://www.myetherwallet.com/" target="_blank" rel="nofollow noopener noreferrer">MyEtherWallet</a>. Put this as the destination address. Tick the box to save the destination address for future payments. However, this didn't work.</li>
</ol>
I also sent an email to Coinjar to suggest that they develop functionality for purchasing Ether directly using AUD. You can do the same with the exchange of your choice.

I have been able to deposit funds into Coinjar (needing to be less than the transaction limits) but have not been able to get Eth funds as of yet. I have also tried to create an account on BitGo, send coins from Coinjar to BitGo, and use Shapeshift with that account and still with MyEtherWallet, however that didn't work.

I will not discuss trading (which I mean buying with the intention to sell most or all of the purchase at any future time particularly in the short term in order to realize a profit) as I am not very interested in trying to guess the short-term direction of markets (although I admit that trading helps to provide liquidity).
<h2>Concluding remarks</h2>
Ether certainly seems like a good investment, and a good alternative to using fiat currencies, as well as an enabler for otherwise uneconomical business, due to lower transaction costs. It's more decentralized nature than central banks has advantages for trade from a local to global scale. With governance applications and systems on top Ethereum, it is even possible to do away with the hindering borders surmounted by nation-states. By doing away with these borders, society can be more open, inclusive and equitable.

However, I should note that all technology can only help mankind and the world to a certain extent. What is more important is for each and every person to become a more peaceful, blissful, God-attuned being. It is often seen in the business world or with many people that God is put aside, ignored, or shunned, or at least to some extent. This is mainly due to ignorance of the profound benefits that come from living a Godly life (or at least making an effort to live such a life). That being said, technological advancement can certainly be beneficial to mankind, but it needs to be coupled with moral and spiritual living, otherwise there will still be suffering. To enter a golden age of both spiritual and material wealth, each person must go within and enter a stillness of body and mind, which is when God starts to manifest, and practice balanced living. Practicing certain techniques such as those given by Self-Realization Fellowship helps each person manifest God within, and from there, express Godliness outwardly at all times.
<h2>References</h2>
[1] https://cryptolization.com/ethereum

[2] etherchain.org. "Accounts - etherchain.org - The ethereum blockchain explorer". www.etherchain.org. Retrieved 2017-05-30.  https://www.etherchain.org/account/0x5abfec25f74cd88437631a7731906932776356f9

[3] Davis, Joshua (10 October 2011). "The Crypto-Currency: Bitcoin and its mysteriousinventor". The New Yorker. Retrieved 31 October 2014. http://www.newyorker.com/reporting/2011/10/10/111010fa_fact_davis
<h2>Further reading</h2>
<ul>
	<li>https://www.ethereum.org/</li>
	<li>https://github.com/ethereum</li>
	<li>https://gitter.im/ethereum</li>
	<li>https://ethresear.ch/
<ul>
	<li>https://ethresear.ch/t/the-correct-by-construction-casper-paper-prototype-published-at-devcon-tear-it-apart/196</li>
	<li>https://ethresear.ch/t/latest-casper-basics-tear-it-apart/151/57</li>
	<li>https://ethresear.ch/t/the-stateless-client-concept/172</li>
	<li>https://ethresear.ch/t/ethereum-2-and-alternative-pos-implementations/190/7</li>
</ul>
</li>
	<li>https://en.wikipedia.org/wiki/Ethereum</li>
</ul>
https://www.reddit.com/r/ethtrader/comments/6jyn9y/ethereum_the_hodlors_that_love_them/
<!--more-->

