+++
title = "Two tools that can lead to better digital-services acquisition outcomes"
date = "2018-10-31"
cover = "/images/blog-images/accelerate-book-cover.jpeg"
images = ["/images/blog-images/accelerate-book-cover.jpeg"]
+++

Identifying qualified vendors to deliver digital services and effectively monitoring delivery by those vendors is a significant challenge for government acquisition professionals. Although there are numerous resources that can help government teams do a better job of building and buying technology, in this post, I highlight two new tools that should be considered indispensable for the digital-services expert.

The first, [Steps to Performance-Based Acquisition](https://pba.app.cloud.gov/app/#/), is an online guide for federal acquisition professionals to use when acquiring professional services. The second, “[Accelerate](https://itrevolution.com/book/accelerate/),” is a book written by Dr. Nicole Forsgren, Jez Humble, and Gene Kim, about DevOps and measuring software-delivery performance.

In this post, I discuss those two resources, and how they can be used _together_ improve digital-services acquisition by helping select high-performing vendors and monitoring performance through a capabilities-based approach.

## Steps to Performance-Based Acquisition

The Federal Acquisition Regulations generally “requires the use of performance-based acquisitions for services to the maximum extent practicable.” FAR 37.000. Accordingly, performance-based acquisitions are a core part of the work of a digital-services acquisition professional in government. Despite the rule, successful implementation of performance-based acquisitions is challenging. To address that challenge, the General Services Administration has created a resource called the [Steps to Performance-Based Acquisition](https://pba.app.cloud.gov/app/#/) (“SPBA”) to aid in the government’s use of performance-based acquisitions.

Generally recognized as a best practice, the document explains that “[p]erformance-based acquisition can dramatically transform the nature of service delivery, and permit the federal government to tap the enormous creative energy and innovative nature of private industry.”

The document helpfully breaks down the acquisition process into 8 “steps” and, within each step, the document provides guidance, resources, and links to other information about how to conduct a successful performance-based acquisition.
The Eight Steps to Performance-Based Acquisition (from https://pba.app.cloud.gov/app/#)

{{< figure src="/images/blog-images/spba-screenshot.png" caption="The Eight Steps to Performance-Based Acquisition (from https://pba.app.cloud.gov/app/#)" >}}

As the [background section](https://pba.app.cloud.gov/app/#/pba/about/background) to the SPBA explains:

> “A successful acquisition answers four questions: what do I need, when do I need it, who needs to get it to me, and how do I know it’s good when I get it?”

Despite the simplicity of the principles of performance-based acquisition, one of the principal challenges facing the government in the delivery of digital services has been answering that last question “how do I know it’s good when I get it?” Defining what successful digital-service delivery looks like has been an ongoing challenge, often answered with varying hand-waves around organizational maturity.

Fortunately, as we’ll see in the next section, we now have research that helps us answer that question with a little more clarity.

## Accelerate: The Science of Lean Software and DevOps

When he left 18F in 2017, I asked [Jez Humble](https://twitter.com/jezhumble) what he was going to do next. He alluded at the time to some research that was underway with a few of his colleagues, and doing some consulting work. Then, in March 2018, Dr. Nicole Forsgren, Jez, and Gene Kim published [Accelerate: The Science of Lean Software and DevOps: Building and Scaling High Performing Technology Organizations](https://itrevolution.com/book/accelerate/), and my head damn near exploded.

> Over our four-year research program we have been able to identify the capabilities that drive performance in software delivery and impact organizational performance, and we have found that they work for all types of organizations.

This was the book that I had been missing: a concise, research-based description of what high-performing teams looked like, and a method by which an organization could measure improvement without resort to organizational “maturity models.”

Instead of trying to define a whole organization’s maturity (which felt rather impossible given my experience), they described a “capabilities model of measurement” using 24 key capabilities, grouped into 5 categories: *Continuous Delivery*, *Architecture*, *Product and Process*, *Lean Management and Monitoring*, and *Culture*.

Some of these capabilities (particularly in the first and second categories) are technical capabilities, such as use of version control, trunk-based development, and test automation. Others involve non-technical capabilities such as relying on customer feedback, implementing Work-in-Progress limits, and cross-team collaboration.

Notably, though, some of the capabilities involve metrics or descriptions of specific behaviors that reflect those capabilities. For example, the research demonstrates that “deploy frequency is high correlated with continuous delivery and the comprehensive use of version control.” Similarly, the research showed that “a lightweight change approval process predicts software delivery performance.”

As such, even though the authors are careful to avoid claims around causation, it would be reasonable to assume that a software development team that deploys regularly and manages change approval with minimal burden will be higher performing than a team that deploys infrequently and has a heavy change advisory board process.

In other words, simply _asking_ a team about their change and deployment process can tell you a lot about the quality of the team’s product.

{{< figure src="/images/blog-images/accelerate-book-cover.jpeg" caption="https://itrevolution.com/book/accelerate/" >}}

## Using Accelerate during the Steps to Performance-Based Acquisition

Now that we have both SPBA and Accelerate, it is possible for acquisition professionals to begin to assess their organization’s capabilities when acquiring digital services _as well as_ to assess industry partners’ capabilities during delivery.

Here are at least three ways that the Accelerate framework can be used for better government contracts.

### Improved market research through capabilities assessment

During the pre-solicitation phase, the Accelerate framework can improve market research. As the SPBA explains for Step 3, market research is where acquisition teams must learn about potential vendors and is “vital to conducting an effective performance-based acquisition.” Usually, when doing market research, acquisition teams will rely on techniques such as Requests for Information (RFI), industry days, “sources sought” notices, and pre-solicitation conferences.

But Step 3 also explains that One-on-One Meetings with Industry are a particularly effective approach to market research:

> “While many may not realize it, one-on-one meetings with industry leaders are not only permissible…they are more effective than pre-solicitation or pre-proposal conferences.”

Armed with the Accelerate framework, acquisition teams can ask vendors to describe not only their experience, but _to specifically probe into understand the vendors’ approach to delivery_. In those one-on-one meetings, the acquisition team can get a sense of whether prospective vendors have the needed capabilities to deliver quality software.

Doing so not only will help identify the right acquisition strategy, but it can reveal where the government may need to expend particular energy to shore up weaknesses and play to strengths. By way of specific example, many delivery teams that traditionally work with government are hindered by inadequate tooling for continuous delivery and heavy change-control processes. Knowing this, by spending time _before_ the acquisition to invest in better approaches to tooling and delivery patterns, the government can improve software quality even before the contract is awarded.

### Using capabilities as part of vendor’s technical evaluation criteria

Even though Accelerate relies significantly on survey data to help develop its conclusions, there is no reason why the government shouldn’t use the framework to develop better evaluation criteria for contracts. Indeed, Accelerate provides an excellent lens to explore teams’ past performance and technical approach.

Rather than relying on certifications or maturity models, Accelerate can provide insight into examine teams’ actual capabilities to deliver. Knowing, for example, that “lean product development capabilities predict Westrum organizational culture, software delivery performance, organizational performance, and less burnout,” it is reasonable to include a vendor’s product-management approach as part of the technical-evaluation criteria.

### Using capabilities to enable better performance management

Finally, after the contract is awarded, the real work of delivery begins. The SPBA makes plain that effective performance-based acquisition doesn’t stop after the award is made.

> “Correctly managing performance may be the most important step to successful performance-based acquisitions.”

But even though managing performance may be hard, it’s virtually impossible unless there is a shared understanding of what successful performance actually means. And that’s where Accelerate comes to the rescue; using the capabilities approach described in the book, you can both assess the team’s approach and capabilities, but you can also _measure the quality of the product_. Using DevOps and lean-product metrics to assess how things are going can help make sure that teams are continuously improving, and consistently shipping quality software.

## Conclusion

Separately, the SPBA and Accelerate are important documents. The SPBA helps acquisition professionals break down the key parts of performance-based acquisition, and provides resources about how to best conduct one. Accelerate helps organizations identify, measure, and improve software delivery performance through DevOps and lean practices. Together, though, they are greater than the sum of the parts. For those who work in government digital-services acquisition (and [those who teach it](https://medium.com/@vdavez/my-next-chapter-61295c237d67)), both the SPBA and Accelerate should be considered essential resources.
