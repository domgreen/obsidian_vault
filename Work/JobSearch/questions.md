---
id: questions
aliases: []
tags: []
---


# Introduce Yourself

So I’m Dom (pronouns he/him) and currently the CTO at NetspeakGames, a small games studio aiming to make a cozy social online world and leading the technology side of the business, ranging from enabling others to keep a high velocity to building out our backend microservices and looking at what future tech we can leverage.
Global cross platform services that enable players connect and play together
Built out to eventually be used as a SaaS based platform for other games
Training out the team about best practice and the SDLC

Before this I worked at Improbalbe helping to build out their version of the metaverse. Also have customer facing experience both at i8e and as a consultant at Microsoft where I helped customers solve complex problems with Azure.

# Why do you want to leave your current Job?

- So were scaling down #netspeak as we need to get more investment and so I’m currently at risk of redundancy but its been a great team to be part of 
- As part of this journey it has made me consider more about what I want as an engineer and my career and want learn and grow more
- Experience the scale problems that are unique to companies like meta
- Learn new technologies such as AI and how this can not only help our customers but the workforce as well

###  What was the team working on?

- QA
  - Process Improvements around hte testing and releasing of the game
  - Left shift of testing to earlier in the processes
  - Better visibility of test and confidence
- GameTeam
  - Monetisation
  - Better integration of deep linking
- Platform
  - Retention Emails
  - Global friendship / groups
  - Upgrade of UE4 engine build pipeline

# Tell me where you failed

Okay so when I was working at #improbable as a Platform Engineer I was tasked with cleaning up some of our DNS entries that were stale from old projects so no longer needed.
Not all of this has been moved ot an infrastructure as code approach so needed to do some manual operations within the UI to remove them. When clicking in the UI I had accidently selected the root DNS record rather than that of the individual records. This resulted in huge impact to the running services at Improbable.

First thing I did was escalate to a more senior engineer and then look for the last backup of the DNS entries that we had taken. I quickly managed to get the core DNS entries back and then slowly brought back the rest of the system to full health.

My learnings from this was to try to make things as simple as possible to do the right thing wether this be IoC or just making sure that it is really clear what will happen and if this is intended.
“Move fast … on stable infrastructure”

# Collaboration Experience

- Cross Team SDLC diversity in different areas adding velocity


Working as the CTO of #netspeak it has given me the opportunity to work across a wide range of diverse and talented people including the game engineering team and QA teams. As part of this it was part of my role to help upskill the team and ensure quality both of the product and the engineering practices.


I worked closely with the GameTeam to ensure that best practices like code reviews were in place bringing them up to what I would expect from the teams and how building with Feature Flags can be a benefit not only for safety of releasing new features but also experimenting in production. I really needed to win over and take into consideration their different backgrounds to ensure they were on the same journey and saw the benefits of these approaches that were new to them.

This resulted in much better code, shared knowledge and was the basis of our LiveOps system ehre we could run multiple experiments with real users to see how this effected our KPIs.
The QA team was an interesting one as I drove the efforts to bring testing to much earlier in the SDLC than was normal in the games world. Resulting in a reduction of bugs and increased player retention.

I learned that part of collaboration with a group of different people is all about bringing them on the journey and not just giving them the answer but helping them see why its important.

- Friends API
  - Working with the Game Team to ensure that there was adequate touch points on what the systems were doing
  - Initially went with API documentation
  - Then moved to blueprints
    - This allowed me to start adding suggestions and improvements around observability to their servers
    - Worked with the team over the next few montjhs to allow this to happen
  - Customer focus is that they work best with certain things
- Anemic Servers
  - Noticed that servers were having a low number of CCU
  - Discussed and debugged with Andy in teh Game Team
  - Created a number of tickets
    - Kick inactive players
    - Matchmaking to be more conscious of servers that are shutting down
    - Unloading parts of the map
- Cross Company - Testing process
  - QA/GameTeam/Production


# A time that you disagreed and came to a compromise

#improbable training the new china team … Playwright an in house configuration tool


## Growing Others

- Dan as Platform Lead
  - Do myself out of a job
  - Allow myself to focus on other things
  - slowly hand over responsibilities
- Dan as GoLang engineer
  - Started by pairing and code reviews
  - small tickets and fixes
  - ended up handing over the design and implementation of whole systems by the end
- Olha
  - worked with her as part of intrim QA Lead

# Working under pressure 

- upgrading the UE4 build agents
  - had to split this out into a number of phases
  - Mitigation
  - Fixing
  - Future Proof

# How do you manage difficult employees
- Mat true infra engineer
- Had to make sure they were touch points
- Initial improvement 
- Slipped back into ways
- Didnt able to resolve
- Document this

# Professional Failings as a Manager

- Heechul not removing soon enough or feedback not getting through
- Dan managing Evgeniy
  - Wasnt ontop of their notes
  - Was giving dan feedback but nto getting through to 

