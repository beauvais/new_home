---
author: admin
date: 2009-05-18 17:03:35+00:00
draft: false
title: A Good Week for RDFa
type: post
url: /archives/a-good-week-for-rdfa/
categories:
- From Nodblog
---

**Originally appeared on Nodalities Blog: http://blogs.talis.com/nodalities**

With the unveiling of [Google's RDFa support](http://googlewebmastercentral.blogspot.com/2009/05/introducing-rich-snippets.html) and discussions from the UK's [Central Office of Information](http://zachbeauvais.com/wp-content/uploads/2009/05/more-rdfa-goodness-from-uk-government-web-sites) around using RDFa in their job sites, there has certainly been a lot of coverage of RDFa and [Linked Data](http://zachbeauvais.com/wp-content/uploads/2009/05/linked_data_is_blooming_why_you_should_care.php) over the past few days.

Google's announcement feels a bit limp, hidden as it is in the webmasters' tools. To read their own description of "Rich Snippets," you'd think they were little more than an additional piece in the armory of SEO's and content editors, giving them the ability to flag reviews and products on their pages. The real excitement, as [Tim O'Reilly mentioned](http://zachbeauvais.com/wp-content/uploads/2009/05/google-rich-snippets-semantic-web.html), is that this is Google's first active support for explicit information. A site can now state: "We give this widget 4 stars out of 5, it costs £100, and our CEO is Joe Bloggs." That's fantastic!

I wonder if we tend to miss the importance of explicit statements, because we default to googleing for something and hoping the first page or so of results will contain the answer. I can very swiftly find "reviews" for a Logitech Mouse, for example; but I still have to go through the reviews and find what they said. I might be lucky if Google shows me the result within the site description, but I'm much more likely to need to follow my own lead after Google serves me up a bunch of links to follow. This lets sites explicitely surface an ([admittedly currently woefully limited](http://zachbeauvais.com/wp-content/uploads/2009/05/googles-rdfa-a-damp-squib)) amount of their own data. It makes much more sense for finding what you're actually after without needing to disambiguate yourself. It feels like a step in the right direction. It leaves me personally wishing Google would open it right out and support full vocabularies, but I'm glad for this initial offering.

Alongside Google, the Central Office of Information seems to be taking a much more webby approach to Linked Data, by supporting FoaF and other public vocabularies. [Mark Birbeck explains](http://zachbeauvais.com/wp-content/uploads/2009/05/more-rdfa-goodness-from-uk-government-web-sites):



<blockquote>To facilitate this we set up an open source project called argot-hub, with a wiki, issue-tracking system and associated discussion lists.

The first vocabularies -- or argots -- that I defined were for job vacancies, but in order to make the terminology usable in other situations, I broke out argots for replying to the vacancy, the specification of contact details, location information, and so on.

An argot doesn't necessarily involve the creation of new terms, and in fact most of the argots use terms from Dublin Core, FOAF and vCard. So although new terms have been created if they are needed, the main idea behind an argot is to collect together terms from various vocabularies that suit a particular purpose.</blockquote>



The first pages to support the RDFa information will be vacancy notices, which can be seen at the [Civil Service home page](http://zachbeauvais.com/wp-content/uploads/2009/05/www.civilservice.gov.uk). The great thing about this is that it's supporting application information retrieval. An application can query the site, pull out explicit information, and voila: You're very own "what jobs are available in the Civil Service" app. Looking at all the info there, you could have a field day, sorting by salary, area of interest or whatever.

So, two very different use cases for the Semantic Web via RDFa. What's next?
