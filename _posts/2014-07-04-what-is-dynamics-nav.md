---
layout: post
title:  "What is Microsoft Dynamics NAV?"
tagline: An introduction.
date:   2014-07-04 00:00:00
author: Dennis Decoene
category: Tech
tags: [Intro,NAV]
---
{% include JB/setup %}

So you would like to get to know [Microsoft Dynamics NAV](http://www.microsoft.com/en-us/dynamics/erp-nav-overview.aspx) (NAV for short). Let me give you a quick overview of what is is and what it does. I'll also try to explain some pitfalls.

According to the Microsoft website it is this:

>Microsoft Dynamics NAV is a multi-language, multi-currency business management solution that helps small and mid-sized businesses manage their financials, supply chain, and people to create experiences that delight their customers. It is quick to implement and easy to use, with the power to support your growth ambitions. Start with what you need today and add what you need later—whether it's in the cloud or on your servers.

Their statement is mostly right. But it does not give you the answers you are looking for, that I'm certain of. Let's disassemble Microsoft's claim.

1. multi-language, multi-currency business management solution --> True.

    No doubt about this one. You can work in the same company with different languages. You can also efficiently work with different currency's. You can buy in Chinese yen and sell in Thai Bath if you'd like.
	
2. helps small and mid-sized businesses manage their financials, supply chain, and people --> True
    
    Nav is indeed made for business management and nothing but that. It covers all areas. MS used to say it covers 80% of your business needs. That is true.

3. that delight their customers --> BS

    It is not your management software that will delight your customers. It is your people. Get real.

4. It is quick to implement --> Partial BS

    I've never implemented a completely standard NAV. In theory you can just install the clients and a server and you are running. But you have to set the settings and probably want customization here and there so there will be an analysis, development, implementation phase which will take time.
	
5. easy to use, with the power to support your growth ambitions --> True
    
	I've worked with SAP too in the past. Yes, NAV is easy to use. SAP is not.
	
6. Start with what you need today and add what you need later --> Partial BS

    It is difficult to start with an application that does not work according to your business model.
	
7. whether it's in the cloud or on your servers. --> True

    We are used to having a humongous server park which gives us headaches. But does it really need to be that way? Not anymore. With [Microsoft Azure](http://azure.microsoft.com/en-us/) and other could hosting partners, you can provision servers, expand the capacity, shrink the capacity, delete it, spin up a test server, all from your browser. Magic.
    
But NAV is so much more than that.

In its roots, it is a framework for developing applications. Business applications. On top of that framework Microsoft built a business management application. When you buy a license from a partner, you get the framework PLUS the source code of that complete management application. You thus also have the power to change the behavior of the application to suit your own needs. How cool is that?

There are some downsides though. The language of choice is a proprietary language called C/AL and the development environment C/SIDE. While they are not that hard to learn, it is still hard to find good, experienced developers. C/AL has its peculiarities and we see a lot of starting developers make the same mistakes.

In other languages and technologies, you have a plethora of communities, fora and tutorials (thinking about [Stack Overflow](http://stackoverflow.com/ for one)). You get stuck? Just ask. For NAV we only have two worth mentioning. [Mibuso](http://mibuso.com/) and [Dynamics User Group](http://dynamicsuser.net/) are the leading knowledge exchanges. I must admit that almost every problem I came across, I found an answer on one of those two.

So executives remember that NAV is a full suite ERP system. Users remember you can work smarter and faster. Developers remember you have a complete development environment along with an easy to understand application to build on.

NAV is in my opinion the best management software for small and medium companies. MS is not lying...

