# Software Disclaimer, Licensing & Entity Attribution Guide

This guide explains how to use the repository’s notices. It is general information, not legal advice, and does not guarantee protection from claims.

## 1. Publisher name and copyright ownership

Use **Bitseeker LLC** as the publisher in current materials if the LLC is the entity distributing the software. A personal name does not need to appear in a README slogan or general disclaimer merely because the person maintains the GitHub account. The `@cjtsh` handle may identify the repository account without naming an individual.

Copyright notices should identify the actual copyright owner. Authorship alone does not automatically transfer a copyright to an LLC. If software was created personally and the LLC is intended to own it, confirm that the rights were assigned in writing before using an LLC-only copyright notice. Keep third-party and contributor rights distinct. A GitHub handle or LLC label does not create anonymity or erase a person’s own legal responsibility.

Florida law generally makes an LLC’s debts the company’s debts and does not impose them on a member solely because they are a member or manager. See [Fla. Stat. § 605.0304](https://www.leg.state.fl.us/statutes/index.cfm?App_mode=Display_Statute&URL=0600-0699%2F0605%2FSections%2F0605.0304.html). That protection is not personal immunity for someone’s own tortious conduct; see, for example, [Costa Investors, LLC v. Liberty Grande LLC](https://law.justia.com/cases/florida/fourth-district-court-of-appeal/2022/21-2676.html). Keep company and personal affairs distinct, sign agreements in the company’s name and capacity, and avoid personal guarantees unless intended.

## 2. What disclaimer language can and cannot do

Clear, prominent language helps communicate that software is provided without warranties and that certain damages are excluded. It cannot guarantee dismissal of a claim, bind someone who never agreed to contractual terms, or waive duties and liabilities that applicable law makes nonwaivable. Florida courts assess whether a release is clear and understandable and whether enforcing it would violate public policy; see [Sanislo v. Give Kids The World, Inc.](https://law.justia.com/cases/florida/supreme-court/2015/sc12-2409.html).

The UCC is not a universal software-disclaimer statute. Article 2 applies to sales of goods; how it applies to a software transaction can depend on the transaction and governing law. Under [Fla. Stat. § 672.316](https://www.leg.state.fl.us/Statutes/index.cfm?App_mode=Display_Statute&URL=0600-0699%2F0672%2F0672.316.html), certain written warranty exclusions must be conspicuous. Uppercase text may help visibility where that rule applies, but typography alone does not establish assent or enforceability.

## 3. Notice and affirmative assent

A public README or disclaimer link is useful notice, but do not assume that visiting GitHub or downloading a repository proves acceptance of every contractual term. Florida decisions distinguish passive browsewrap notice from a clear action that manifests assent; see [Eglin Federal Credit Union v. Baird](https://law.justia.com/cases/florida/first-district-court-of-appeal/2024/1d2023-1866.html).

If a product relies on indemnification or a forum-selection clause as contract terms, present the terms before use, make them easy to review, require an affirmative “I agree” action where appropriate, and retain evidence of the version and acceptance. A first-run text file only accomplishes this if the application actually presents it and conditions use on an affirmative action. For interactive CLI tools, use a clear first-use prompt; for unattended runs, require an explicit acceptance flag and fail closed if it is absent. A printed banner by itself is notice, not necessarily assent. Retain only the acceptance evidence needed for the use case and follow applicable privacy rules. Consider separate counsel review of any click-through agreement, especially before distributing an app or binary.

## 4. License and distribution consistency

The root `LICENSE` grants the rights stated in the MIT License. A separate disclaimer should not silently add restrictions that conflict with that license. Keep all copyright notices accurate, preserve third-party notices, and identify the correct licensor in source files, release packages, and documentation.

For releases, include the license and disclaimer in the package and link them prominently from the project README. A DMG or first-run screen can improve notice, but it is not automatically a binding contract without suitable presentation and assent.
