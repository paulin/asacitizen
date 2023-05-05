---
layout: post
title:  "As A Citizen: I want to be identified securely"
categories: US OKRs
date: 2021-05-21
---
#As a Citizen I want to be identified securely


Passport.png
## As a Citizen, Do I Want A National ID?

In the United States we are at a turning point around a national digital identity. We do not have an official National ID but we treat our Social Security Numbers to identify ourselves for taxes and government benefits. This leaves us vulnerable to identity theft and confusing complications because we are not addressing the problems of a National Identity system head on. If a National ID is done badly it can create a worse situation where we lose more liberty than we realize in the promise of convenience.

In this article I want to explore what it would mean to have a national id and why that would be important. I also use techniques borrowed from product development to show how this can be done to make a system that is transparent without being broken.

## What is a National ID?
Simply put, a National ID is a way for a nation to identify its citizens. Technically, the United States doesn’t have one because it must be a mandatory ID with a picture on it. Imagine something that looks like a drivers license, issued by the federal government, that everyone must have with them.

It is a mixed bag of convenience except that by forcing the citizens to all have the ID it makes the citizens the subjects of the national government instead of the government working for the citizens. If you know one thing about the United States it would have to be that liberty and independence is a key part of the identity. Therefore we don’t have a National ID by name.

**However over 100 other countries do!**

*According to a 1996 publication by Privacy International, around 100 countries had enacted laws making identity cards compulsory:* [Source](https://en.wikipedia.org/wiki/List_of_national_identity_card_policies_by_country)

The [American Civil Liberties Union](https://www.aclu.org/), ACLU, sees a lot of problems with having a National ID card which they document in [this article](https://www.aclu.org/other/5-problems-national-id-cards).

1. It will not solve the purpose for why it is built: A national ID card system will not prevent terrorism.
2. It will not be restricted: Once put in place, it is exceedingly unlikely that such a system would be restricted to its original purpose.
3. It will be clunky: A national ID would require a governmental database of every person in the U.S. containing continually updated identifying information.
4. It reduces your liberty: It can be used to monitor a citizens internal movements.
5. It would enable more discrimination and harassement

Creating a database of all of the citizens does seem fraught with abuse. It is very one sided and this sort of information is power. In my opinion, the information owned by our government should be transparent. **We should have more information about our government than our government has about us.** However, that is another topic I hope to cover in a future article.

## Instead we have the Social Security system.
*“The Social Security number (SSN) was created in 1936 for the sole purpose of tracking the earnings histories of U.S. workers, for use in determining Social Security benefit entitlement and computing benefit levels. Since then, use of the SSN has expanded substantially. Today the SSN may be the most commonly used numbering system in the United States.”* [Source SSA.gov](https://www.ssa.gov/policy/docs/ssb/v69n2/v69n2p55.htm)

I’m writing this in 2021, we are talking about 1936 when President Franklin Delano Roosevelt was fighting the great depression. Later the SSN became the National Identifier of people in the United States. Listen to this from [Planet Money](https://www.npr.org/2018/03/22/596180023/how-social-security-numbers-became-a-form-of-national-identification) to learn more. [This is a longer version](https://www.npr.org/transcripts/593603674) which digs into it even more.

The TL;DR is they needed to index the population so they could figure out who needed to pay into the Social Security fund so then they could figure out how to pay it back out later at retirement. Notice that this was far before computers and everything was being done on paper.

Unfortunately this simply put a number to every citizen which then was convenient for other government agencies to use to keep track of how we are paying our taxes, applying for financial assistance and really this 9 digit number is how we have organized our information around a common index.



## Anti User Stories: We have the worst of all worlds
It’s hard to express how badly this turned out so I think I will write out the User Stories we have to show the mess we are in.

1. As a Citizen I want to be tracked by my government in ways I am not aware of
2. As a Citizen I want to memorize a nine digit number and keep it secret so that I can participate in government programs
3. As a Citizen I want the number issued on a paper card that is hard to replace.
4. As a Citizen I want the only security of my identity is my ability to keep my 9 digit number secret
5. As a Citizen I want to have no control over my information so that I can easily end up with mistakes affecting my future.
6. As a Government I want to use a numbering system that a modern computer can cycle through in less than 15 seconds to try every combination.

## User Stories
Now that we have a set of user stories that do not work. How about we look into what we would actually want. NOTE: I realize that some people don’t want to be in a database at all. But they are being unrealistic. Either you accept the power that comes with this modern world or you ignore it and give that power to others.

1. As a Citizen I want to use a digital id to interact with government systems so that I can pay my taxes securely.
2. As a Citizen I want a secure way to sign up for Government programs.
3. As a Citizen I want to control what is tracked about me.
4. As a Citizen I want to opt in to being tracked.
5. As a Citizen I want to know what my Government knows about me so that I can argue if there is false information being used to determining my future
6. As a Citizen I want my government to use an open standard to identify me so that my data is portable beyond my government because I might travel to other countries

## Solutions that already exist
This is not a new idea. There are many groups that are working on building a secure system that puts the control of identity in the hands of the user. Identity has gone through so many evolutions over the last few decades so that users of vast computer systems can have a balance of convenience and security. [This article explains the evolution](https://medium.com/evernym/the-three-models-of-digital-identity-relationships-ca0727cb5186) if you want to dig into this more. The summary is that we want Self Sovereign Identity which is a peer to peer system. It gets rid of the need to have a centralized database that can be controlled and corrupted. Essentially, since no one can be trusted with the power of identity, then we will all share in the responsibility.

Here is a sample of the groups that have evolved to give you the best control over your identity.

**Bloom:** [https://bloom.co/](https://bloom.co/): Bloom is a blockchain solution for secure identity and credit scoring. Bloom gives consumers ownership over their identity and financial data. By decentralizing the way that information is shared between untrusted parties, the system reduces risk of identity theft and minimizes costs associated with customer onboarding, compliance and fraud prevention.

**Civic:** [https://www.civic.com/](https://www.civic.com/) : AI-powered identity verification combined with human review to ensure that your users are real, always.

**Hyperledger Indy:** [https://www.hyperledger.org/](https://www.hyperledger.org/) : Hyperledger Indy provides tools, libraries, and reusable components for providing digital identities rooted on blockchains or other distributed ledgers so that they are interoperable across administrative domains, applications, and any other silo. Indy is interoperable with other blockchains or can be used standalone powering the decentralization of identity.

**Serto:** [https://www.serto.id/](https://www.serto.id/) : *We enable people and enterprises to utilize the newest innovations in decentralized technology to make data more portable, private, and valuable.*

**Sovrin:** [https://sovrin.org/](https://sovrin.org/) : *Personally manage your digital IDs online with the Sovrin Network – an open source project creating a global public utility for self-sovereign identity.*



Of all of these Sovrin stands out to me. The whole purpose is to provide an id that a user can use that is beyond the country they live in. So starting with the user and decentralizing the ID across multiple computers it allows you to have a secure ID that cannot be compromised. This would be the root of your identity and you would control it.


## Legislation
It is so amazing to me that we have such an obvious problem and that someone has already come up with a fantastic solution. All that has to happen is for our government to decide this is a good idea.

In a previous article I posed the question that why wouldn’t every citizen have a login into the federal government? This became a discussion around login and what is possible.

As it turns out there is one already that exists. It was put together by the [https://www.gsa.gov/](https://www.gsa.gov/) and is called [https://login.gov/](https://login.gov/)

*“Login.gov offers the public secure and private online access to participating government programs. With one login.gov account, users can sign in to multiple government agencies. Our goal is to make managing federal benefits, services and applications easier and more secure.”*


*Step 1:* Switch to Sovrin
The GSA would need to work with Sovrin to switch the authentication to the Sovrin credential platform Evernym. After that all groups using Login.gov to access would need to migrate over to the new authentication system.

*Step 2:* The State Department issues an electronic version of the U.S. passport using Sovrin
Currently the Department of Homeland Security has an e-passport which consists of a chip built into the passport. This isn’t the same thing. I think these could work together to provide some authentication. For example, if more biometric data was stored on the physical passport it could be used to verify identity into the Sovrin system.

*Step 3:* The IRS would ask all citizens to create an account on Login.gov instead of using their Social Security number to file their taxes
This untangles the use of Social Security numbers as the common “National ID” we are using currently and provides a reason for every U.S. citizen to have a more secure online identity.

*Step 4:* The U.S. would push the other countries in the United Nations to adopt the same practices.
It’s very important that other countries adopt a similar practice for tracking identity and authentication. If this happened I think it would unlock opportunities for world citizens far beyond what they have to do currently.

## Why Now?
As we are coming out of covid times and in need of an international passport to verify our vaccine standards, Sovrin would be an obvious choice. If we could get something like this inserted into the global identity it would reduce the amount of “hacking” done with a SSN, improve convenience, and reduce the power of national governments over their citizens.



## OKRs for Outcomes over Output
In the world of business OKRs are a fantastic communication tool to provide alignment between different entities by describing what they are trying to achieve. The following would help other entities adjust to the changes.

* __Objective:__ Reduce costs of digital infrastructure
  * __Key Result 1:__ Establish a list of all government entities requiring a login and automate how they are doing it. Track this as a cost.
  * __Key Result 2:__ Track the costs of business that is devoted to chasing down identity theft due to SSN impersonation

* __Objective:__ Reduce identity theft for its citizens
  * __Key Result 1:__ Track the number of identity theft cases that occur
  * __Key Result 2:__ Track the number of incidents per department and what identity solution the department is using.

* __Objective:__ Improve international identity
  * __Key Result 1:__ Track ID forgeries at border crossings. The system described should make it nearly impossible to replicate a passport.

## What happens if we get here?
This is a rather inexpensive change for an inestimable benefit. As a Citizen you will be in control of your own identity. When you log in to do your taxes, they will know it is you, and you can feel some confidence that a hacker did not claim your returns. The reduction in identity theft will save businesses countless amounts. The reduction in wasted federal money spent dealing with security breaches will be vastly reduced.

Most importantly, for the first time you will feel like you control your own identity since it is decentralized and no government will control it. Depending on what our future holds this can make all the difference between an oppressive future or one where we can remake it again, without having to figure out how to index ourselves.
