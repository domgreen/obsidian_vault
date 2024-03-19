## Mission Statement

Epic Games's mission statement is "To create fun games we want to play and building the art and tools we need to bring those games to life."

```
Date/Time: Mar 18, 2024 10:45am-11:30am GMT Interviewers: Adam Harrison | Principal Platform Engineer Olga Sermon | Senior Engineering Lead
```

[Adam Harrison](https://www.linkedin.com/in/awharrison/)
[Olga Sermon](https://www.linkedin.com/in/olga-sermon-787527a4/)

**Culture and Team fit**
- asking behavioural questions about experienceds that I have had

```

```

- collaboration and culture

```
- culture is what you tolerate
- good culture
  - strong communication
  - empatetic and egoless (humility)
  - passion to learn/do better
- bad culture
  - rock star solo engineers
  - being smart and adding complexity
  - no room for discussion (command and control)
- cross team collaboration
  - QA left shift
    - QA was often just involved at the end of the processs
    - writing test plans
    - signed off by engineers
  - Peek Behind the curtiains
	- getting all differetn teams together
	- keep saying the same things
	- record it
	- share it after
  - LiveOps / Feature Flagging
    - backbone of the company
    - needed to get buy in from people
    - not always easy asking ppl to take a leap of faith
    - talk through the details
    - only really see the benifit once its working
    - DATA team wanted more autonomy of changing and experimenting
    - Exec Level wanted to release more often
    - GameTeam required upskilling
```

- dealing with ambiguity
	- change of requirements

```
- ask clarifying questions, especially when you are being given a solution find out what the real underlying problem might be?
  - clearly define what is in and out of scope
    - defining out of scope often highlights assumptions
  - GameTeam wanted another Linux Build box.
    we need more build agents (why?)
  - the others are always in use (why?)
  - the build takes a long time to complete (why?)
  - shaders are being built, c++ is being built (why?)
  - we dont have a DDC cache and clear intemidate folders (why?)
  - the original build team wasnt aware of this.
- build out in an incremental way
  - start with the base funcationality
  - see if you can integrate this
  - keep communication high with the team your working with
- Plan for future change
  - friends API 
- road map being very visible
  - Platform Team roadmap
  - top of each of the teams slack channels
  - each time it was updated a image and link shared
  - explain the changes
  - ensure other teams are doing the same
  - over share say it say it say it
- Changing Requirments
  - Friends API
	  - started global
	  - changed to regional for implementation speed
	  - kept the design doc with all the opinions
	  - shipped it one way
	  - then changed again to be global
	  - had designed it in such a way to deal with this
  - Character API
	  - want to bring back certain criteria
	  - team wanted to add various things
```

- empathy
	- understanding that you need empathy with other engineers and why things might have been done in such a way
	- compromises
		- shipping something that works over doing something perfect

```
- perfect is the enemy of good
- value is only realised when we get it in the hands of the customer
- People have different priorities
  - Game team are getting hit to make the fun
	  - Dont want to deal with anything else
  - QA team are getting hit for bugs getting into prd
  - Platform team flip flopping between priorities
- Assume the best decision based on the information was done at the time
- no mercy no malice
- Git & Code Reviews
  - team didnt see the value of code reviews
- On Call
	- Game team didnt want to be on call
	- understandable that they dont want to be disturbed at evening or weekend
	- dug into why and they were all reasonable
	- how could we make on call less risky
		- improve QA, flagging etc. better reviews
		- No Friday releases :(
- No Friday Releases
- Times I didnt show enough empathy
	- Great learning peices if you reflect over them
	- Code Reviews
	- Playwrite with the China Engineers
```

- communication skills
	- how do you go about having discussions
	- nurturing a conversational environment
```
- be aware of personal impact
- give praise loud and publicly
- give feedback directly and timley
- Try and be as direct and open as possible
- ask the questions and encourage others to do so
- make space and time for conversation (co-working spaces)
- get comfortable with silence
- hold people to account
  - document one to ones with actions and follow up on those actions
- Give pause for others to speak
- invite counter arguments
- realise people have different communication preferences
  - inability to focus etc. 
```


## Questions

- If you could change one thing what would it be?
- Adam
	- Talk me through a typical week in the life of a platform engineer at Epic
		- roles and responsibilities
	- Transition from SA to Epic?
		- what would do you miss?
	- Ability to have impact?
		- If you see somethign that is adding friction what do you do to solve it?
	- What additional responsibilites can you take on over time?
- Olga
	- What does career progression look like at Epic?
	- How does feedback work?
	- How would you describe your management / leadership style?
	- What would the first 3months look like in the role?
	- What is the overlap between platform and the other teams, which teams do you support
	- How to build a culture and team cohesion
		- what is the teams identity?
	- How is performance of the team measured
	- Vision for the team
		- why keep this team and split out the other?


## Interview

- Discuss culture at the previous company
- discuss the challengages or remote and how you overcame these
- what would be the first thing I did in the role?
- how would you go about making hte product better?
- building trust with the team and customers
- what would i look for in a senior engineer
- what about junior
- what if they didnt want to do tests for example?
- on-call
	- expected to be on call
	- team is respoinsoible for the underlying aspects of it
	- ownership based 
- build vs buy discussions
- what do you expect from the manager


### My questions
- onboarding
	- 30 days get the machine up and running
	- start some tickets
	- understand the stack people and role
	- look and contribute to the roadmap
- performance
	- measured by goal settings 
	- getting things done
	- good team member
- Leadership style
	- olga 
		- coaching
		- transparency 
	- Adam
		- build concensus
		- discuss and communicate
	- Role
		- CDP
		- core team 
		- focus on domains
			- less horizontal discussions
- Carreer path
	- IC/engineer
	- team leader
	- management
- Currently building 2 products
	- ontop of existing platform
	- work closley with the existing teams
- sister teams take care of provisioning
- online is a customer
- fortnite is a incoming customer
- Consolidation of the platform


