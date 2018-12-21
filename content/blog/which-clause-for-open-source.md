---
title: "Which clause should I use for buying custom open-source software?"
date: 2018-12-20T10:20:50-06:00
draft: "false"
publishDate: "2018-12-20"
images: ["/images/blog-images/choosing-data-rights-clauses.png"]
cover: "/images/blog-images/choosing-data-rights-clauses.png"
---

The [federal source-code policy](https://sourcecode.cio.gov) requires contracting officers to, when buying custom-developed software, "consider the value of publishing custom code as [open source software] and negotiate data rights reflective of its value-consideration." But then the policy says absolutely nothing about which FAR clause to include to ensure appropriate data rights. Should COs use the [General rights in data clause](https://www.acquisition.gov/content/52227-14-rights-data-general)? Should they use the [Special Works clause](https://www.acquisition.gov/content/52227-17-rights-data-special-works)? I've seen some contracts do *both*. And, really, who can blame them, given the lack of guidance?

**So, which data-rights clause should the contracting officer choose?**

Fortunately, if you're in a civilian agency[^1], here's a really easy way to think about which FAR clause to use when acquiring custom free and open-source software (FOSS). If you *know* at the time of solicitation you're going to publish the delivered code as free and open-source software, it doesn't really matter: either the FAR's General Rights in Data clause or the Special Works clause works just fine. But if you don't know whether you'll open source but suspect you might, stick with the Special Works clause.

Here's why.

{{< figure src="/images/blog-images/choosing-data-rights-clauses.png" caption="Who doesn't love a flowchart?!" alt="A flowchart describing the approach to choosing data-rights clauses" >}}

[^1]: There are totally different rules applicable to the Department of Defense when it comes to data rights. As someone who is not an expert in the DFARS, I'll simply note that the rules are different and encourage others to write something definitive on how defense acquisition professionals should handle data rights for custom-developed, open-source software.

## The FOSS "Freedoms"

Although a full treatment of the differences between FOSS licenses is beyond the scope of this post, it is important to understand that *all* FOSS licenses share the same [four basic "freedoms"](https://fsfe.org/freesoftware/basics/4freedoms.en.html): the freedoms "to use, study, share and improve the software."

Effectively, to qualify as FOSS, the software's author must allow, subject to certain limitations, anyone else to use, access, redistribute, and make "derivative works" of the software.

If you're *really* interested in the differences between the licenses, you might visit [Choose a License](https://choosealicense.com/). But, fair warning, I've found it to be pretty easy to go down open-source-license rabbit holes.

## Unlimited rights

By default, in civilian agencies, "unlimited rights" in data pretty much always automatically apply to custom-developed code. The government has unlimited rights for all computer software "first produced in the performance of a contract." So, almost by definition, if a vendor is hired to deliver custom-developed code, that code is going to be eligible for unlimited rights.

Critically, though, unlimited rights are **largely coextensive with the "freedoms" associated with FOSS**. Here's the formal definition of unlimited rights:

> "Unlimited rights" means the rights of the Government to use, disclose, reproduce, prepare derivative works, distribute copies to the public, and perform publicly and display publicly, in any manner and for any purpose, and to have or permit others to do so.

Use? Check. Study/access? Check. Disclose/share/reproduce? Check. Prepare derivative works? Check.

FOSS and Unlimited Rights go hand in hand. Which is great when you're dealing with custom-developed software for government!

## Picking a FAR clause

So if the government already has the rights it needs when creating open-source software, why is there confusion about which FAR clause to use? When is it appropriate to use FAR clause 52.227-14 ("Rights in Data-General") or FAR clause 52.227-17 ("Rights in Data-Special Works")?

That issue typically boils down to who can assert a copyright interest. In the case of the "general" clause, the vendor may assert a copyright interest. In the case of the "special works" clause, the vendor *assigns* that copyright interest to the government. Fortunately, if an agency defaults to open as part of the performance of the contract, that decision is largely meaningless.

To understand why, it's worth remembering that open-source licenses necessarily grant both the government *and* the public the right to use, reuse, distribute, and modify the source code. As such, the government's and the public's interests are protected irrespective of whether the government holds title to the underlying copyright or whether the vendor holds title. If the agency is going to require the vendor open source the custom code -- and the agency **should** require this -- then the government can use language like [how 18F implements its open source policy](https://github.com/18F/tts-buy-searchgov-development/blob/master/solicitation_documents/RFQ.md#data-rights-and-ownership-of-deliverables):

> [The Government] intends that any data or deliverable created as a result of the work performed under this order be made available under a free and open-source license.

When the vendor creates FOSS pursuant to the contract, the question of title is irrelevant because the government and the public enjoy the FOSS Freedoms, and the Government can go ahead and use the General rights in data clause.

The decision about who holds title only *really* matters when the government does not require the vendor to use an open-source license as part of the performance of the contract. In such cases, the Special Works clause is valuable because it explicitly provides that "[t]he contract may specify the purposes and conditions (including time limitations) under which the data may be used, released, or reproduced other than for contract performance." Although this provision is really intended to *prevent* public distribution of data, the clause works just as well for *publishing open source* directly.

When weighing which clause to use, a CO should simply ask whether the agency is going to require its source code be made available under a FOSS license as part of the requirement. If the agency is requiring its custom code be licensed as open-source, then it's perfectly fine to stick with the General clause. But if you're not sure, use the Special Works clause to reserve the government's right to publish the software as FOSS later.

And if you're *still* not sure, here are two good default rules:

1. [Default to open](https://playbook.cio.gov/#play13); or
2. Default to [Special Works](https://www.acquisition.gov/content/52227-17-rights-data-special-works).

And one more: if you're *still still* not sure, ask your Office of General Counsel because I'm not your lawyer!

If you're interested in practical tips like these, [join my mailing list](https://zvenyach.com/signup) and look out for updates on my forthcoming book: [Joyful Procurement](https://zvenyach.com/blog/joyful-procurement-announcement).

Disagree with my analysis? Or have a different perspective on when to use which clause? Let me know in the comments below!
