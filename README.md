# e-portfolio-4-Censorship-and-Government
A collection of artefacts that demonstrate what I have learnt about Censorship and Government this week

---

## Artefact 1: Government Report – Age Assurance Technology Trial (2025)

**Link:** https://www.infrastructure.gov.au/department/media/publications/age-assurance-technology-trial-final-report

### Summary of the artefact
This is the final report from the Government's Age Assurance Technology Trial, released in September 2025, just before the under-16 ban kicked in. It tested more than 60 age-check tools from 48 vendors and found that age checks can work, but facial age estimation has a "grey zone" of about 2–3 years either side of the limit. Some providers also kept more personal data than they needed to (Age Check Certification Scheme 2025).

### Justification on why I chose the artefact
I'm doing a Bachelor of IT majoring in software development, and laws like the under-16 ban are enforced through software. Developers are the ones who build the age checks, content filters and geo-blocks. This report backs up two problems I could face in my career. The first is accuracy: facial age estimation is weakest right at the ages that matter, like 15 versus 16, so real users get wrongly blocked. The second is privacy: everyone, adults included, might have to hand over a face scan or ID, and developers have to store and protect that data (Age Check Certification Scheme 2025). Honestly, it makes me a bit less supportive of the ban, because a 2–3 year grey zone right around 16 means a lot of people will be judged wrong.

---

## Artefact 2: Scholarly Article – O'Donnell (2025), *Alternative Law Journal*

**Link:** https://doi.org/10.1177/1037969X251394092

### Summary of the artefact
O'Donnell explains how the *Online Safety Amendment (Social Media Minimum Age) Act 2024* works. Platforms have to take "reasonable steps" to stop under-16s having accounts, with fines of up to $49.5 million per breach, but "there is no penalty imposed on young people who manage to circumvent age assurance processes" (O'Donnell 2025, pp. 305–306). Platforms also have to offer an option other than government ID and destroy the data after use.

### Justification on why I chose the artefact
I picked this article because it shows how the law actually works in practice. The obligation is on the platforms, not the users, which is a lot like Section 313, where carriers have to help authorities enforce the law (CQUniversity 2026). It also shows why oversight matters. In my view, Parliament should make the rules, courts should review them, and regulators need to be transparent, rather than leaving it to one agency or one company. Mill's harm principle says protection is only justified to prevent harm to others (Quinn 2020), so safeguards like destroying ID data are really important. I don't think "reasonable steps" is clear enough for a developer to build to, because it doesn't say which checks to use or how many mistakes are acceptable, so every platform is basically guessing.

---

## Artefact 3: News Article – ABC News (10 December 2025)

**Link:** https://www.abc.net.au/news/2025-12-10/social-media-ban-day-one-teen-access/106126706

### Summary of the artefact
This ABC article from the first day of the ban showed how easily the age checks were fooled. A 14-year-old passed as 23 on Snapchat, a 13-year-old passed Instagram's photo check as 16, and other teens got around it with VPNs, older siblings doing the face scan, or even makeup. The Communications Minister said teens who dodged the ban on day one wouldn't necessarily avoid it "in weeks or months" (Dervisevic 2025).

### Justification on why I chose the artefact
The topic I'm most interested in is getting around blocks with VPNs and Tor, and whether bans like this can really be enforced. This article showed the age checks were already failing on day one. In our class discussion, some people said VPNs and Tor make censorship pointless, while others argued that most people never bother to bypass blocks, so blocking still reduces harm. It also links back to the workshop slides on the limits of DNS and IP blocking (CQUniversity 2026). After reading it, I lean more towards the second group: some teens will always find a way around, but most won't bother, so the ban still does something, just not as much as the government claims.

---

## Artefact 4: Workshop Personal Reflection

**Workshop:** Week 9, [Day], [Date], [Tutor], [Campus]

![Selfie in the Week 9 Censorship and Government workshop](images/week9-selfie.jpg)

*My selfie from the Week 9 workshop with [the lecture slides / my tutor] in the background.*

### Summary of the artefact: My Personal Reflection
The case study that really got me thinking was ASIC blocking an IP address instead of the actual domain names, which ended up taking down about 250,000 legitimate websites, including Melbourne Free University (House of Representatives Standing Committee on Infrastructure and Communications 2015). What bothered me most was the lack of transparency. There was no court involved, and it wasn't until June that the media revealed ASIC was behind it. Cloudflare dropping the Daily Stormer also stood out to me. I think it was the right call, but the CEO admitted it would make it harder to say no to government takedown requests later on (Prince 2017).

### Justification on why I chose the artefact
In the discussion, I argued that agencies do need blocking powers, but with oversight, like the court orders needed for copyright blocking. For me, protection turns into restriction when it's used to silence criticism. Nepal's ban on 26 platforms crossed that line and sparked the Gen Z protests (CQUniversity 2026). The eSafety v X case showed that one country shouldn't get to control content for the whole world (Evans & Butler 2024). As a future developer, I realised that if my code wrongly blocks someone, or gets used to silence people, part of that responsibility is mine (Australian Computer Society 2023).

---

## Use of AI
I used Claude (Anthropic) to help plan this e-portfolio. It helped me find sources from 2025 onwards, pull out key facts and page numbers, set up the Markdown structure and reference list, and draft the wording of the summaries and justifications from my own workshop notes and opinions. I checked each source myself and edited the wording so it reflects what I actually think.

---

## References in CQU Harvard Style

Age Check Certification Scheme 2025, *Age Assurance Technology Trial: final report*, Department of Infrastructure, Transport, Regional Development, Communications, Sport and the Arts, Canberra, viewed 24 September 2026, https://www.infrastructure.gov.au/department/media/publications/age-assurance-technology-trial-final-report

Australian Computer Society 2023, *ACS Code of Professional Ethics*, Australian Computer Society, Sydney, viewed 24 September 2026, https://www.acs.org.au/content/dam/acs/rules-and-regulations/CodeOfProfessionalEthics_Mar_2023.pdf

CQUniversity 2026, 'Week 9: Censorship and Government', *COIT11223 ICT Ethics and Governance in Society*, workshop slides, CQUniversity, Rockhampton.

Dervisevic, H 2025, 'Age verification errors see some under-16s retain access to banned social media platforms', *ABC News*, 10 December, viewed 24 September 2026, https://www.abc.net.au/news/2025-12-10/social-media-ban-day-one-teen-access/106126706

Evans, J & Butler, J 2024, 'eSafety drops case against Elon Musk's X over church stabbing videos', *ABC News*, 5 June, viewed 24 September 2026, https://www.abc.net.au/news/2024-06-05/esafety-elon-musk-x-church-stabbing-videos-court-case/103937152

House of Representatives Standing Committee on Infrastructure and Communications 2015, *Balancing freedom and protection: inquiry into the use of subsection 313(3) of the Telecommunications Act 1997 by government agencies to disrupt the operation of illegal online services*, Parliament of the Commonwealth of Australia, Canberra, viewed 24 September 2026, https://www.aph.gov.au/parliamentary_business/committees/house/infrastructure_and_communications/inquiry_into_the_use_of_section_313_of_the_telecommunications_act_to_disrupt_the_operation_of_illegal_online_services/report

O'Donnell, L 2025, 'Australia's social media minimum age laws', *Alternative Law Journal*, vol. 50, no. 4, https://doi.org/10.1177/1037969X251394092

Prince, M 2017, 'Why we terminated Daily Stormer', *The Cloudflare Blog*, 16 August, viewed 24 September 2026, https://blog.cloudflare.com/why-we-terminated-daily-stormer/

Quinn, MJ 2020, *Ethics for the information age*, 8th edn, Pearson, United States.
