# Offline-First [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://img.shields.io/travis/pazguille/offline-first.svg)](https://travis-ci.org/pazguille/offline-first)

> Useful resources for creating Offline-First web apps

> "Web" and "online" are two closely associated terms, downright synonymous to many people. So why on earth would we talk about "offline" web technologies, and what does the term even mean?

> via https://www.html5rocks.com/en/features/offline

Inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing.

## Table of Contents
- [W3C Specification](#w3c-specification)
- [Newsletter](#newsletter)
- [Posts](#posts)
- [Presentations](#presentations)
  - [Videos](#videos)
  - [Slides](#slides)
- [Tools](#tools)
- [Books](#books)
- [Showcase](#showcase)
- [Who to Follow](#who-to-follow)
- [Contributing](#contributing)

## W3C Specification

[Offline Web Applications](http://www.w3.org/TR/offline-webapps/)
> This specification highlights features (SQL, offline application caching APIs as well as online/offline events, status, and the localStorage API) from HTML5 and provides brief tutorials on how these features might be used to create Web applications that work offline.

[Service Workers](http://www.w3.org/TR/service-workers/)
> This specification describes a method that enables applications to take advantage of persistent background processing, including hooks to enable bootstrapping of web applications while offline.

[IndexedDB](http://www.w3.org/TR/IndexedDB/)
> This specification defines APIs for a database of records holding simple values and hierarchical objects. Each record consists of a key and some value. Moreover, the database maintains indexes over records it stores. An application developer directly uses an API to locate records either by their key or by using an index. A query language can be layered on this API. An indexed database can be implemented using a persistent B-tree data structure.

[WebStorage](http://www.w3.org/TR/webstorage/)
> This specification defines an API for persistent data storage of key-value pair data in Web clients.

## Newsletter
[The Offline First Reader](http://offlinefirst.us4.list-manage1.com/subscribe?u=12d36bbe9418ed6a43127cd62&id=7fc00bfaef). A monthly reader featuring all things Offline First, covering theory, technology and user experience for new offline use cases.

## Posts

[The Service Worker Lifecycle](https://developers.google.com/web/fundamentals/instant-and-offline/service-worker/lifecycle)
(Jake Archibald - Oct 13, 2016)

[Do you need Service Worker in your web app?](https://codingbox.io/do-you-need-service-worker-in-your-web-app-d68131d65e2c?gi=666f4385e803)
(Valerii Iatsko - Oct 9, 2016)

[Progressive Web Apps with React.js: Part 3 — Offline support and network resilience](https://medium.com/@addyosmani/progressive-web-apps-with-react-js-part-3-offline-support-and-network-resilience-c84db889162c?source=userActivityShare-136a881c591e-1475748613)
(Addy Osmani - Oct 5, 2016)

[Offline Reading List](https://chrisruppel.com/blog/service-worker-offline-content-list/)
(Chris Ruppel - Oct 5, 2016)

[Enabling Offline First Experiences on the Web with Service Workers](https://medium.com/offline-camp/enabling-offline-first-experiences-on-the-web-with-service-workers-e4bc8c773dae#.c6ui0i9cs)
(Dan Zajdband - Sep 12, 2016)

[Build More Reliable Web Apps with Offline](http://thenewstack.io/build-better-customer-experience-applications-using-offline-first-principles/)
(Pedro Teixeira - Sep 7, 2016)

[Songsearch – using ServiceWorker to make a 4 MB CSV easily searchable in a browser](https://www.christianheilmann.com/2016/08/26/songsearch-using-serviceworker-to-make-a-4-mb-csv-easily-searchable-in-a-browser/)
(Christian Heilmann - Aug 26, 2016)

[Offline Storage for Progressive Web Apps](https://medium.com/dev-channel/offline-storage-for-progressive-web-apps-70d52695513c#.ryrpvq43r)
(Addy Osmani - Aug 15, 2016)

[Add offline support to any Web app](https://medium.com/google-developer-experts/add-offline-support-to-any-web-app-c20edc4bea0e#.jeseb4ovf)
(Wassim Chegham - Jul 23, 2016)

[ServiceWorker: A Basic Guide to BackgroundSync](https://ponyfoo.com/articles/backgroundsync)
(Dean Hume - Jul 19, 2016)

[Offline First, the Decentralized Web, and Peer-to-Peer Technologies](https://medium.com/offline-camp/offline-first-the-decentralized-web-and-peer-to-peer-technologies-b05b7fb3bcdd#.6xdfvy6on)
(Pedro Teixeira - Jul 15, 2016)

(Offline Google Analytics Made Easy)[https://developers.google.com/web/updates/2016/07/offline-google-analytics]
(Jeff Posnick - Jul, 2016)

[Offline Content with Service Worker](https://chrisruppel.com/blog/service-worker-offline-content/)
(Chris Ruppel - Jun 6, 2016)

[Taking an online book offline](https://adactio.com/journal/10754)
(Jeremy Keith - Jun 3, 2016)

[Service Workers — Gotchas](https://medium.com/@boopathi/service-workers-gotchas-44bec65eab3f#.4q0ncllos)
(Boopathi Rajaa - May 9, 2016)

[Offline-first QR-code Badge Scanner](https://developer.ibm.com/clouddataservices/2016/05/05/offline-first-qr-code-badge-scanner/)
(Glynn Bird - May 5, 2016)

[Service Workers and PWAs: It’s About Reliable Performance, Not “Offline”](https://infrequently.org/2016/05/service-workers-and-pwas-its-about-reliable-performance-not-offline/)
(Alex Russell- May 4, 2016)

[Progressive Web Apps: Eating your Cake](https://medium.com/@torgo/progressive-web-apps-eating-your-cake-c0a79797220f#.jp6qup8xg)
(Daniel Appelquist - Apr 27, 2016)

[Progressive Web Apps with Service Workers](http://blog.booking.com/progressive-web-apps-with-service-workers.html)
(Jesse Yang - Apr 21, 2016)

[How To Use PouchDB + SQLite For Local Storage In Ionic 2] (http://gonehybrid.com/how-to-use-pouchdb-sqlite-for-local-storage-in-ionic-2/)
(Ashteya Biharisingh - Apr 18, 2016)

[Offline-First, Document Sharing, Templates: Monod is Back (not in Black)] (https://tailordev.fr/blog/2016/04/15/le-lab-2-offline-first-document-sharing-templates-monod-is-back/)
(Apr 15, 2016)

[Issue 4: Offline badging, DevTools, Testing, Travis, Web Storage, Service Worker Scopes, Data-driven Development, Compute Engine](https://medium.com/totally-tooling-tears/issue-4-offline-badging-testing-travis-devtools-issues-web-storage-data-driven-development-8dd1cfbc410a#.mgur8g8n3)
(Addy Osmani - Apr 15, 2016)

[The New Builders Ep. 1: Craft Beer and Progressive Web Apps](https://developer.ibm.com/tv/untappd-web-apps/)
(Douglas Flora - Apr 14, 2016)

[Service Workers replacing AppCache: a sledgehammer to crack a nut](https://medium.com/@firt/service-workers-replacing-appcache-a-sledgehammer-to-crack-a-nut-5db6f473cc9b#.sdp7iqxc3)
(Maximiliano Firtman - Apr 11, 2016)

[Progressive Web Apps — Offline And Add To Home Screen](https://medium.com/@greenido/progressive-web-apps-offline-and-add-to-home-screen-2187a2487a5c#.7m52kq892)
(Ido Green - Mar 28, 2016)

[The web on my phone](https://adactio.com/journal/10410)
(Jeremy Keith - Mar 23, 2016)

[The copy & paste guide to your first Service Worker](https://remysharp.com/2016/03/22/the-copy--paste-guide-to-your-first-service-worker)
(Remy Sharp - Mar 22, 2016)

[Service Workers: Save your User's Data using the Save-Data Header](http://www.deanhume.com/Home/BlogPost/service-workers--save-your-users-data-using-the-save-data-header/10139)
(Dean Hume - Mar 8, 2016)

[Service Worker notes](https://adactio.com/journal/10186)
(Jeremy Keith - Feb 4, 2016)

[Making A Service Worker: A Case Study](https://www.smashingmagazine.com/2016/02/making-a-service-worker/)
(Lyza Danger Gardner - Feb 1, 2016)

[Create a really, really simple offline page using Service Workers](http://deanhume.com/home/blogpost/create-a-really--really-simple-offline-page-using-service-workers/10135)
(Dean Hume - Jan 25, 2016)

[Offline Web Applications: Using IndexedDB & Service Worker](https://www.udacity.com/course/offline-web-applications--ud899)
(Michael Wales - Jan 20, 2016)

[Building Offline Sites with ServiceWorkers and UpUp](https://dev.opera.com/articles/offline-with-upup-service-workers/)
(Tal Ater - Jan 19, 2016)

[Instant Web Application](https://glebbahmutov.com/blog/instant-web-application/)
(Gleb Bahmutov - Dec 24, 2015)

[Introducing Background Sync](https://developers.google.com/web/updates/2015/12/background-sync)
(Jake Archibald - 2015)

[Beyond Offline](https://hacks.mozilla.org/2015/12/beyond-offline/)
(Salvador de la Puente González - Dec 21, 2015)

[Getting started with the Service Worker Toolbox ](http://deanhume.com/Home/BlogPost/getting-started-with-the-service-worker-toolbox/10134)
(Dean Hume - Dec 17, 2015)

[ServiceWorker Cookbook](https://serviceworke.rs/)
(by Mozilla)

[Offline Web Applications with CouchDB, PouchDB and Ember CLI](https://teamgaslight.com/blog/offline-web-applications-with-couchdb-pouchdb-and-ember-cli)
(Chris Moore - Dec 10, 2015)

[A Hoodie Case Study: How minutes.io does offline](http://hood.ie/blog/minutes-offline-case-study)
(Alex Feyerke - Dec 1, 2015)

[Reducing Single Point of Failure using Service Workers](http://calendar.perfplanet.com/2015/reducing-single-point-of-failure-using-service-workers/)
(Dean Hume - Dec 1, 2015)

[Building realtime collaborative offline-first apps with React, Redux, PouchDB and WebSockets](http://blog.yld.io/2015/11/30/building-realtime-collaborative-offline-first-apps-with-react-redux-pouchdb-and-web-sockets/)
(Pedro Teixeira - Nov 30, 2015)

[Cache-limiting in Service Workers …again](https://adactio.com/journal/9888)
(Jeremy Keith - Nov 29, 2015)

[Introducing Pokedex.org: a progressive webapp for Pokémon fans](http://www.pocketjavascript.com/blog/2015/11/23/introducing-pokedex-org)
(Nolan Lawson - Nov 23, 2015)

[Cache-limiting in Service Workers](https://adactio.com/journal/9844)
(Jeremy Keith - Nov 19, 2015)

[Offline Recipes for Service Workers](https://hacks.mozilla.org/2015/11/offline-service-workers/)
(David Walsh - Nov 19, 2015)

[Instant Loading Web Apps With An Application Shell Architecture](https://medium.com/google-developers/instant-loading-web-apps-with-an-application-shell-architecture-7c0c2f10c73)
(Addy Osmani - Nov 17, 2015)

[An Offline Experience with Service Workers](http://brandonrozek.tumblr.com/post/135657690564/service-workers)
(Brandon Rozek - Nov 14, 2015)

[Building Flipkart Lite: A Progressive Web App](https://medium.com/@AdityaPunjani/building-flipkart-lite-a-progressive-web-app-2c211e641883)
(Aditya Punjani - Nov 11, 2015)

[Your first offline web app](https://developers.google.com/web/fundamentals/getting-started/codelabs/offline/)
(Chrome Developer Team - 2015)

[Making a Simple Site Work Offline with ServiceWorker](https://css-tricks.com/serviceworker-for-offline/)
(Nicolas Bevacqua - Nov 10, 2015)

[My first Service Worker](https://medium.com/@adactio/my-first-service-worker-5e5af0b1bdbb#.tsjcjzk2n)
(Jeremy Keith - Nov 7, 2015)

[Building an offline page for theguardian.com](https://www.theguardian.com/info/developer-blog/2015/nov/04/building-an-offline-page-for-theguardiancom)
(Oliver Joseph Ash - Nov 4, 2015)

[Creating Offline-First Web Apps with Service Workers](https://auth0.com/blog/2015/10/30/creating-offline-first-web-apps-with-service-workers/)
(Ryan Chenkie - Oct 30, 2015)

[Cache sandboxed HTTP requests with Service Worker](https://medium.com/@roman01la/cache-sandboxed-http-requests-with-service-worker-6bb3801237d1#.3jjklzohz)
(Roman Liutikov - Oct 26, 2015)

[The offline experience (or, saying goodbye to imperative data fetching)](https://medium.com/@d.gieselaar/the-offline-experience-or-saying-goodbye-to-imperative-data-fetching-9b2fa487eea7)
(Dario Gieselaar - Oct 25, 2015)

[ServiceWorker: Revolution of the Web Platform](https://ponyfoo.com/articles/serviceworker-revolution)
(Nicolas Bevacqua - Oct 21, 2015)

[Taking the web offline with service workers](https://mobiforge.com/design-development/taking-web-offline-service-workers)
(Ruadhan O'Donoghue - Oct 21, 2015)

[Using Service Workers](https://developer.mozilla.org/en-US/docs/Web/API/Service_Worker_API/Using_Service_Workers)
(MDN - Oct 18, 2015)

[Don’t Wait for ServiceWorker: Adding Offline Support with One-Line](https://davidwalsh.name/dont-wait-serviceworker-adding-offline-support-oneline)
(Kenneth Ormandy - Oct 14, 2015)

[Service Workers in Production](https://developers.google.com/web/showcase/2015/service-workers-iowa)
(Jeff Posnick - Oct 01, 2015)

[How Do We Get It Done, Now?](http://alistapart.com/column/how-do-we-get-it-done-now)
(Lyza Danger Gardner - Sep 30, 2015)

[The Role of Workers and Offline Cache](https://unoyunodiez.com/2015/09/07/modern-mobile-web-development-breaking-the-rules-beating-delays-improving-responsiveness-and-performance-ii/)
(Sep 7, 2015)

[Let's make Offline Web Applications secure!](http://sakurity.com/blog/2015/07/28/appcache.html)
(Egor Homakov - Jul 28, 2015)

[Service Worker Meeting Highlights](https://blog.wanderview.com/blog/2015/07/28/service-worker-meeting-highlights/)
(Ben Kelly - Jul 28, 2015)

[Q&A: Offline first, not just mobile first says Couchbase](http://www.cbronline.com/news/mobility/apps/qa-offline-first-not-just-mobile-first-says-couchbase-4609613)
(James Nunns - Jun 26, 2015)

[Why offline-first matters, and what developers should know about it](https://logbook.hanno.co/offline-first-matters-developers-know/)
(Marcel Kalveram - Jun 2, 2015)

[Getting Appcache’s Fallback to work, crossbrowser](https://www.iandevlin.com/blog/2015/06/html5/getting-appcaches-fallback-to-work-crossbrowser)
(Ian Devlin - Jun 1, 2015)

[Mobile Apps Offline Support](https://www.infoq.com/articles/mobile-apps-offline-support)
(Gustavo Machado - May 29, 2015)

[Making react-europe.org work offline with Service Workers and free SSL from Cloudflare](https://medium.com/@patcito/making-react-europe-org-work-offline-with-service-workers-f54fb0457048)
(Patrick Aljord - May 14, 2015)

[Offline Data Synchronization in Ionic](https://frontmag.no/artikler/utvikling/offline-data-synchronization-ionic)
(Marco Fernandes - Apr 29, 2015)

[Offline Data in the Browser](http://www.levvel.io/blog-post/offline-data-in-the-browser/)
(Assaf Weinberg - Mar, 2015)

[Offline: When Your Apps Can’t Connect to the Internet](https://uxdesign.cc/offline-93c2f8396124)
(Daniel Sauble - Mar 29, 2015)

[Offline is not just another mobile feature](http://betanews.com/2015/03/04/offline-is-not-just-another-mobile-feature/)
(Chuck Ganapathi - Mar 4, 2015)

[Offline-first, fast, with the sw-precache module](https://developers.google.com/web/updates/2015/02/offline-first-with-sw-precache)
(Jeff Posnick - Feb 23, 2015)

[Offline is Not a Feature](http://www.formotus.com/17221/blog-mobility/offline-is-not-a-feature)
(Feb 16, 2015)

[The Right and Wrong Strategies When Taking Your App Offline](http://appdevelopermagazine.com/2356/2015/2/9/The-Right-and-Wrong-Strategies-When-Taking-Your-App-Offline/)
(Martin Heller - Feb 9, 2015)

[Three takeaways for web developers after two weeks of painfully slow internet](https://byrslf.co/three-takeaways-for-web-developers-after-two-weeks-of-painfully-slow-internet-9e7f6d47726e)
(Gabor Lenard - Jan 25, 2015)

[Offline first: as simple as unplug & play?](http://www.ae.be/blog-en/offline-first-simple-unplug-play/)
(Thomas Anciaux - Jan 15, 2015)

[A simple ServiceWorker app](http://blog.lamplightdev.com/2015/01/06/A-Simple-ServiceWorker-App/)
(Chris Haynes - Jan 6, 2015)

[ServiceWorker is available in Chrome 40 beta](https://plus.google.com/+IlyaGrigorik/posts/WPZsWr4QGqR)
(Ilya Grigorik - Dec 11, 2014)

[PSA: Service Workers are Coming](http://infrequently.org/2014/12/psa-service-workers-are-coming/)
(Alex Russell - Dec 11, 2014)

[The offline cookbook](https://jakearchibald.com/2014/offline-cookbook/)
(Jake Archibald - Dec 9, 2014)

[The next UX challenge on the web: gaining offline trust](https://www.christianheilmann.com/2014/12/08/the-next-ux-challenge-on-the-web-gaining-offline-trust/)
(Christian Heilmann -  Dec 8, 2014)

[Service Worker Recipes](https://github.com/GoogleChrome/samples/tree/gh-pages/service-worker)
(Cesar William Alvarenga - Dec 8, 2014)

[Introduction to Service Worker](https://developers.google.com/web/fundamentals/getting-started/primers/service-workers)
(Matt Gaunt - Dec 1, 2014)

[offline decentralized single sign-on in the browser](http://substack.net/offline_decentralized_single_sign_on_in_the_browser)
(James 'substack' Halliday - Nov 27, 2014)

[Offline Web Apps with Meteor](https://subvisual.co/blog/posts/45-offline-web-apps-with-meteor)
(Gabriel Poça, Nov 26, 2014)

[How to build web applications that can work offline with PouchDB?](http://www.theodo.fr/blog/2014/11/how-to-build-web-applications-work-offline-pouchdb/)
(Yann Jacquot - Nov 25, 2014)

[Making Your App Work Offline: Tips and Cautionary Tales](https://quickleft.com/blog/making-your-app-work-offline-tips-and-cautionary-tales/)
(David Aragon  - Nov 11, 2014)

[How Google and Mozilla are aiming to make web apps shine offline](http://www.techrepublic.com/article/how-google-and-mozilla-are-aiming-to-make-web-apps-work-as-well-offline-as-on/)
(Nick Heath - Oct 30, 2014)

[Offline-first is people-first](https://nolanlawson.com/2014/10/03/offline-first-is-people-first/)
(Nolan Lawson - Oct 3, 2014)

[Introducing Hoodie: Full Stack App Development for Front-End Developers](https://www.toptal.com/front-end/introducing-hoodie-full-stack-app-development-for-front-end-developers)
(Alvaro Oliveira - Sep 24, 2014)

[Offline-first: a new paradigm in web development](ttps://translate.google.com/translate?hl=en&sl=nl&tl=en&u=http%3A%2F%2Fwww.e-sites.nl%2Fblog%2F400-offline-first-een-nieuw-paradigma-in-web-development.html)
(Boye Oomens - Sep 16, 2014)

[Building A Simple Cross-Browser Offline To-Do List With IndexedDB And WebSQL](https://www.smashingmagazine.com/2014/09/building-simple-cross-browser-offline-todo-list-indexeddb-websql/)
(Matt Andrews - Sep 2, 2014)

[Introducing MakeDrive](http://blog.humphd.org/introducing-makedrive/)
(David Humphrey - Aug 25, 2014)

[Worklight Authentication done right with AngularJs](https://medium.com/@papasimons/worklight-authentication-done-right-with-angularjs-768aa933329c)
(Gideon Simons - Aug 22, 2014)

[Taking your Worklight apps offline](https://medium.com/@papasimons/taking-your-worklight-apps-offline-e8c2c2d8533a)
(Gideon Simons - Aug 19, 2014)

[Working offline](https://developer.mozilla.org/en-US/Apps/Fundamentals/Offline)
(Aug 12, 2014)

[Offline First - the new paradigm in web development done Neptune style](http://scn.sap.com/community/developer-center/front-end/blog/2014/08/05/offline-first--the-new-paradigm-in-web-development-done-neptune-style) (Njål Stabell - Augt 5, 2014)

[Breaking Development: Offline First is the new Mobile First](http://www.lukew.com/ff/entry.asp?1902)
(Luke Wroblewski - Jul 29, 2014)

[Offline Patterns](https://www.ibm.com/developerworks/community/blogs/worklight/entry/offline_patterns?lang=en)
(Carlos Andreu - Jul 3, 2014)

[Offline Web Apps,Web Storage,IndexedDB,AppCache,File API Futures](https://www.youtube.com/watch?v=pklpK55uQmE&feature=youtu.be)
(Ali Alabbas - May 21, 2014)

[Service Workers: Offline Now(ish)!](https://www.youtube.com/watch?v=BKD7ZLRi9HI)
(Alex Russell - May 21, 2014)

[Service Worker - first draft published](https://jakearchibald.com/2014/service-worker-first-draft/)
(Jake Archibald - May 8, 2014)

[The BMEAN Stack and Offline-First Design](http://dailyjs.com/2014/04/10/bmean/)
(Daishi Kato - Apr 11, 2014)

[Do HTML5 apps have to be online all the time?](https://www.christianheilmann.com/2014/03/23/do-html5-apps-have-to-be-online-all-the-time/)
(Christian Heilmann - Mar 23rd, 2014)

[Building an Offline First App with PouchDB](https://www.sitepoint.com/building-offline-first-app-pouchdb/)
(Tiffany Brown - Mar 10, 2014)

[Introduction to Offline Web Apps on the Kindle Fire](https://developer.amazon.com/public/community/post/Tx21KG2QC7O71S9/Introduction-to-Offline-Web-Apps-on-the-Kindle-Fire.html)
(Russell Beattie - Jan 30, 2014)

[Designing Offline-First Web Apps](http://alistapart.com/article/offline-first)
(Alex Feyerke - Dec 4, 2013)

[Offline First: Learning from native experiences](https://medium.com/@dalmaer/offline-first-learning-from-native-experiences-4a778ce8a445)
(Dion Almaer - Dec 4, 2013)

[Offline First](http://www.kryogenix.org/days/2013/11/06/offline-first/)
(Stuart Langridge - Nov 6, 2013)

[Making the web work offline first](http://marcelkalveram.com/2013/11/developing-for-offline-first/)
(Marcel Kalveram - Nov 20, 2013)

[Say Hello to Offline First](http://hood.ie/blog/say-hello-to-offline-first.html)
(Dan Lash - Nov 5, 2013)

[Offline First: Your Next Progressive Enhancement Technique?](https://www.sitepoint.com/offline-first-next-progressive-enhancement-technique/)
(Craig Buckler - Oct 30, 2013)

[Appcache, not so much a douchebag as a complete pain in the #$%^](http://www.webdirections.org/blog/appcache-not-so-much-a-douchebag-as-a-complete-pain-in-the/)
(John Allsopp - Jul 19, 2013)

[Using HTML5 AppCache with Single Page Applications](http://techblog.dorogin.com/2013/03/using-html5-appcache-with-single-page-apps.html)
(Sergei Dorogin - Mar 29, 2013)

[Application Cache is a Douchebag](http://alistapart.com/article/application-cache-is-a-douchebag)
(Jake Archibald - May 08, 2012)

[Appcache Facts](http://mmariani.github.io/appcachefacts/)

[Chrome Offline Apps](https://developer.chrome.com/apps/offline_apps)

[Offline Support is Valuable, and You Can’t Add it Later](http://aanandprasad.com/articles/offline/)
(Aanand Prasad - Aug 13, 2011)

[Offline-first web app design](https://unhosted.org/practice/29/Offline-first-web-app-design.html)
(Michiel B. de Jong - 2011)

[5 Reasons Why There are no Killer Offline Web Applications](https://www.sitepoint.com/killer-offline-web-applications/)
(Craig Buckler - Feb 16, 2010

[Offline Web Applications](https://hacks.mozilla.org/2010/01/offline-web-applications/)
(Paul Rouget - Jan 7, 2010)

[Let's take this offline](http://diveintohtml5.info/offline.html)
(Mark Pilgrim)


## Presentations

### Videos

[Offline is the new black](https://vimeo.com/171317290)
(Max Stoiber - Jun 19, 2016)

[Service workers at scale with Facebook and Flipkart](https://www.youtube.com/watch?v=fGTUIlEM0m8&feature=youtu.be&t=2200)
(Owen Campbell-Moore, Aditya Punjani and Nate Schloss - May 20, 2016)

[Instant Loading: Building offline-first Progressive Web Apps](https://www.youtube.com/watch?v=cmGr0RszHc8)
(Jake Archibald - May 20, 2016)

[Offline First – the good parts](https://www.youtube.com/watch?v=NEferkZOGV4&feature=youtu.be)
(Gregor Martynus - May 12, 2016)

[Offline Web Applications: Using IndexedDB & Service Worker](https://www.udacity.com/course/offline-web-applications--ud899)

[Totally Tooling Tips: Offline Support](https://www.youtube.com/watch?v=OBfLvqA_E4A)
(Addy Osmani & Matt Gaunt - Apr 27, 2016)

[Using Service Workers in Ember](http://confreaks.tv/videos/emberconf2016-using-service-workers-in-ember)
(John Kleinschmidt - Mar 29, 2016)

[Offline-First Apps with PouchDB](https://www.youtube.com/watch?v=7L7esHWAjSU)
(Bradley Holt - Dec 11, 2015)

[Worker as a Service](https://www.youtube.com/watch?v=5LAMbIlwilc)
(Ola Gasidlo - Nov 19, 2015)

[Taking Your Web Apps Offline](https://www.youtube.com/watch?v=EZF1EfjQlbo)
(Mike Nitchie - Nov 16, 2015)

[There is a client-side proxy (ServiceWorker) in your browser!](https://www.youtube.com/watch?v=etACK2qbHfc)
(Ilya Grigorik - Nov 16, 2015)

[OnConnectionLost: The life of an offline web application](https://www.youtube.com/watch?v=rw8Q9ZLDkEs)
(Stefanie Grewenig - Oct 12, 2015)

[Offline First and Service Workers](https://www.youtube.com/watch?v=TGwjgmAqNRo)
(Maximilian Stoiber - Oct 5, 2015)

[Offline First Podcast](https://www.youtube.com/watch?v=tilH8jgLrXQ)
(The Web Platform Podcast - Sep 8, 2015)

[The Once & Future Web](https://www.youtube.com/watch?v=RQQNNP8tFro)
(Jake Archibald - Jul 28, 2015)

[Go Offline](https://www.youtube.com/watch?v=BucGrYACJdQ)
(Rob Dodson - Jun 29, 2015)

[Taking Ember Offline](https://www.youtube.com/watch?t=20&v=VhZS4n2DMyU)
(John Kleinschmidt - Jun 16, 2015)

[Holy sync](https://www.youtube.com/watch?v=Yp1h3cd8dsg)
(Eugenio Marletti - May 5, 2015)

[Making Offline Suck Less with Service Workers](https://www.youtube.com/watch?v=nqecpa6MtZ0)
(Bret Little - Mar 28, 2015)

[Say Hello to Offline First](https://www.youtube.com/watch?v=ZsMS_sviJs0)
(Ola Gasidlo - Mar 26, 2015)

[The UX Of Offline-First](https://vimeo.com/125479288)
(Jake Archibald - Mar 18, 2015)

[The Web's Future is Offline](https://vimeo.com/120474703)
(John Allsopp - Feb 24, 2015)

[Building Offline First Applications with Backbone](https://www.youtube.com/watch?v=Zb01eNS6-no)
(Gregor Martynus - Dec 17, 2014)

[Working connected to create offline](https://www.youtube.com/watch?v=fj49cSQ986k)
(Christian Heilmann - Nov 24, 2014)

[The ServiceWorker is coming, look busy!](https://www.youtube.com/watch?v=Rr2vXDIVerI)
(Jake Archibald - Sep 21, 2014)

[The Next Challenge of the Web is Us](https://www.youtube.com/watch?v=QPRqQH_30hU&t=22m53s)
(Christian Heilmann - Aug 1, 2014)

[Offline First](https://www.youtube.com/watch?v=dPz_5-MEvcg)
(Alex Feyerke - Jul 17, 2014)

[The ServiceWorker: The network layer is yours to own](https://www.youtube.com/watch?v=4uQMl7mFB6g)
(Jake Archibald - Jun 25, 2014)

[Offline Web Applications](https://www.youtube.com/watch?v=AbixY3W8ayo)
(Jan Jongboom - May 23, 2014)

[The Offline Web](https://www.youtube.com/watch?v=nnLBdFLo2fc)
(Dale Harvey - Jun 20, 2014)

[Bring NoSQL to your mobile](https://www.youtube.com/watch?v=qfC90DQEoeY)
(Patrick Heneise - Dec 16, 2013)

[Network connectivity: optional](https://www.youtube.com/watch?v=Z7sRMg0f5Hk)
(Jake Archibald - Dec 4, 2013)

[Surviving the Offline Apocalypse](https://www.youtube.com/watch?v=Qg75x08Mtcs)
(John Kleinschmidt - Nov 29, 2014)

[Offline First](https://www.youtube.com/watch?v=7mdG-iAizVc)
(Jan Lehnardt - May 27, 2013)

[Offline rules: Bleeding edge web standards at the Financial Times](https://vimeo.com/64201695)
(Andrew Betts - Apr , 2013)

[What's the right way to build offline into a web application?](https://www.youtube.com/watch?v=Oic22dQMRXQ)
(Jake Archibald, Mark Christian, Alex Russell and Jonas Sicking - Feb 9, 2013)

[AppCache: Douchebag](https://www.youtube.com/watch?v=cR-TP6jOSQM)
(Jake Archibald - Jan 20, 2013)

[Application Cache And Local Storage](https://www.youtube.com/watch?v=ceODU6z4-yc)
(Scott Davis - Dec 7 , 2012)

[Offline Rules](https://www.youtube.com/watch?v=RrGo1Sz4IgQ)
(Andrew Betts - Dec 4, 2012)

[Building Web Apps of the future. Tomorrow, today and yesterday.](https://www.youtube.com/watch?v=O3AukCYymEU)
(Paul Kinlan - Nov 12, 2012)

[Taking Web Apps Offline](https://www.youtube.com/watch?v=ejcJmeewtd4)
(Kevin Markman - Nov 5, 2012)

[Building Offline Web Apps with HTML5](https://www.youtube.com/watch?v=W41mvarupH0)
(Jonathan Stark - Jul 25, 2012)

[Getting off(line): appcache, localStorage for HTML5 apps that work offline](https://www.youtube.com/watch?v=dN8e-QdYyCk)
(John Allsopp - Jul 3, 2012)

### Slides

[Offline, progressive, and multithreaded](https://nolanlawson.github.io/fronteers-2016/#/)
(Nolan Lawson - Oct 10, 2016)

[Rise of the Web Workers](http://blog.nparashuram.com/2016/09/rise-of-web-workers-nationjs.html)
(Parashuram N - Sep 16, 2016)

[Building an Offline Page for theguardian.com](https://speakerdeck.com/oliverjash/building-an-offline-page-for-theguardian-dot-com-jsconf-budapest-may-2016)
(Oliver Joseph Ash - May 14, 2016)

[Go offline with Service Workers](https://docs.google.com/presentation/d/1crh5m2aDdZPAL07Zo1FtuAliwwghW6FMOEtXviA_BZo/edit#slide=id.p)
(Emanuel Kluge - 2016)

[Building an Offline Page for theguardian.com](https://speakerdeck.com/oliverjash/building-an-offline-page-for-theguardian-dot-com-london-web-perf-march-2016)
(Oliver Joseph Ash - Mar, 2016)

[Insanely fast rendering w/ Service Workers and Early Flushing](https://speakerdeck.com/mstuart/service-workers-and-early-flushing)
(Mark Stuart - Dec 14, 2015)

[Offline-First Apps with PouchDB at Node.js Interactive](https://speakerdeck.com/bradleyholt/offline-first-apps-with-pouchdb-at-node-dot-js-interactive)
(Bradley Holt - Dec 9, 2015)

[Developing for Offline First Mobile Experiences](http://www.slideshare.net/NicRaboy/developing-for-offline-first-mobile-experiences)
(Nic Raboy - Dec 2, 2015)

[At your service! - More than appcache uses for Service Workers](http://delapuente.github.io/presentations/at-your-service/index.html)
(Salvador de la Puente González - Oct 21, 2015)

[Offline First (Web) Apps](https://speakerdeck.com/espylaub/offline-first-web-apps-beuth-hochschule-berlin)
(Alex Feyerke - Oct 20, 2015)

[Offline-First Web Applications](https://docs.google.com/presentation/d/1gDGIyGtXMSmtT8WsyXj7ADyUjNV679T1BF5QGEKqooc/mobilepresent)
(Peter Müller - 2015)

[Server in your Client - Service Workers' rise to fame](http://slides.com/flaki/server-in-the-client#/)
(Szmozsánszky István - Oct 7, 2015)

[Offline-First Web Applications](https://docs.google.com/presentation/d/1gDGIyGtXMSmtT8WsyXj7ADyUjNV679T1BF5QGEKqooc/mobilepresent?slide=id.gb7f243163_0_53)
(Peter Müller - Jun 27, 2015)

[Offline-first mobile web apps with PouchDB, IBM Cloudant, and IBM Bluemix](http://www.slideshare.net/IBMBluemix/offlinefirst-mobile-web-apps-with-pouchdb-ibm-cloudant-and-ibm-bluemix)
(Bradley Holt - Jun 22, 2015)

[Building Offline-Enabled Apps with PouchDB](https://speakerdeck.com/bradleyholt/building-offline-enabled-apps-with-pouchdb-at-php-tek-2015)
(Bradley Holt - May 20, 2015)

[Naked and afraid Offline Mobile](http://www.slideshare.net/ColdFusionConference/naked-and-afraid-48288396)
(Matt Woodward - May 18, 2015)

[Offline first, the painless way](http://de.slideshare.net/MarcelKalveram/offline-first-the-painless-way)
(Marcel Kalveram - May 17, 2015)

[noBackend e Offline First: focusing on creating experiences (pt-br)](https://speakerdeck.com/joselitojunior1/nobackend-e-offline-first-foque-em-criar-experiencias-number-frontinfortaleza)
(Joselito Júnior - May 16, 2015)

[HOLY SYNC: a sane approach to offline-first cross-platform data syncing](https://speakerdeck.com/takhion/holy-sync-a-sane-approach-to-offline-first-cross-platform-data-syncing)
(Eugenio Marletti - Apr 10, 2015)

[Service Worker and the Offline Web](https://slidr.io/lewiscowper/service-worker-and-the-offline-web-lightning-talk)
(Lewis Cowper - Mar 7, 2015)

[Service Workers on vacay...](https://docs.google.com/presentation/d/1LUuMYDi1ssmslQKnnX3cwrdLVy2YCqyww3PBtqEP0q8/edit)
(Natasha Rooney - Mar 6, 2015)

[TGIF - Offline-first](http://codekult.github.io/tgif-offline-first/)
(Diego Calderón - Jan 30, 2015)

[ServiceWorkers and High Performance Offline Apps](https://huffduffer.com/AlanDalton/202718)
(AlanDalton - Jan 13, 2015)

[Leveraging hood.ie to build for the offline state](http://de.slideshare.net/MarcelKalveram/codemotion-talk-41932602)
(Marcel Kalveram - Nov 24, 2014)

[Let's Take Drupal Offline!](http://www.slideshare.net/dickolsson/lets-take-drupal-offline-41650712)
(Dick Olsson - Nov 17, 2014)

[Offline-first web apps - Velocity EU 2014](http://www.slideshare.net/andrewsmatt/velocity-eu-2014)
(Matt Andrews - Nov 17, 2014)

[Discover ServiceWorker](http://www.slideshare.net/sandropaganotti/discover-serviceworker)
(Sandro Paganotti - Nov 16, 2014)

[Offline first <3](https://speakerdeck.com/zoepage/ayb14-offline-first-1)
(Ola Gasidlo - Oct 17, 2014)

[Scaling Down: The Offline First Story](https://speakerdeck.com/wohali/scaling-down-the-offline-first-story)
(Joan Touzet - Sep 16, 2014)

[Status Web Offline](https://www.infoq.com/presentations/status-web-offline)
(Caolan McMahon -  Aug 21, 2014)

[Look Ma, No Connections! Building Offline-capable Web Apps with HTML5](https://www.infoq.com/presentations/html5-offline-storage)
(Bijan Vaez -  Aug 1, 2014)

[Say hello to offline first!](https://speakerdeck.com/zoepage/say-hello-to-offline-first)
(Ola Gasidlo - May 19, 2014)

[Offline First (Web) Apps](https://speakerdeck.com/espylaub/offline-first-web-apps)
(Alex Feyerke - May 2, 2014)

[Offline First – Made Simple!](https://speakerdeck.com/gr2m/offline-first-made-simple)
(Gregor Martynus - Apr 24, 2014)

[Offline First Re-Imagining Web Development For The Real World](https://qconlondon.com/london-2014/dl/qcon-london-2014/slides/CaolanMcMahon_OfflineFirstReImaginingWebDevelopmentForTheRealWorld.pdf)
(Caolan McMahon - Mar, 2014)

## Tools

[Kinto](http://www.kinto-storage.org/): Add synchronisation and sharing abilities to your Web application in seconds.

[bottle-service](https://github.com/bahmutov/bottle-service): Instant web applications restored from ServiceWorker cache.

[react-boilerplate](https://github.com/mxstbr/react-boilerplate): Quick setup for performance orientated, offline-first React.js applications.

[Haywire](https://github.com/omnia-salud/haywire): A minimal javascript library for network issues detection.

[sw-toolbox](https://github.com/GoogleChrome/sw-toolbox): A collection of tools for service workers.

[UpUp](https://www.talater.com/upup/): An Offline First library designed to be the easiest way to add offline capabilities to a site.

[simple-serviceworker-tutorial](https://github.com/jakearchibald/simple-serviceworker-tutorial): A really simple ServiceWorker example, designed to be an interactive introduction to ServiceWorker.

[Hyperboot](https://github.com/substack/hyperboot): Offline webapp bootloader.

[MakeDrive](https://github.com/mozilla/makedrive): A cloud-based Dropbox® equivalent for browser filesystems. Designed for use with Mozilla Webmaker tools and services.
See the [Mozilla MakeDrive Wiki page](https://wiki.mozilla.org/Webmaker/MakeDrive) for background info.

[ApplicationCache](https://developer.mozilla.org/en-US/docs/Web/HTML/Using_the_application_cache): HTML5 provides an application caching mechanism that lets web-based applications run offline.

[IndexedDB](https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API): IndexedDB is an API for client-side storage of significant amounts of structured data and for high performance searches on this data using indexes.

[ServiceWorkers](https://developer.mozilla.org/en-US/docs/Web/API/Service_Worker_API): A Service Worker acts like a proxy on the client. For page requests and requests made by pages, you get a fetch event that you can respond to yourself, creating offline experiences.

[localForage](https://github.com/localForage/localForage): Offline storage, improved. Wraps IndexedDB, WebSQL, or localStorage using a simple but powerful API.

[remoteStorage](https://remotestorage.io/): remoteStorage enabled apps automatically sync your data across all of your devices, from desktop to tablet to smartphone, and even your TV.

[pouchdb](https://pouchdb.com/): PouchDB is an open-source JavaScript database inspired by Apache CouchDB that is designed to run well within the browser.

[Offline.js](http://github.hubspot.com/offline/docs/welcome/): An awesome JavaScript library to improve the experience of your app when your users lose connection.

[Hoodie](http://hood.ie/): Hoodie is an Offline First and noBackend architecture for frontend-only web apps on the web and on iOS.

[Offline States](http://offlinestat.es/): What show applications when we have not internet connection.

[appCache Nanny](https://github.com/gr2m/appcache-nanny):  JavaScript APIs for appCache

## Books
[Building Progressive Web Apps](http://shop.oreilly.com/product/0636920052067.do)
(by Tal Ater)

[Client-Side Data Storage](http://shop.oreilly.com/product/0636920043676.do)
(by Raymond Camden)

[Offline First: The book (draft)](http://www.webdirections.org/offlineworkshop/ibooksDraft.pdf)
(by John Allsopp)

[Pro HTML5 Programming - Chapter 12: Creating HTML5 Offline Web Applications](http://apress.jensimmons.com/v5/pro-html5-programming/ch12.html)
(by Peter Lubbers, Brian Albers and Frank Salim)

## Showcase
[Minutes.io](https://minutes.io): Awesome offline first minute taking app built with [Hoodie](http://hood.ie/).

[2048](https://gabrielecirulli.github.io/2048/): The original 2048 is a great game to pin to your homescreen. 

[hospitalrun.io](http://hospitalrun.io/): Open source software for developing world hospitals.

[pokedex.org](https://www.pokedex.org/): An index of Pokémon, built as a client-side JavaScript webapp. Powered by ServiceWorker, PouchDB, virtual-dom, and web workers.

[Soundslice](https://www.soundslice.com/): Learn and teach music better with interactive notation with [offline mode](https://www.soundslice.com/blog/29/introducing-soundslice-offline-mode/).

## Who to Follow
- [Matthew Riley](https://github.com/tofumatt): Works at mozilla, creator of localForage (localstroage, IndexedDb and WebSQL Wrapper)
- [Jake Archibald](https://github.com/jakearchibald): Self described service worker fanatic, works at google helping make offline web apps a thing.

## Contributing
Sharing, suggestions and contributions are always welcome! If you want to contribute, you are highly encouraged to do so. Please read the [contribution guidelines](CONTRIBUTING.md).

Thanks to all [contributors](https://github.com/pazguille/offline-first/graphs/contributors).

## Maintained by
- Guille Paz (Front-end developer | Web standards lover)
- E-mail: [guille87paz@gmail.com](mailto:guille87paz@gmail.com)
- Twitter: [@pazguille](https://twitter.com/pazguille)
- Web: [https://pazguille.me/](https://pazguille.me/)

## License
[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
