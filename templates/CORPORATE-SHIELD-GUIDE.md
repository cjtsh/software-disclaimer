# Software Disclaimer, Licensing & Entity Attribution Guide

This guide explains how to use the repository’s notices. It is general information, not legal advice, and does not guarantee protection from claims.

## 1. Publisher name and copyright ownership

Use **Bitseeker LLC** as the publisher in current materials if the LLC is the entity distributing the software. A personal name does not need to appear in a README slogan or general disclaimer merely because the person maintains the GitHub account. The `@cjtsh` handle may identify the repository account without naming an individual.

Copyright notices should identify the actual copyright owner. Authorship alone does not automatically transfer a copyright to an LLC. If software was created personally and the LLC is intended to own it, confirm that the rights were assigned in writing before using an LLC-only copyright notice. Keep third-party and contributor rights distinct. A GitHub handle or LLC label does not create anonymity or erase a person’s own legal responsibility.

Wyoming law provides that an LLC’s debts, obligations, and liabilities are solely those of the company and do not become a member’s or manager’s solely because of that status. See [Wyo. Stat. § 17-29-304](https://wyoleg.gov/statutes/compress/title17.pdf). The statute does not erase liability for a person’s own conduct; see also [Wyo. Stat. § 17-29-301(b)](https://wyoleg.gov/statutes/compress/title17.pdf). Keep company and personal affairs distinct, sign agreements in the company’s name and capacity, and avoid personal guarantees unless intended. The Wyoming Limited Liability Company Act is codified at Wyo. Stat. § 17-29-101 et seq.

## 2. What disclaimer language can and cannot do

Clear, prominent language helps communicate that software is provided without warranties and that certain damages are excluded. It cannot guarantee dismissal of a claim, bind someone who never agreed to contractual terms, or waive duties and liabilities that applicable law makes nonwaivable. Enforceability depends on the facts, applicable law, and public policy.

The UCC is not a universal software-disclaimer statute. Article 2 applies to sales of goods; how it applies to a software transaction can depend on the transaction and governing law. Under [Wyo. Stat. § 34.1-2-316](https://www.wyoleg.gov/statutes/compress/title34.1.pdf), certain written warranty exclusions must be conspicuous. Uppercase text may help visibility where that rule applies, but typography alone does not establish assent or enforceability.

## 3. Notice and affirmative assent

A public README or disclaimer link is useful notice, but do not assume that visiting GitHub or downloading a repository proves acceptance of every contractual term. Whether a user manifested assent depends on the presentation, the user’s actions, and applicable law.

If a product relies on indemnification or a forum-selection clause as contract terms, present the terms before use, make them easy to review, require an affirmative “I agree” action where appropriate, and retain evidence of the version and acceptance. A first-run text file only accomplishes this if the application actually presents it and conditions use on an affirmative action. For interactive CLI tools, use a clear first-use prompt; for unattended runs, require an explicit acceptance flag and fail closed if it is absent. A printed banner by itself is notice, not necessarily assent. Retain only the acceptance evidence needed for the use case and follow applicable privacy rules. Consider separate counsel review of any click-through agreement, especially before distributing an app or binary.

## 4. License and distribution consistency

The root `LICENSE` grants the rights stated in the MIT License. A separate disclaimer should not silently add restrictions that conflict with that license. Keep all copyright notices accurate, preserve third-party notices, and identify the correct licensor in source files, release packages, and documentation.

For releases, include the license and disclaimer in the package and link them prominently from the project README. A DMG or first-run screen can improve notice, but it is not automatically a binding contract without suitable presentation and assent.
