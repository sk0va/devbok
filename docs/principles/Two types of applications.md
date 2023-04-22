
Every application is maintainable or non-maintainable depending on usage and purpose.

## Maintainable applications

Maintainable applications are expected to be developed with time. It is the most common type of application. Any app in production is maintainable. Any internal tool which you use periodically is also a kind of maintainable application. In general, any application which works constantly or periodically and provides value for its users is maintainable.

The more important application is for its stakeholders, the more its developers should care about the quality of functional and non-functional requirements, the proper development process, architecture, design, implementation, quality assurance, security considerations, etc

In the case of maintainable applications, developers should follow best practices and use common and modern approaches well-known in the industry like Testing Pyramid, DRY, KISS, YAGNI, etc. 


## Non-maintainable applications
What are non-maintainable apps? There are a few types of such applications - proof of concepts and one-time tools.

Proof of concept is usually created just as an experiment and its main purpose - is to prove some hypotheses. Once it happened, PoC is not needed anymore and could be deleted or archived for history. 

A one-time tool is an app created to make some specific job. After that job is done, this tool is no longer needed and also could be deleted or archived for history.

In the case of non-maintainable applications, you don't need to think about unit tests, architecture, SOLID, clean code, DRY, etc. All these best practices will not only be redundant in case of non-maintainable applications but even will be undesirable because will just waste your time without any real benefits. But at least KISS and YAGNI principles still work. You should completely focus on business logic and use the simplest solution possible.
You still need to test your application, but it should be done manually. No automation tests are needed, except in the case, when you implement your PoC as a specific unit test. Also usually you don't need any kind of CI/CD, if a non-maintainable application should be deployed somewhere, i.e. to provide remote access to other stakeholders, much better to do it manually. 

Sometimes stakeholders may ask you to change PoC not even once, but several times. Anyway, it is still a one-time job to prove some theory, prove some statements or find a solution for some problem. So it is still a non-maintainable application.

The most important thing about non-maintainable applications - you should be sure that this application will not be maintained either. As soon as someone decided to make it maintainable - that application must be refactored, to make it maintainable, or a new maintainable application must be created instead.

