

2. Can you discuss your experience with bug tracking and test case management tools? What strategies do you use to prioritize testing efforts?
	- Jira 
	- Heavy involvement with the team
	- Prioritise based on impact
	- Money always highest priority
	- Connection
	- Does it effect everyone or just a small perent
	- Game Team and Platform slightly different
	- Rollout cadence mostly makes this a thing

3. Describe your process for identifying and addressing software defects or vulnerabilities during development.
	- Ideally come from an alert based on metrics and observability
	- When we find something that wasnt covered we make sue that it is added to the backlog
	- If not will come from customer reports
	- HelpDesk
	- Adding various touch points to make it more seamless to view the requests and impact
	- Being able to locate where in teh system the issues were being found
	- An example
	- Incorrect ordering of friends
	- Onion of Doom
	- Connection issue
	- Logs via the all the various connections
	- Data too large to push over the RDP connection in time
	- Slimmed down the response with field mapping
	- Discussions with the team about their data strucutures

9. How do you stay current on industry trends and emerging technologies relevant to game development?
	- This is something in a startup that I struggled with as it was constant go
	- Decided to put specific time in my calendar to focus on this 
	- Investigate things around tech or projects that we were looking to adopt
	- Looking at places like large org blogs or projects
	- GitHub / Newsletters etc.
	- Decondstuctor of Fun
	- YouTube … GDC / CNCF / Primeagen  

13. Walk us through your approach to creating clear and concise documentation for both internal and external stakeholders.
	- Documentation is part of the “Done Done” for a project 
	- Using PostMan as a documentation source for APIs
	- Moved onto implementing the APIs in C++ with Blueprint wrappers

14. Can you provide examples of how you’ve contributed to improving team workflows or processes within a game development environment?
	- Reducing the build times 
	- mac OS builds with intermediate folders not always cleaned
	- Containerisation to have multiple builds
	- Looking at code review process and how that can help
	- Looking at the depth of the project 
	- Sharing experiences  outside of the company

15. Describe a challenging technical problem you’ve encountered during game development and how you overcame it.
	- Anemic servers 
		- Worked with the team to boot idle players
		- Matchmaking 
		- Instanceing and reuse of servers

18. Discuss your experience with performance profiling tools and techniques, particularly as they relate to optimizing game performance on various hardware configurations.

	-  Non-game 
		- base server has pprof etc. installed so at anypoint we could profile the code
		- Tracing 
		- Load testing
	- Game Server
		- Load testing tools
		- Spinning up clients that would be headless chickens
		- Connect into a server
		- Ensure that the data is good
		- Rsync the perf data of running servers
		- Bugsplat
	- Game Client
		- Analytics    
		- Pushing metrics back to the server

20. Share an example of a time when you had to balance multiple competing priorities during a project. How did you manage your workload and ensure timely delivery?
	- Upgrade of UE4 game engine 
	- Was a hard limit on Google to update to the latest payments API
	- Was struggling to containerise or build out the engine
	- Decided to split the project
	- Focused on mitigation
	- Working on retention emails at athe same timer
	- Got the PoC working with teh team
	- Hand off to other engineers
	- Learnings is to bring people on teh journey 

21. Describe how you’ve effectively communicated technical concepts or limitations to non-technical team members or stakeholders.
	- Production team were often struggling with platform work as it was different to the game side    
	- Adding business value to all epics
	- Being careful of hte wording we used to the wider company to not use tech specific terms
	- Login flow 
	- Diagrams (peek behind the curtain)
	- Design docs … read like a newspaper
		- Exec summary

25. Describe a challenging aspect of working on a live service game, such as Fortnite, and how you would address it to maintain stability and user satisfaction.

	- Feature flags
	- Communication to players
	- In game messaging system at boot
	- Allowed us to communicate early that we were working on something