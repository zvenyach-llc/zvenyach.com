+++
title = "Three cool new things about the Recipient Profile feature of USASpending.gov"
date = 2018-12-03
draft = "false"
images = ["/images/blog-images/fitchburg-profile.png"]
cover = "/images/blog-images/fitchburg-profile.png"
+++

When the news of an update to [USASpending.gov](https://usaspending.gov) came out at the end of November 2018, I went a bit overboard on the superlatives:

{{< tweet 1068633951684710401 >}}

But the truth is that the new features add to an already powerful tool for companies who are in the government contracting and grantmaking space. In this post, I focus on one new feature -- the **Recipient Profile** feature -- to illustrate how you might use it.

## The Recipient Profile

Before diving in, just to remind you, USAspending.gov is the "official source for spending data for the U.S. Government." After a dramatic revamp in 2017 as a result of the DATA Act, it now allows you to "follow the money from the Congressional appropriations to the federal agencies and down to local communities and businesses."

Well, one of the ways that USASpending.gov does that is let you see who actually gets that money in what they call the "Recipient Profile."

To find the recipient profile, you'll need to navigate to the USASpending.gov website and look for the ["Profiles" menu option](https://www.usaspending.gov/#/recipient). From there, you'll see a large-ish table that lets you search by Recipient Name or DUNS number. What's a recipient?

> Recipients are any entity that has received federal money in the form of contracts, grants, loans, or other financial assistance."

If you received money from the US Government, you're a recipient (including states)!

Ok. Let's see it in action. As you may know, I live in the city of Fitchburg, WI. So, I've typed in "City of Fitchburg" and _voila_, [here's my hometown](https://www.usaspending.gov/#/recipient/d31faaaa-ac82-ca1a-59f6-8e8e48665195-P). (Admittedly, I had to double check because Massachusetts has a Fitchburg, too. Glad I don't live in Springfield...)

{{< figure src="/images/blog-images/fitchburg-profile.png" class="figure" alt="A view of Fitchburg, WI's receipts" caption="Home, sweet home.">}}

From here, I learned that in July 2018, my hometown picked up a _single_ federal grant: an "Assistance to Firefighters Grant" in the amount of $15,678 from the Department of Homeland Security. Neat!

## What can I do with the tool?

So, now that I know the tool exists, what are some of the ways you can use it? Here are two obvious ways:

### You can view total spend across multiple subsidiaries

If you're into government contracting in Wisconsin, chances are you've heard of [Oshkosh Corporation](https://www.usaspending.gov/#/recipient/d9fe644d-d231-ccfe-f705-66f86c48f5f6-P). Why? Oshkosh, b'gosh?! No, that's a different company. Oshkosh Corporation primarily sells military trucks. And it is the largest contractor in the state.

Let's take a look at it.

{{< figure src="/images/blog-images/oshkosh-profile-screenshot.png" alt="A view of the Oshkosh Corporation's profile" class="figure" caption="Oshkosh Corporation">}}

Now, here's what's cool. See where it says "Parent Recipient"? Amazingly, because the [System for Award Management](https://sam.gov) maintains an entity hierarchy for all recipients of federal dollars, it is possible to see not only which individual company receives federal money, but _all of the companies_ in the hierarchy. To see the list of "children" in the Oshkosh Corporation, you just click the "View child recipients" and you get this:

{{< figure src="/images/blog-images/oshkosh-children-screenshot.png" class="figure" alt="A view of the Oshkosh Corporation's children entities" caption="Oshkosh Corporation's children">}}

This ability to go up and down in an entity's hierarchy is incredibly valuable when it comes to understanding aggregate spending patterns for large organizations.

### You can see a recipient's socioeconomic categories at a glance

In addition to the transaction volume over time, the recipient profile provides information about an entity's socioeconomic characteristics.

{{< figure src="/images/blog-images/usaspending-socioeconomic-profiles.png" class="figure" alt="A listing of socioeconomic categories for a particular company" caption="A listing of socioeconomic categories for a particular company" >}}

This feature is particularly useful when doing [market research](/blog/pricing-market-research/) as part of developing an acquisition strategy or whether you're evaluating potential teaming arrangements in federal contracting.

## What's still to come

In Even though the tool is incredibly powerful, the linking between the recipient tool and underlying awards data seems to be a work-in-progress. I imagine that, eventually, you'll be able to click and drill down to individual awards from within the profile, and _vice versa_. But for now, the tool is a window into what's to come.

So, what's the third cool thing I refer to in my blog post title? And to that end, because USASpending is an API-driven web application, if you look under the hood, it [looks like there's much more to come with the new API version](https://api.usaspending.gov/api/v2/recipient/duns/d9fe644d-d231-ccfe-f705-66f86c48f5f6-P/?year=all):

{{< figure src="/images/blog-images/undocumented-api.png" class="figure" alt="A screenshot of the undocumented API" caption="Yes, this is an as-of-yet undocumented API endpoint for recipient data." >}}

That's right. There are whole new API endpoints on the way, making it even easier to analyze federal spending data and follow federal funds.

How might *you* use the tools? What would you like to see in USASpending.gov? Let me know in the comments below!
