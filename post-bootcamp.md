# Post-Bootcamp Learning

## Getting Started

Prerequisites:

 * Comfortable in Java
     - Maven or Gradle
     - Spring Boot
     - JUnit

# Table of Contents

1. [Solid Principles](#solid-principles)
2. [Test-Driven Development](#test-driven-development)
3. [Refactoring](#refactoring)
4. [Code Review](#code-review)
5. [Architectural Styles](#architectural-styles)
6. [Design Patterns](#design-patterns)
7. [Connascence](#connascence)
8. [Domain Models](#domain-models)
9. [Domain Driven Design](#domain-driven-design)
10. [Functional Programming](#functional-programming)
11. [Code Katas](#code-katas)
12. [Diagramming Code](#diagramming-code)
13. [Legacy Code](#legacy-code)
14. [Continuous Integration](#continuous-integration)
15. [Deploying your code](#deploying-your-code)
16. [Continuous Delivery](#continuous-delivery)
17. [Agile Methodologies](#agile-methodologies)
18. [Enterprise Integration](#enterprise-integration)
19. [Patterns of Software Architecture](#patterns-of-software-architecture)
20. [Learning Go](#learning-go)
21. [Smalltalk](#smalltalk)
22. [Essential Reading](#essential-reading)
23. [Other Recommendations](#other-recommendations)

## SOLID Principles

 * [Core Design Principles for Software Developers by Venkat Subramaniam (Video)](https://www.youtube.com/watch?v=llGgO74uXMI)
 * https://itnext.io/solid-principles-explanation-and-examples-715b975dcad4

 * Single-responsibility Principle
     - https://web.archive.org/web/20150202200348/http://www.objectmentor.com/resources/articles/srp.pdf
     - https://dzone.com/articles/single-responsibility-principle-done-right
     - https://deviq.com/single-responsibility-principle
 * Open-closed Principle
     - https://web.archive.org/web/20150905081105/http://www.objectmentor.com/resources/articles/ocp.pdf
     - https://deviq.com/open-closed-principle/
 * Liskov substitution Principle
     - https://web.archive.org/web/20150905081111/http://www.objectmentor.com/resources/articles/lsp.pdf
     - https://deviq.com/liskov-substitution-principle/
 * Interface-seggregation Principle
     - https://web.archive.org/web/20150905081110/http://www.objectmentor.com/resources/articles/isp.pdf
     - https://deviq.com/interface-segregation-principle
 * Dependency inversion Principle
     - https://web.archive.org/web/20150905081103/http://www.objectmentor.com/resources/articles/dip.pdf
     - https://deviq.com/dependency-inversion-principle

 * [SOLID Object-Oriented Design by Sandi Metz (Video)](https://youtu.be/v-2yFMzxqwU)
 * [Building on Solid Foundations - Nat Pryce and Steve Freeman (Video)](https://youtu.be/6Bia81dI-JE)

## Test-Driven Development

 * [Agile Alliance definition](https://www.agilealliance.org/glossary/tdd/)
 * [Test Driven Development: By Example - Kent Beck](https://www.informit.com/store/test-driven-development-by-example-9780321146533)
 * [Kent Beck Screencasts (Video)](https://pragprog.com/screencast/v-kbtdd/test-driven-development)
 * [Growing Object-Oriented Software, Guided by Tests, by Steve Freeman and Nat Pryce](https://www.informit.com/store/growing-object-oriented-software-guided-by-tests-9780321503626)
 * [C2 Wiki](http://wiki.c2.com/?TestDrivenDevelopment)
 * [Refactoring and Design Skills for Test Driven Development by Roy Osherove (Video)](https://youtu.be/9ZSbuwCmwuc)
 * [Guide: Writing Testable Code - Miško Hevery](http://misko.hevery.com/code-reviewers-guide/)
 * [TDD - Jason Gorman](http://codemanship.co.uk/tdd_jasongorman_codemanship.pdf)
 * [TDD and Software Design - JB Rainsberger and Sandro Mancus (Video)](https://youtu.be/ty3p5VDcoOI)
 * [Agile Technical Practices Distilled](https://leanpub.com/agiletechnicalpracticesdistilled)
 * [Mocks Aren't Stubs - Martin Fowler](https://martinfowler.com/articles/mocksArentStubs.html)
 * [Classicist and Mockist schools of TDD](https://github.com/testdouble/contributing-tests/wiki/Test-Driven-Development)
 * [Mockists are dead, Long live classicists - Fabio Pereira](https://www.thoughtworks.com/insights/blog/mockists-are-dead-long-live-classicists)
 * [A Case for Outside-In Design - Sandro Mancuso (Video)](https://youtu.be/rbSDGr-_UwY)
 * [Outside-in-TDD (Part 1) Sandro Mancuso (Video)](https://youtu.be/XHnuMjah6ps)

 * [TDD: The Bad Parts (Video)](https://youtu.be/xPL84vvLwXA)
 * [Is TDD Dead](https://martinfowler.com/articles/is-tdd-dead/)

## Refactoring

 * [Refactoring.com](https://refactoring.com/)
 * [Unit Test Craftsmanship by Gerard Meszaros (Video)](https://youtu.be/qdSns9BOFrM)
 * [Workflows of Refactoring - Martin Fowler (Video)](https://youtu.be/vqEg37e4Mkw)
 * [Refactoring Course](http://www.cs.unc.edu/~stotts/COMP204/refactor/)

## Code Review

 * [Code Review Best Practices - Trisha Gee](https://trishagee.github.io/presentation/code_review_best_practice/)
     - [Code Review Best Practices - Trisha Gee (Video)[https://youtu.be/jXi8h44cbQA]
 * [What to Look for in a Code Review](https://leanpub.com/whattolookforinacodereview)
 * [Google's Code Review Developer Guide](https://google.github.io/eng-practices/review/)
 * [Code Review Guidelines for Humans](https://phauer.com/2018/code-review-guidelines/)
 * [Amazing Code Reviews: Creating a Superhero Collective - Alejandro Lujan (Video)](https://youtu.be/ly86Wq_E18o)

## Architectural Styles

 * [Making Architecture Matter - Martin Fowler (Video)](https://youtu.be/DngAZyWMGR0)
 * [Monolith](http://www.codingthearchitecture.com/2014/11/19/what_is_a_monolith.html)
     - [Modular Monoliths - Simon Brown (Video)](https://youtu.be/5OjqD-ow8GE)
     - [Majestic Modular Monoliths - Axel Fontaine (Video)](https://youtu.be/BOvxJaklcr0)
 * [Service Oriented Architecture](http://www.opengroup.org/soa/source-book/soa/p1.htm#soa_definition)
     - [SOA Patterns - Arnon Rotem-Gal-Oz](https://www.manning.com/books/soa-patterns)
     - [SOA Patterns (drafts) - Arnon Rotem-Gal-Oz](https://arnon.me/soa-patterns/)
 * [Microservices](https://martinfowler.com/articles/microservices.html)
     - [Micro services, Java the Unix Way](https://www.infoq.com/presentations/Micro-Services/)
     - [Micro-Service Architecture, by Fred George (Video)](https://youtu.be/2rKEveL55TY)
     - [Microservices Patterns and Anti-patterns - Stefan Tilkov (Video)](https://youtu.be/VaYmRe104HU)
     - [10 Tips for failing Badly at Microservices (Video)](https://youtu.be/X0tjziAQfNQ)
     - [Design Microservice Architectures the Right Way - Michael Bryzek (Video)](https://youtu.be/j6ow-UemzBc)
     - [Microservices Domain Driven Design, why and how? - Michael Plöd (Video)](https://youtu.be/lUCLFOISuXk)
 * Distributed Monoliths
     - [Distributed Monolith - Alex Topalov (Video)](https://youtu.be/AbZq32XCzU8)
     - [Microservices Ending up as a Distributed Monolith](https://www.infoq.com/news/2016/02/services-distributed-monolith/)
 * [Self-contained Systems](https://scs-architecture.org/)
     - [Nano, Micro, Mini, oh my: Modularization for sustainable systems (Video)](https://youtu.be/HYiLzji7MuY)

## Design Patterns

 * Gang of Four (original Design Patterns Book)
     - [Design Patterns: Elements of Reusable Object-Oriented Software](https://www.informit.com/store/design-patterns-elements-of-reusable-object-oriented-9780201633610)
     - [Design Patterns in Object Oriented Programming](https://www.youtube.com/playlist?list=PLrhzvIcii6GNjpARdnO4ueTUAVR9eMBpc)
     - [The 7 Most Important Software Design Patterns](https://medium.com/educative/the-7-most-important-software-design-patterns-d60e546afb0e)
     - [Head First Design Patterns](http://shop.oreilly.com/product/9780596007126.do)
 * Software Architectural Patterns
     - [Software Architecture Guide](https://martinfowler.com/architecture/)
     - [Software architecture patterns (Video)](https://www.youtube.com/playlist?list=PLnIXQSIsn7B3eqIFpamOvjmRriEQ8wlbw)
     - [10 Common Software Architectural Patterns in a nutshell](https://towardsdatascience.com/10-common-software-architectural-patterns-in-a-nutshell-a0b47a1e9013)
     - [The top 5 software architecture patterns](https://techbeacon.com/app-dev-testing/top-5-software-architecture-patterns-how-make-right-choice)
     - [10 Common Software Architetural Patterns](https://nix-united.com/blog/10-common-software-architectural-patterns-part-1/)
     - [Patterns of Enterprise Application Architecture](https://martinfowler.com/eaaCatalog/)
 * Hexagonal Architecture
     - [Hexagonal Architecture - Animesh gaitonde](https://itnext.io/hexagonal-architecture-principles-practical-example-in-java-364bb2e50075)
     - [Hexagonal Architecture: Three patterns and an implementation example](https://blog.octo.com/en/hexagonal-architecture-three-principles-and-an-implementation-example/)
     - [Ian Cooper on Hexagonal Architectures (Video)](https://youtu.be/FJUevNLEtuU)
     - [Mid-sized building Blocks & Hexagonal Architecture - Jakub Nabrdalik (Video)](https://youtu.be/sND1AR7Q_T0)
     - [Hexagonal at Scale, with DDD and microservices! (Cyrille Martraire) (Video)](https://youtu.be/xZOO_CksS-E)
 * [Design patterns implemented in Java](https://java-design-patterns.com/)
 * Microservice Patterns
     - [Microservice Patterns](https://microservices.io/)
     - [A pattern language for microservices - Chris Richardson (Video)](https://youtu.be/1mcVQhbkA2U)
     - [Implementation Patterns for Microservice Architectures - Woolf and Brown](https://www.hillside.net/plop/2016/papers/proceedings/papers/brown.pdf)

## Connascence

 * [Connascence](https://connascence.io/)
 * [Connascence Examined - Jim Weirich (Video)](https://youtu.be/22vYwcfQnk8)
 * Connascence posts by Kevin Rutherford
     - [Connascence of Value](https://silkandspinach.net/2015/01/22/connascence-of-value/)
     - [Connascence of Meaning](https://silkandspinach.net/2015/01/25/connascence-of-meaning/)
     - [Connascence of Position](https://silkandspinach.net/2015/02/09/connascence-of-position/)
     - [Connascence of Algorithm](https://silkandspinach.net/2015/02/10/connascence-of-algorithm/)
     - [Connascence of Algorithm revisited](https://silkandspinach.net/2015/02/10/connascence-of-algorithm-revisited/)
     - [Connascence Revisited](https://silkandspinach.net/2015/02/10/connascence-a-retrospective/)

## Domain Models

 * [Analysis Patterns](https://martinfowler.com/books/ap.html)
 * [Data Model Patterns - Conventions of Thought - David C Hay](https://www.informit.com/store/data-model-patterns-conventions-of-thought-9780133492125)
     - [Sample](http://ptgmedia.pearsoncmg.com/images/9780133492125/samplepages/0133492125.pdf)
 * [Data modeling - an introduction (Video)](https://youtu.be/tR_rOJPiEXc)
 * [Data Modeling 101](http://www.agiledata.org/essays/dataModeling101.html)

## Domain Driven Design

 * [Domain-Driven Design: Tackling Complexity in the Heart of Software - Eric Evans](https://www.informit.com/store/domain-driven-design-tackling-complexity-in-the-heart-9780321125217)
     - [Tackling Complexity in the Heart of Software - Eric Evans (Video)](https://youtu.be/dnUFEg68ESM)
 * [Implementing Domain-Driven Design](https://www.informit.com/store/implementing-domain-driven-design-9780321834577)
 * [Microservices and Domain Driven Design - Vaughn Vernon (Video)](https://youtu.be/3o4_FWk6JOQ)
 * [Domain Driven Design: The Good Parts - Jimmy Bogard (Video)](https://youtu.be/U6CeaA-Phqo)
 * [The Anatomy Of Domain-Driven Design - Booklet](https://leanpub.com/theanatomyofdomain-drivendesign)
 * [Hands-on Domain-driven Design - by example - Michael Plöd](https://leanpub.com/ddd-by-example)
 * [Implementing DDD with the Spring Ecosystem by Michael Plöd (Video)](https://youtu.be/a9dF7fnArq0)
 * [Practical DDD: Bounded Contexts + Events = Microservices by Indu Alagarsamy (Video)](https://youtu.be/Ab5-ebHja3o)
 * [Microservices love Domain-Driven Design, why and how? Michael Plöd (Video)](https://youtu.be/ZJiFlgimHss)
 * [The Language of Actors: Vaughn Vernon (Video)](https://youtu.be/KtRLIzG5c54)
 * [Reactive DDD: Modeling Uncertainty - Vaughn Vernon (Video)](https://youtu.be/MKLRXCiU5IE)
 * [A Decade of DDD, CQRS, Event Sourcing - Greg Young (Video)](https://youtu.be/LDW0QWie21s)

## Functional Programming

  * [Functional Programming in Java - Venka Subramaniam](https://pragprog.com/book/vsjava8/functional-programming-in-java)
      - [Functional Programming with Java 8 by Venkat Subramaniam (Video)](https://youtu.be/15X0qFtBqiQ)
  * [Functional Programming for the Object-Oriented Programmer](https://leanpub.com/fp-oo)
  * [Functional Programming in 40 Minutes - Russ Olsen (Video)](https://youtu.be/0if71HOyVjY)
  * [Domain Modeling Made Functional (Video)](https://youtu.be/1pSH8kElmM4)
  *  [Domain Modeling Made Functional - Scott Wlaschin](https://pragprog.com/book/swdddf/domain-modeling-made-functional)
      - [Functional programming design patterns - Scott Wlaschin (Video)](https://youtu.be/E8I19uA-wGY)
  * [Functional Programming in Kotlin](https://kotlinlang.org/docs/tutorials/kotlin-for-py/functional-programming.html)
  * [7 Languages in 7 Weeks](https://pragprog.com/book/btlang/seven-languages-in-seven-weeks)
  * [http4k - Kotlin functional Web](https://github.com/http4k/http4k)
      - [Server as a Function in Kotlin - Ivan Sanchez & David Denton (Video)](https://youtu.be/vdxBNh1qx1Q)
  * [ring - Clojure functional Web](https://github.com/ring-clojure/ring)

## Code Katas

 * [Tennis Kata](https://github.com/emilybache/Tennis-Refactoring-Kata)
 * [Birthday Greetings Kata](http://matteo.vaccari.name/blog/archives/154)
 * [Racing Car Katas](https://github.com/emilybache/Racing-Car-Katas)
 * [Kata01: Supermarket Pricing](http://codekata.com/kata/kata01-supermarket-pricing/)
 * [Kata09: Back to the Checkout](http://codekata.com/kata/kata09-back-to-the-checkout/)
 * [Webhook Refactoring Kata](https://github.com/bigkevmcd/webhook-kata)
 * [Gilded Rose Refactoring Kata](https://github.com/emilybache/GildedRose-Refactoring-Kata)
     - [Writing Good Tests for the Gilded Rose Kata - Emily Bache](http://coding-is-like-cooking.info/2013/03/writing-good-tests-for-the-gilded-rose-kata/)
     - [All the Little Things by Sandi Metz (Video)](https://youtu.be/8bZh5LMaSmE)
     - [The Gilded Rose Refactoring Kata](https://medium.com/@gabriellamedas/the-gilded-rose-refactoring-kata-2dd2d6f52601)
     - [What I've learned by doing the Gilded Rose Kata](https://blog.lunarlogic.io/2015/what-ive-learned-by-doing-the-gilded-rose-kata-4-refactoring-tips/)
 * [Object Calisthenics](https://williamdurand.fr/2013/06/03/object-calisthenics/)
 * [Code Katas](http://codekata.com/)
 * [Emily Bache's Kata Collection](https://github.com/emilybache/)

## Diagramming Code

 * [C4 Model by Simon Brown](https://c4model.com/)
 * [Visualise, document and explore your software architecture - Simon Brown (Video)](https://youtu.be/Ym9nhVZs89o)
 * [Introduction to the Diagrams of UML 2.X](http://agilemodeling.com/essays/umlDiagrams.htm)
 * [Allen Holub's UML Quick Reference](https://holub.com/uml/)
 * [Picturing Architecture: UML (The Good Bits) and More by Allen Holub](https://www.pluralsight.com/courses/picturing-architecture-uml)
 * [Modeling Style Guidelines - Scott Ambler](http://agilemodeling.com/style/)
 * [Fc4 framework](https://github.com/FundingCircle/fc4-framework)

## Legacy Code
 * [Working Effectively with Legacy Code - Michael Feathers](https://www.informit.com/store/working-effectively-with-legacy-code-9780131177055)
 * [Testing and Refactoring Legacy Code - Sandro Mancuso (Video)](https://youtu.be/_NnElPO5BU0)

## Continuous Integration

 * [Continuous Integration: Improving Software Quality and Reducing Risk - Paul M.  Duvall](https://www.informit.com/store/continuous-integration-improving-software-quality-and-9780321336385)
 * [Continuous Integration](https://martinfowler.com/articles/continuousIntegration.html)

## Deploying your Code

 * [The Twelve-factor App](https://12factor.net/)
 * [Getting Started on Heroku with Java](https://devcenter.heroku.com/articles/getting-started-with-java)
 * [Spring Boot with Docker](https://spring.io/guides/gs/spring-boot-docker/)

## Continuous Delivery

 * [Continuous Delivery: The Dirty Details (Video)](https://youtu.be/JR-ccCTmMKY)
 * [Patterns for Continuous Integration with Docker on Travis CI](https://medium.com/mobileforgood/patterns-for-continuous-integration-with-docker-on-travis-ci-71857fff14c5)

## Agile Methodologies

 * [Learning Agile - Andrew Stellman & Jennifer Greene](http://shop.oreilly.com/product/0636920025849.do)
 * Extreme Programming
 * Scrum
 * Kanban

 * [To Pair or Not To Pair (Video)](https://youtu.be/u_eZ-ae2FY8)

## Enterprise Integration

 * [Enterprise Integration Patterns](https://www.enterpriseintegrationpatterns.com/)
 * [Apache Camel](https://camel.apache.org/docs/)
     - [Getting Started with Apache Camel - Claus Ibsen (Video)](https://youtu.be/_xJipu2E0Pc)
 * [Spring Integration](https://spring.io/projects/spring-integration)
     - [Spring Tips: A Gentle Introduction to Spring Integration (Video)](https://youtu.be/MTKlk8_9aAw)

## Patterns of Software Architecture

 * [Pattern-Oriented Software Architecture: Patterns for Concurrent and Networked Objects "POSA 2"](http://www.dre.vanderbilt.edu/~schmidt/POSA/POSA2/)
 * [Pattern-Oriented Software Architecture: A Pattern Language for Distributed Computing "POSA 4"](http://www.dre.vanderbilt.edu/~schmidt/POSA/POSA4/)

## Learning Go

 * [A Tour of Go](https://tour.golang.org/welcome/1)
 * [Go by Example](https://gobyexample.com/)
 * [Get Programming With Go](https://www.manning.com/books/get-programming-with-go)
 * [Effective Go](https://golang.org/doc/effective_go.html)
 * [Effective Go Supplement](https://github.com/golovers/effective-go)
 * [The Go Programming Language](https://www.informit.com/store/go-programming-language-9780134190440)

## Smalltalk

 * [Stef's Free Online Smalltalk Books](http://stephane.ducasse.free.fr/FreeBooks.html)
 * [How learning Smalltalk can make you a better developer](https://techbeacon.com/app-dev-testing/how-learning-smalltalk-can-make-you-better-developer)

## Essential Reading

 * [97 Things Every Programer Should Know](https://www.oreilly.com/library/view/97-things-every/9780596809515/)
 * [Agile Technical Practices Distilled](https://leanpub.com/agiletechnicalpracticesdistilled)

## Other Recommendations

 * [Reactive Messaging Patterns with the Actor Model: Applications and Integration in Scala and Akka](https://www.informit.com/store/reactive-messaging-patterns-with-the-actor-model-applications-9780133846836)
 * [The Object Primer: Third Edition - Scott Ambler](https://www.cambridge.org/core/books/object-primer/BD0D59A20FFCF1DB1FD2F0E813DC5533)
 * [Your Code as a Crime Scene - Adam Thornhill](https://pragprog.com/book/atcrime/code-as-a-crime-scene)
