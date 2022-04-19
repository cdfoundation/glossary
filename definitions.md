# Continuous Delivery Definitions

The purpose of this doc is to record definitions of important terminology in the Continuous
Delivery space, based on [the canonical definitions of these terms](timeline.md).

This is meant to be a living document: if you would like to propose updates to these definitions,
[please open a PR](CONTRIBUTING.md).

* [Continuous Delivery](#continuous-delivery)
* [Continuous Deployoment](#continuous-deployment)
* [Continuous Integration](#continuous-integration)
* [CI/CD](#cicd)

## Continuous Delivery

**Continuous Delivery (CD)**: A software development practice in which teams release software changes to users safely,
quickly and sustainably by:

 1. Proving that changes can be released at any time
 2. Automating release processes

Sources: [Continuous Delivery (2010)](https://www.oreilly.com/library/view/continuous-delivery-reliable/9780321670250/),
[Martin Fowler](https://www.martinfowler.com/bliki/ContinuousDelivery.html),
[Jez Humble](https://www.informit.com/articles/article.aspx?p=1833567&seqNum=2)

How does Continuous Delivery relate to:
* [Continuous Integration](#continuous-integration): Continuous Integration is a practice that makes Continuous Delivery
  Possible - [Continuous Delivery (2010)](https://www.oreilly.com/library/view/continuous-delivery-reliable/9780321670250/)
* [Continuous Deployment](#continuous-deployment): Continuous Deployment is made possible by Continuous Delivery -
  [Jez Humble](https://continuousdelivery.com/2010/08/continuous-delivery-vs-continuous-deployment/),
  [Timothy Fitz](https://www.blazemeter.com/blog/five-things-you-should-know-about-continuous-deploymentby-man-who-coined-term),
  [Martin Fowler](https://martinfowler.com/bliki/ContinuousDelivery.html)

## Continuous Deployment

**Continuous Deployment**: Working software is released to users automatically on every commit.

Sources: [Timothy Fitz](http://timothyfitz.com/2009/02/08/continuous-deployment/),
[Continuous Integration (2007)](https://martinfowler.com/books/duvall.html)

How does Continuous Deployment relate to:
* [Continuous Delivery](#continuous-delivery): Continuous Deployment is made possible by Continuous Delivery -
  [Jez Humble](https://continuousdelivery.com/2010/08/continuous-delivery-vs-continuous-deployment/),
  [Timothy Fitz](https://www.blazemeter.com/blog/five-things-you-should-know-about-continuous-deploymentby-man-who-coined-term),
  [Martin Fowler](https://martinfowler.com/bliki/ContinuousDelivery.html)
* [Continuous Integration](#continuous-integration): Continuous Integration is a requirement for Continuous Deployment -
  [Timothy Fitz](http://timothyfitz.com/2012/11/25/paths-to-continuous-deployment/)

## Continuous Integration

**Continuous Integration (CI)**: The process of combining code changes frequently, where each change
  is verified on check in.

Sources: [Continuous Delivery (2010)](https://www.oreilly.com/library/view/continuous-delivery-reliable/9780321670250/),
[Continuous Integration (2007)](https://martinfowler.com/books/duvall.html)

## CI/CD

**CI/CD**: A phrase with no clear origin which popped into existence around 2014, which combines
[Continuous Integration (CI)](#continuous-integration) with either [Continuous Delivery (CD)](#continuous-delivery) or
[Continuous Deployment](#continuous-deployment). The phrase is used to refer to tools and practices which encompass one
or more of: Continuous Integration, Continuous Delivery and Continuous Deployment.

Sources: [Google trends](https://trends.google.com/trends/explore?date=all&q=ci%2Fcd),
[First Wikipedia entry (Dec 2016)](https://en.wikipedia.org/w/index.php?title=CI/CD&oldid=756752283),
[2014 article](https://blogs.oracle.com/ravello/continuous-integration-deployment-test-automation)

