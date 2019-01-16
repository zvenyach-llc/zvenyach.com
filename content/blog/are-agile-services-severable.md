---
title: "Are agile services severable?"
date: 2019-01-16T12:26:17-05:00
draft: "true"
publishDate: ""
images: [""]
cover: ""
---

Fiscal law and "color of money" issues are pretty wonky important aspects of government procurement. And one particularly wonky issue that comes up from time to time relates to whether a service is "severable." Today I tackle a question that seems as-of-yet unresolved: is software delivery using agile methodologies a severable service?

Understanding whether a service is severable or not is important because the answer can dramatically affect how an agency obligates money for that service. If a service is severable, the agency can only obligate funds for "services to be performed during the time period of availability of the appropriation to be obligated." In other words, if you expect to deliver a service in a future fiscal year, you need to wait until _that fiscal year_ for the money to be available. If the service is nonseverable, however, the "the entire cost of the nonseverable service is properly charged to a current appropriation, _despite the fact that performance may extend into future fiscal years_." (emphasis added).

In other words, from the perspective of continuity in delivery, a nonseverable service is advantageous because it allows for using existing money to cover future fiscal years.

On the other hand, whether a service is severable or nonseverable can also dramatically affect the ability of the government to use incremental-funding approaches: "severable services contracts may be incrementally funded, while nonseverable services contracts must be fully funded at the time of the award of the contract." If you want to "smooth" your costs across multiple fiscal years, a severable service allows for funding only when the need arises in the fiscal year. In other words, from the perspective of incremental-funding, a severable service is advantageous.

As readers of this blog may know, agile delivery contemplates the notion of delivering working software in increments (typically called "sprints"). So, which is it? Are agile services severable?

In my view (after the mandatory disclaimer that I'm not your lawyer)... it depends!

The GAO Redbook, the primary reference for federal fiscal-law issues, offers a "fairly simple test" to help determine whether a service is severable or not:

> Suppose that a service contract is to be performed half in one fiscal year and half in the next. Suppose further that the contract is terminated at the end of the first fiscal year and is not renewed. What do you have? In the case of a window-cleaning contract, you have half of your windows clean, a benefit that is not diminished by the fact that the other half is still dirty. What you paid for the first half has not been wasted. These services are clearly severable. Now consider a contract to conduct a study and prepare a final report, as in 65 Comp. Gen. 741 (1986). If this contract is terminated halfway through, you essentially have nothing. The partial results of an incomplete study, while perhaps beneficial in some ethereal sense, do not do you very much good when what you needed was the complete study and report. Or suppose the contract is to repair a broken frammis. If the repairs are not completed, certainly some work has been done but you still don’t have an operational frammis. The latter two examples are nonseverable.

On one hand, you can certainly argue that agile software delivery--delivered in sprints or releases--is a severable service because you should have working software at the conclusion of each sprint. If you have a team that delivers working software, it's not "wasted."

On the other, if you are purchasing _outcomes_ and allow the team to define its methodology for delivery, and not just buying a delivery team for a set number of sprints, then you have a nonseverable service.

Some folks focus on contract type when dealing with the analysis of severability. They argue that FFP contracts are nonseverable and T&M contracts are. But this analysis seems to be disfavored by GAO ("After a confusing start, we have determined that the type of contract does not affect the severable versus nonseverable distinction"). To me, the correct analysis is whether you're buying an outcome or only buying capacity.

By way of specific example, suppose you have a legacy web application that needs replacing. If you structure your contract as a "modernization" initiative separate from the underlying application, and you hire a team that delivers incrementally using agile methodologies, then you've got a severable service. On the other hand, if you focus on the value of decommissioning the legacy application, and identify objectives around users actually, ya know, _using_ the modernized application, then it's a nonseverable service because half the code doesn't meet your objectives. You've still got a legacy web application.

If this seems like it's pretty flexible, you're not wrong. As GAO acknowledges, "to some degree an agency can control whether services are severable or nonseverable by selecting the type of contract and crafting the statement of work." Redbook 5-27.

From my perspective, though, this is a feature because it forces the agency to focus on the _value that's supposed to be delivered under a contract_ rather than just hiring teams and hoping for the best. If you've got a well-formed product vision and product strategy, your acquisition strategy can choose to have severable or nonseverable services. If the only thing you know that you need is butts in seats, then you are limited to severable services.

Do you agree? Have you seen contracts for agile services treated as severable services? Nonseverable services? Both? Let me know in the comments below.
