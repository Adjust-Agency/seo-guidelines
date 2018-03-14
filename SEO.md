# SEO Guidelines

## While building a strategy

* Make competitor, market and keywords research
* Use Adwords Keyword Planner for Keyword research (and use them in website copy)
* Start a page title with a keyword
* Use keywords when writing your page description
* Use Lexical Field or related keywords in titles / page content (think of human language bots)
* Use Page Title Qualificators or Long Tail Keywords [[3]] [[4]]
* Page title around 10 words max
* Page description should be 160 chars long
* Quickly mention keywords in homepage content ( first 100 words )
* Think about a way to create fresh content (blog, news, ...)
* Use a wide range of social networks ( Facebook, Instagram, Pinterest, Twitter ... )
* Uniformize the brand on social networks (names, logo)...
* ... but choose the right tone for the right network (Twitter: quick and wit, Facebook: gatherer, Instagram: beautiful and idealize, ...)
* Use link intersect on competitor to find opportunities [[8]]
* Plan outbound links to related external pages
* Reflect on the eventuality of an AMP version [[5]]

## While designing

* Mobile design is __not__ optional
* Think about mobile first vs adaptive design and provide layouts accordingly [[7]]
* Design mobile ui when creating desktop ui
* Mobile design is __still not__ optional
* Create appealing visuals to reduce bounce rate
* Create appealing Call To Action (ex: badge, buttons) and A/B them
* And __nope__, mobile design __still not__ optional here either
* __Win awards__ to build awareness
* A/B Test your design for best UX experience

## While coding

* A page __MUST__ contains __ONLY ONE__ H1 tag
* __No non-text content__ in H1 or Hx tag (use background image with hidden text if necessary)
* Use structured Hx tags (No H3 without H2)
* __Be semantic !__ ( lists in ul/ol, menu in nav, header in header, ... )
* Minimize assets ( CSS and JS ). The fewer assets loaded the better (use [adjust gulpfile](https://github.com/Adjust-Agency/boilerplate-frontend)).
* Always use crawlable content and make __judicious__ use of AJAX ( Google is deprecating AJAX Scheme technique in July 2018 [[6]])
* Always use descriptive alt on images
* Avoid single page content as much as possible. Or use Javascript URL routing if the need to build a single page __really makes sense__.
* Keywords in __URL MUST__ match page content
* Structure your page titles ( H1 -> Category -> Brand ). [[1]] [[2]]
* Use keywords defined by the strategy in URLs, Meta title and H1
* Use as much SVG pictures as possible (ex: icons, logos, ...)
* Always compress bitmap images (no picture above 600kb) [[9]]
* Think about resolution management technique (ex:[picture element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/picture))
* Never use meaningful or descriptive image as background (use IMG or PICTURE Tag with ALT attributes)
* Pay attention to case sensitive files and urls
* Rewrite URL when possible ( htaccess or routes )
* Create a landing page for subcategories (/cat/subcat/page, /cat/subcat, /cat)
* Use dash instead of underscore in URLs
* Make use of internal links
* Create a sitemap (use [adjust tool](https://github.com/Adjust-Agency/adjuvant-sitemap))
* Create a robots.txt
* Add opengraph and share snippets
* Use microdata when possible (ex: [breadcrumbs](http://schema.org/BreadcrumbList))
* Use canonical metatag for duplicate content
* Use CDN for images if possible
* Paginate with rel="prev" and rel="next"

## Practical

* Never publish a website without Google analytics
* Add the website to Google Search Console as soon as it enters production
* Add SSL
* Check for favicon

## Follow-up

* Use 301 Redirect for old website links
* Check for duplicate content with the Google Search Console (GSC) 
* Analyse Google search for keywords, use logic, boost your best keywords
* Broke deals with partners for linking

## Tools and links

* <https://moz.com/researchtools/ose/>
* <https://moz.com/blog/15-seo-best-practices-for-structuring-urls>
* <https://lsigraph.com/>
* <https://moz.com/blog/find-competitor-backlinks-next-level>
* <http://schema.org/docs/gs.html>
* <https://github.com/scottjehl/picturefill>
* <https://developer.mozilla.org/en-US/docs/Web/HTML/Element>
* <https://developers.google.com/speed/>
* <https://search.google.com/test/mobile-friendly>
* <https://support.google.com/webmasters/answer/6062596?hl=en>
* <https://github.com/Adjust-Agency/adjuvant-sitemap>
* <https://blog.hubspot.fr/marketing/le-guide-ultime-pour-devenir-un-virtuose-des-long-tail-keywords>
* <https://yoast.com/focus-on-long-tail-keywords/>
* <https://backlinko.com/on-page-seo>
* <https://compressor.io/>

[1]: https://www.sony.com/electronics/headband-headphones/mdr-z1r
[2]: https://www.massimodutti.com/be/fr/mid-saison/manteaux-et-vestes/blouson-vert-nappa-c1760630p8138032.html?colorId=500&parentId=8138208
[3]: https://yoast.com/focus-on-long-tail-keywords/
[4]: https://blog.hubspot.fr/marketing/le-guide-ultime-pour-devenir-un-virtuose-des-long-tail-keywords
[5]: https://www.ampproject.org/
[6]: https://webmasters.googleblog.com/2017/12/rendering-ajax-crawling-pages.html
[7]: https://blog.stephaniewalter.fr/traduction-adaptive-vs-responsive-quelle-est-la-difference/
[8]: https://moz.com/blog/competitive-link-analysis-link-intersect-in-excel
[9]: https://compressor.io/
