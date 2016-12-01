Headless Browsers
================

### A list of (almost) all headless web browsers in existence

*A web browser without a graphical user interface, controlled programmatically. Used for automation, testing, and other purposes.*

## Browser engines

*These browser engines fully render web pages or run JavaScript in a virtual DOM*

Name  | About  | Supported Languages | License
:------------ |:---------------| :----- | :-----------
|[Chromium Embedded Framework](https://bitbucket.org/chromiumembedded/cef) |CEF is a open source project based on the Google Chromium project.        |   JavaScript | BSD |
|[Erik](https://github.com/phimage/Erik) | Headless browser on top of Kanna and WebKit.|Swift| MIT |
|[jBrowserDriver](https://github.com/machinepublishers/jbrowserdriver) | A Selenium-compatible headless browser which is written in pure Java. WebKit-based. Works with any of the Selenium Server bindings.|Java| Not specified |
|[PhantomJS](http://phantomjs.org/) | PhantomJS is a headless WebKit scriptable with a JavaScript API. It has fast and native support for various web standards: DOM handling, CSS selector, JSON, Canvas, and SVG. | JavaScript, Python, Ruby, Java, C#, Haskell, Objective-C, Perl, PHP, R(via [Selenium](http://docs.seleniumhq.org/about/platforms.jsp#programming-languages))  | BSD-3 Clause |
|[Splash](https://github.com/scrapinghub/splash) | Splash is a javascript rendering service with an HTTP API. It's a lightweight browser with an HTTP API, implemented in Python using Twisted and QT.|Any| BSD-3 Clause |

## Multi drivers

*These libraries can control multiple browser engines (typically using Selenium)*

Name  | About  | Supported Languages | License
:------------ |:---------------| :----- | :-----------
|[CasperJS](http://casperjs.org/) | CasperJS is an open source navigation scripting & testing utility written in Javascript for the PhantomJS WebKit headless browser and SlimerJS (Gecko).        |   JavaScript | MIT |
|[Geb](http://www.gebish.org/) | Geb is a Groovy interface to WebDriver.|Groovy| Apache |
|[Selenium](http://seleniumhq.org) | Selenium is a suite of tools to automate web browsers across many platforms.|JavaScript, Python, Ruby, Java, C#, Haskell, Objective-C, Perl, PHP, R| Apache |
|[Splinter](https://splinter.readthedocs.io/en/latest/) | Splinter is an open source tool for testing web applications using Python. It lets you automate browser actions, such as visiting URLs and interacting with their items.|Python| - |
|[SST](https://pypi.python.org/pypi/sst/0.2.4) | SST (selenium-simple-test) is a web test framework that uses Python to generate functional browser-based tests.|Python| - |
|[Watir](https://watir.com/) | The most elegant way to use Selenium WebDriver with ruby.|Ruby| MIT |

## PhantomJS drivers

*These libraries control PhantomJS*

Name  | About  | Supported Languages | License
:------------ |:---------------| :----- | :-----------
|[Ghostbuster](https://github.com/joshbuddy/ghostbuster) | Automated browser testing via phantom.js, with all of the pain taken out! That means you get a real browser, with a real DOM, and can do real testing!|JavaScript| Not specified |
|[jedi-crawler](https://github.com/spacenick/jedi-crawler) | Lightsabing Node/PhantomJS crawler; scrape dynamic content : without the hassle|JavaScript| Not specified |
|[Lotte](https://github.com/StanAngeloff/lotte)| Lotte is a headless, automated testing framework built on top of PhantomJS and inspired by Ghostbuster. | JavaScript | MIT |
|[phantompy](https://github.com/niwinz/phantompy) | Phantompy is a headless WebKit engine with powerful pythonic api build on top of Qt5 Webkit|Python| LGPL-2.1 |
|[X-RAY](https://github.com/lapwinglabs/x-ray) | Supports strings, arrays, arrays of objects, nested object structures, selector API, pagination, crawler, concurrency, throttles, delays, timeouts, and pluggable drivers (PhantomJS, HTTP)|JavaScript| MIT |

## Chromium drivers

*These libraries control Chromium*

Name  | About  | Supported Languages | License
:------------ |:---------------| :----- | :-----------
|[Awesomium](http://www.awesomium.com/) | Chromium-based headless browser engine|C++, .NET| Free/Commercial |
|[Headless Chromium](https://chromium.googlesource.com/chromium/src/+/lkgr/headless/README.md) | Headless Chromium is a library for running Chromium in a headless/server environment.|C++| Not Specified |

## Webkit drivers

*These drivers control an in-process instance of Webkit*

Name  | About  | Supported Languages | License
:------------ |:---------------| :----- | :-----------
|[Browserjet](https://github.com/briankircho/browserjet) | Runs a custom build of webkit, controlled by node.js interface.|JavaScript| Not specified |
|[ghost.py](http://jeanphix.me/Ghost.py/) | ghost.py is a webkit web client written in python.|Python| MIT |
|[headless_browser](https://github.com/alexandernst/headless_browser) | Headless browser based on WebKit written in C++.|C++| Not Specified |
|[Jabba-Webkit](https://github.com/jabbalaci/Jabba-Webkit) | Jabba's headless webkit browser for scraping AJAX-powered webpages.|Python| Not specified |
|[Jasmine-Headless-Webkit](http://johnbintz.github.io/jasmine-headless-webkit/) | jasmine-headless-webkit uses the QtWebKit widget to run your specs without needing to render a pixel.|Python, JavaScript, Ruby| Free |
|[Python-Webkit](http://www.gnu.org/software/pythonwebkit/) | Python-Webkit is a python extension to Webkit to add full, complete access to Webkit's DOM|Python| GNU |
|[Spynner](https://github.com/makinacorpus/spynner) | Programmatic web browsing module with AJAX support for Python|Python| Not specified |
|[Webloop](https://github.com/sourcegraph/webloop) | Scriptable, headless WebKit with a Go API. | Go | BSD-3 Clause |
|[WKZombie](https://github.com/mkoehnke/WKZombie) | Functional headless browser (with JSON support) for iOS using WebKit and hpple/libxml2.|Swift| MIT |

## Other drivers

*These libraries control lesser known browsers or OS-provided web libraries*

Name  | About  | Supported Languages | License
:------------ |:---------------| :----- | :-----------
|[grope](https://github.com/youpy/grope) | A RubyCocoa interface to the macOS WebKit Framework |RubyCocoa| MIT |
|[SlimerJS](http://slimerjs.org/) | SlimerJS is similar to PhantomJs, except that it runs Gecko, the browser engine of Mozilla Firefox, instead of Webkit (And it is not yet truly headless).|JavaScript| Mozilla 2.0 |
|[SpecterJS](https://github.com/andyjansson/specterjs) | A scriptable headless Internet Explorer port of PhantomJS. | JavaScript | MIT |
|[trifleJS](http://triflejs.org/) | A headless Internet Explorer browser using the .NET WebBrowser Class with a Javascript API running on the V8 engine.|JavaScript| MIT |


## Fake Browser Engine

*These libraries are typically naive or HTML-only browsers*

|Name  | About  | Supported Languages | License
|:------------ |:---------------| :----- | :-----------
|[AngleSharp](https://github.com/AngleSharp/AngleSharp) | .Net Http Parsing Library | .NET | MIT |
|[benv](https://github.com/artsy/benv) | Stub a browser environment in node.js and headlessly test your client-side code.|JavaScript| MIT |
|[browser.rb](https://github.com/tmp8/browser-rb) | Headless Ruby browser on top of Nokogiri and TheRubyRacer|Ruby| Not specified |
|[BrowserKit](https://github.com/symfony/browser-kit) | BrowserKit simulates the behavior of a web browser.|PHP| MIT |
|[DamonJS](https://github.com/damonjs/damon) | Bot navigating urls and doing tasks.|JavaScript| Apache |
|[Headless](https://github.com/roryprimrose/Headless) | Headless browser support for fast web acceptance testing in .Net|.NET| MIT |
|[HeadlessBrowser](https://github.com/clubajax/HeadlessBrowser) | A very miniature headless browser, for testing the DOM on Node.js|JavaScript| Not specified |
|[HtmlUnit](http://htmlunit.sourceforge.net/) | HtmlUnit is a "GUI-Less browser for Java programs".|Java| Apache |
|[Jaunt](http://jaunt-api.com/) | Java Web Scraping & Automation API|Java| Not specified |
|[JSDom](https://github.com/tmpvar/jsdom) | A JavaScript implementation of the WHATWG DOM and HTML standards, for use with Node.js. |JavaScript| MIT |
|[MechanicalSoup](https://github.com/hickford/MechanicalSoup) | A Python library for automating interaction with websites.|Python| MIT |
|[mechanize](http://wwwsearch.sourceforge.net/mechanize/) | Stateful programmatic web browsing.|Python| BSD-3 clause, ZPL 2.1 |
|[RoboBrowser](https://github.com/jmcarp/robobrowser) | A simple, Pythonic library for browsing the web without a standalone web browser.|Python| BSD-3 clause |
|[SimpleBrowser](https://github.com/SimpleBrowserDotNet/SimpleBrowser) | A flexible and intuitive web browser engine designed for automation tasks. Built on the .Net 4 framework.|.NET| BSD-3 Clause |
|[stanislaw](https://github.com/teddziuba/stanislaw) | Naive, mechanize-like HTML parser/form driver.|Python| Not specified |
|[twill](http://twill.idyll.org/) | Twill is a simple language that interacts with basic HTML pages (no JavaScript support).|Python| MIT |
|[WWW::Mechanize](https://metacpan.org/search?size=20&q=WWW%3A%3AMechanize&search_type=modules) |  Headless browser for Perl with many plugins and extensions, notably Test::WWW:Mechanize for testing | Perl | Perl 5 |
|[Zombie.js](http://zombie.js.org/) | Zombie.js is a lightweight framework for testing client-side JavaScript code in a simulated environment. No browser required.    | JavaScript   | MIT |

## Runs in a browser

Name  | About  | Supported Languages | License
:------------ |:---------------| :----- | :-----------
|[DalekJS](http://dalekjs.com/) | Automated cross browser testing with JavaScript.|JavaScript| MIT |
|[Sahi](http://sahipro.com/sahi-open-source/) | Sahi is a cross-browser automation/testing tool with the facility to record and playback scripts.|JavaScript, Java, Ruby, PHP| Apache / Commercial |
|[WatiN](http://watin.org/) | Web Application Testing In .Net|.NET| Apache 2.0 |

## Misc tools

Name  | About  | Supported Languages | License
:------------ |:---------------| :----- | :-----------
|[browser-launcher](https://github.com/substack/browser-launcher) | Detect and launch browser versions, headlessly or otherwise|JavaScript| MIT |
