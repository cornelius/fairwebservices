---
title: Fair Web Services
layout: main
---
# Fair Web Services

## What makes a web service free as in freedom?

Free Software puts users in charge of their computing. They have control. The Free Software Definition defines the freedoms which guarantee that. When using web services, that is software run by others, the Free Software Definition is not enough. Fair Web Services is an attempt to define criteria for web services which guarantee that users stay in control of their computing and retain the freedoms they have gained with Free Software.

This site is the collection point for defining criteria for Fair Web Services. It's the beginning of a journey and it is in flux. Take it as the base for a discussion and contribute your thoughts. Our goal is to refine that in a solid set of criteria which can be applied by providers and users of web services who care about freedom.

*If you would like to follow this project's progress, feel free to subscribe to our [weekly newsletter](https://tinyletter.com/fairwebservices).*


## Problems

There are a number of problems with the freedom of web services, which can't be addressed through Free Software.

### Lock-in

Some services make it intentionally hard for users to leave or move to another service. They try to lock in users so that they have not much other choice then continuing to use the service.

### Sustainability

If a service provider goes out of business or a service is stopped for any other reason, it can be hard or impossible for users to retrieve their data and replace the service by something else.

### Privacy

Users should be in control of their private data. They should be able to decide who is seeing their data. It takes a serious effort by a service provider to maintain user's privacy. Some service's business models might go against privacy by selling data or tracking. Surveillance can also affect user's privacy.

### Terms of Services

Terms of services govern the relation of the user and the service provider. They are usually hard to read and understand and might take away lots of control and freedom from the user. They can turn a service running on free software in a very non-free service.

### Meta Data

There is not only the actual data users upload to services, but also meta data such as logs, the information who is looking at which data, what users did when, etc. Who owns this data? Who has access to it? How do users control what is happening with their meta data?

### Triple Payment

There are services which let users pay three times, although they are gratis to use in the first place. First, users pay with their data, which they upload and providers can use for their business. Second, users pay with their meta data, which some providers use and sell. Third, some services let users pay for getting access to their data or meta data. Users are not in control when they have to pay for accessing their own data.

### Security

When running Free Software yourself, you can inspect the code, you can prove which code you are running, and you can even fix security problems yourself. When using a web service you have to trust the provider to do this for you.

### Hackability

Hackability (in the good sense) is a fundamental trait of Free Software. You can modify the software to your own needs, can fix bugs, can add features. How can you do this with a web service? How can you help improving it?


## Solutions

There are a number of attempts to solve the problems of freedom of web services. This is a list of relevant links to similar or related projects for inspiration and reference.

* [GNU Affero Public License](https://www.gnu.org/licenses/agpl-3.0.en.html)
* [Franklin Street Statement on Freedom and Network Services](http://wiki.p2pfoundation.net/Franklin_Street_Statement_on_Freedom_and_Network_Services)
* [GNU Ethical Repository Criteria](https://www.gnu.org/software/repo-criteria.en.html)
* [ToS;DR](https://tosdr.org)
* [User Data Manifesto](https://userdatamanifesto.org)
* [Freedom Services](https://exote.ch/blogs/aseigo/2009/10/14/freedom_services)
* [Trusted Internet Services](https://openbit.eu/projekte/trusted-internet-services/)
* [EFF's Best Practices for Online Service Providers](https://www.eff.org/wp/osp)
* [Laws](https://en.wikipedia.org/wiki/Bundesdatenschutzgesetz)
* [5Rights](http://5rightsframework.com/)
* [5 star data](http://data.southampton.ac.uk/5star.html)


## The Fair Web Services certification

None of the solutions is complete yet or has enough traction to serve as a widely accepted solution. The Fair Web Services Definition is the attempt to combine existing approaches and refine them to something which can be used by providers and users of web servcies to make sure that users of web services retain their freedom.

The idea is to create criteria for a certification of services. The certification would allow providers to show that they respect the freedom of users and give users a guideline about what services to use.

We have a [draft of the certification](certification) now.

### Criteria

#### Substitutability

The key criterion is that users are able to substitute a service by another services if they wish. This gives users control as they can take their data and move to a service which better serves them or even run the service themselves.

Substitutability requires well-defined APIs to access the data and functionality, so you can build import tools for other services, support of open protocols, so interoperability of different services becomes possible, that users own their data, a provision for succession in case the service stops operating, and that there are alternative implementations available or possible.

#### Transparency

Transparency is important, so that users can judge what the service does and how that affects their computing. Transparency of terms of use is especially important. But also transparency about what is done with the data, where it's stored and processed.

#### Privacy

Services need to respect the privacy of users and give them ultimate control about what happens with their data. Personal data should only stored when necessary, and it has to be documented what is happening with it. Users need to be able to leave a service and have all their data removed.

#### Security

When running Free Software yourself, you have control about the security of the software, you can inspect the code, analyze it, and fix issues, when necessary. For services this is not possible. They need to establish trust that they are operating in a secure way and are protecting the data of their users. They should use encryption where possible. They need to document procedures how to identify and fix security issues. They need to communicate security issues clearly to their users.

#### Fair model of operation

Paying for a service is ok. Running web services can be costly, and users paying for their share of the costs is a fair model. Creating artificial restrictions as pay barriers, especially to the users own data, is not fair. A user should never be forced to pay for getting access to their own data. A fair web service should also not use third party advertisements, because that introduces tracking of users by third parties, and the users loses control about this data. Users also lose control about what is shown along their own data.


## Examples

We'll collect a list of examples of web services and check how the criteria match. As a first step this is a benchmark for the criteria as well as an initial analysis of how free and fair services are.


## Presentations

The idea of Fair Web Services was presented at a couple of conferences. Recordings from [GUADEC](https://media.ccc.de/v/6-what_makes_a_web_service_free_as_in_freedom), [Akademy](https://www.youtube.com/watch?v=lelaQnW-u0w&index=9&list=PLsHpGlwPdtMogitRYzwPz4dWTVsZRGwts), the [ownCloud conference](https://youtu.be/adz3p5o61wc?list=PLtZe22ggl2YBVYQQ5rMzMi7uFnXHUA0Qg), and the [NextCloud conference](https://www.youtube.com/watch?v=Y2Q1BuBMD7A) are available.


## Road map

The journey started in summer 2016. Here are the next steps. There is no specific time line. It will be done when it is done.

### 1. Starting the discussion

The presentations, workshops and discussions around that in summer 2016 are the starting point to sketch the idea of a fair web services certification. Discussions will go on.

### 2. Launching the web site

On 10 Sep 2016 the [web site](http://fairwebservices.org) was launched. This is the central point where we collect results and discussions.

### 3. Version 1.0 of the Fair Web Services criteria

The goal for the next step is to create a first usable version of the criteria for Fair Web Services. This version 1.0 will be the base for the first certifications. It is expected to evolve over time, while we are learning how it works.

### 4. Self-certification

The first step of certification will be a self-certification, where service providers can declare that they are adhering to the criteria. No formal checks will be involved to make it easy to get started. This will be an intermediate step to a more formal certification.

### 5. Certification by an organization

Finally the certification should be done formally by an organization which is watching over the criteria and that certified services adhere to it. This might involve audits and other formal procedures. This is a last step, which requires an organization to take care of the certification and a business model to cover the costs.


## Contributing to the discussion

You are welcome to contribute to the discussion about how to keep our freedom when using web services. If you want to discuss a topic, open or contribute to an issue in the [issue tracker](https://github.com/cornelius/fairwebservices/issues). If you want to propose a change of the text on the web site, [create a pull request](https://github.com/cornelius/fairwebservices).


## Author

The initial author of this web site is Cornelius Schumacher. Please don't hesitate to [get in touch](mailto:schumacher@kde.org) if you have any questions or comments.


## License

<div class="license-logo"><a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a></div>
This web site and its sources are licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
