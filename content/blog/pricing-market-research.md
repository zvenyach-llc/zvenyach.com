+++
title = "How can I find out what companies charge the government for certain services?"
date = 2018-11-21T20:19:28-05:00
publishDate = ""
cover = "/images/blog-images/photo-1523540939399-141cbff6a8d7.jpg"
images = ["/images/blog-images/photo-1523540939399-141cbff6a8d7.jpg"]
+++

One of the more inside-baseball parts of government contracting is conducting market research to predict your competitors' cost. If you've been in the game for a while, you generally know what others are charging and where you stack up. But, what if you're new and trying to assess your position? Or, what if you're just interested in finding out how much stuff should cost? In this post, I offer some tips on some of the publicly available tools I use that can help with market research on pricing for government.

{{< figure src="/images/blog-images/photo-1523540939399-141cbff6a8d7.jpg" caption="Some pro tips on finding pricing data for government services" class="figure">}}

First, the bad news. You actually can't get the *real* prices paid at the item or service level. There are reasons that I won't get into here, but the bottom line is that companies use a couple of different techniques to obfuscate the actual cost of services provided.

That said, there is good news. In most cases,[^1] you *can* get meaningful information through a variety of sources and put together meaningful estimates.

First, and perhaps most importantly, even though you can't easily find granular line-item data for most contracts (more on that in a bit), you can easily find the **total** price for a given contract using publicly available data on [USASpending.gov](https://usaspending.gov), which in turn draws from the [Federal Procurement Data System](https://fpds.gov). Both of these sites are core parts of the professional government-procurement toolkit.

{{< figure src="/images/blog-images/usaspending-screenshot.png" caption="Bookmark [this website](https://usaspending.gov). It's so good!" class="figure" >}}

Using this as a starting point, you can often reverse-engineer pricing information if you have access to the original solicitation, which you can sometimes find online on [FedBizOpps](https://fbo.gov) or other sites like [FedConnect](https://www.fedconnect.net/FedConnect/default.htm). If you can't find it there, you can use the [Freedom of Information Act](https://foia.gov) to gain access to contract information, including [in some cases](https://www.insidegovernmentcontracts.com/2018/10/new-cases-confirm-foia-exemption-4-protects-line-item-pricing-information/) line-item-pricing information.

Using these tools and related methods are the stock and trade of procurement professionals who are serious about winning specific contracts with known competition.

But if you're looking for _ballpark_ line-item pricing information on labor rates, then there are three other tools that can, well, give you ballpark figures. That's because, even though you can't easily discover what the lowest cost a company charges the government for a particular item or service, you *can* tell what a company claims their *highest* government rate is, if they're on a GSA Schedule. Under the [Price Reduction Clause](https://www.contractorsperspective.com/compliance/applying-the-price-reduction-clause-in-gsa-schedule-contracts/) for GSA Schedule contracts, a contractor generally[^2] agrees to give the best rate to the government, and the contractor has to adjust its price offerings if the contractor "grants more favorable discounts or terms and conditions" to a commercial customer. Given this point of information, you can generally know the *top end* of what a government contractor will charge for an hourly rate.

So how do you find that information? I look in three places: GSA's [eLibrary](https://www.gsaelibrary.gsa.gov/), GSA [Advantage](https://www.gsaadvantage.gov/), and GSA's [CALC](https://calc.gsa.gov). Why are there three places, you might be wondering? That's for another day, but you'll need to buy me a bourbon neat. For now, let's look at how to find the rates in those places.

In eLibrary, the best trick is to see if you know your competition. If you're looking for a particular company, there's a [Contractor Directory](https://www.gsaelibrary.gsa.gov/ElibMain/contractorList.do?contractorListFor=A) (as of November 2018, it's underneath the search bar and a little to the left).

{{< figure src="/images/blog-images/gsa-elibrary-screenshot.png" caption="A screenshot of GSA eLibrary" >}}

Suppose you're looking up the contract for `'APPS' CONSULTANTS INC., THE`.[^3] It's super hard to find, but if you look for the little document image in the `Contractor T&Cs/Pricelist` column (screenshot below), it'll actually pop up a Word document or PDF. In that document, somewhere, there will be a table with labor rates. In our example, a Project Manager from `'Apps' Consultants Inc., The` has an hourly labor rate of $110 in the first year of the contract. It goes up to $126.72 in the last year of the contract.

{{< figure src="/images/blog-images/gsa-elibrary-screenshot-2.png" caption="A screenshot of GSA eLibrary with emphasis on the Pricelist" >}}

If you're not sure who your competition is, you can use the word search functionality of GSA Advantage. I usually just go straight to the ["Advanced Search"](https://www.gsaadvantage.gov/advantage/s/advncdSearchSrvsEnter.do) functionality because it has filtering and exact phrase searches that I use a lot. But, otherwise it's the same deal as with eLibrary: search for the term (or the company name) and then download the catalog/pricelist. On the pricelist, look for the table with the rates. Boom.

{{< figure src="/images/blog-images/gsa-advantage-screenshot.png" caption="A screenshot of GSA Advantage!" >}}

Finally, there's CALC. Compared to GSA eLibrary and GSA Advantage, CALC is a user-interface godsend. Type in the type of labor rate you're looking for and it'll give you a range of prices, and even a standard deviation in either direction. But CALC is *only* useful for labor rates, so you can't look up products or services (such as training services). And although the interface is amazing, the data hasn't always been as reliably complete as I'd like it to be and it doesn't have some of the filtering capabilities (socioeconomic filters in particular) that can be useful in market research. So I use CALC in conjunction with GSA eLibrary and GSA Advantage. But it's not quite a substitute, yet.

{{< figure src="/images/blog-images/calc-screenshot.png" caption="A screenshot of CALC. Much nicer, right?">}}

In sum, even though each tool -- USASpending.gov, FPDS, FOIA, GSA eLibrary, GSA Advantage, and CALC -- is limited in its own way, there is a treasure trove of data out there that you can use to find about your competition's price, if you know what you're looking for. One day, hopefully, the data will be more accessible so you don't need superpowers or arcane knowledge to find out how much things cost. But until that day, fortunately, with just a little practice, you can become pretty adept at using these sites so that you and your organization can make smarter decisions about government contracting. 

[^1]: I say *most cases* because there's a nuanced exception associated with the [Transaction Data Reporting ("TDR") pilot program](https://www.federalregister.gov/documents/2016/06/23/2016-14728/general-services-administration-acquisition-regulation-gsar-transactional-data-reporting) that I won't get into here but may one day fundamentally alter how industry and the government reports transaction-level data. For now, though, TDR isn't going to be all that useful in answering the main question, so I simply note it and move on.

[^2]: I say *generally* because there are a few exceptions that, like the exception in the previous footnote, is not helpful for the current analysis but I want to avoid blanket assertions.

[^3]: Amazingly, it's the first result on the list. Special kudos to the person who realized that a single quotation and setting off the definite article in its name as a first name would get you first on the list. This is, no joke, an impressive bit of bureaucracy hacking.
