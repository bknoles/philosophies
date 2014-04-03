# Software Consulting Philosophies

## Communcation

1. ### Clear communication is as important as technical ability
A technical consultant offers two primary benefits to clients

	1. Technical solutions
	2. Peace of mind that your expertise will solve a business or personal need    
	    
	Deliver both benefits. To me, communicating clearly means:
	
	1. Be empathetic. Understand the client's point of view
	2. Be concise
	3. Don't require unnecessary input from the client [^1]
	4. Send communication regularly
	5. Respond in a predictably prompt manner

2. ### Teaching and educating is a fundamental value
	Teaching is a great marker for expertise.  I have found that those most willing to teach and mentor me are the ones who enjoy thoroughly understanding what they will teach.
	
	Since I enjoy my profession, I believe in applying that attitude to the client relationship.  This does not mean that I teach a client how to code.  It does mean that the client should thoroughly understand how to use the tools that I deliver and how they relate to their business goals.
	
	A great side benefit to this attitude is that teaching requires you to synthesize your knowledge.  You must understand something yourself in order to teach it.  Therefore, by teaching, your own expertise grows. 

## Project Management 

1. ### Thoroughly understand the business and its needs 

	I strongly prefer to avoid discussions of a particular technology when getting to know a client.  I will not recommend a solution like a Rails application, a Wordpress site, an iOS application until I understand what a client wants to accomplish with their business.[^2]
	
	The technology they are familiar with may not be the best fit for their need.  Conversely, they may need a technology I am not familiar with.  They may not even need software technology!
	
	The goal for the client is not a new Wordpress site.  The goal is a platform to reach readers and grow a community or a tool to show off past work to potential clients or something else.

2. ### Prefer to launch quickly and iterate

	Software is very unique in that the existing product can easily be changed and updated.  For this reason, project management techniques that work for physical products don't apply well to software projects.
	
	In the offline world, launches are very important.  A restaurant wants to open with fanfare.  A product like a power tool can't be changed once it is in a consumer's hands.  That's not the case with software.  Software can continuously be updated, and there are plenty of new users online to find.  Fanfare and completeness are often not as valuable in software as the learning you can get from having real users use your product or service.
	
	I prefer a process where a site goes live very early and builds on what it learns.
	
	Structured correctly, this kind of engagement has the added benefit of reducing risk for both the consultant and the client.  The client does not have to commit to, say, 6 months of development before seeing their idea, and the consultant can be paid monthly as opposed to something like a 50% down payment / 50% on delivery arrangement.


3. ### Prefer the simplest implementation of a feature or idea

	This is a corollary to the launch quickly principle, but the idea here is to focus on things that help the client achieve their business goals.
	
	Don't build an iPhone app just because you have the ability to do so.  Don't build a super awesome single page javascript app because you loved the user interface of Trello.  Don't structure your code using advanced design patterns if all you need to do is print the phone number for the client's store.
	
	Prefer to build in complexity when it is needed.  "When it is needed" is a difficult thing to know.  Helping a client decide when complexity is needed and when it is not is one of the most important jobs for the consultant.
	
## Technical Implementation

1. ### Propose Solutions that will solve the business needs

	Solutions for suggestions should be backed by a business reason.
	
	**Bad**: "We suggest building this application as a JSON API that different applications can interact with because that offers a lot of flexibility"
	
	**Better**: "Because we are fairly confident that native mobile applications will serve the target market, we suggest building the application to be able to service many types of apps.  The technical implementation would be that the core software is a JSON API."
	
	**Even better**: "We suggest building a small test site to see if mobile users are inteserested in this product.  If they are, we recommend building the core software as a JSON API so that we can have multiple applications that use the core tech."


2. ### To begin, be technology agnostic

	I don't want to jump to a Wordpress or Rails or javacript or iOS without understanding the problem.  When learning about a client, it's important to understand whether my skill set matches with their business needs.  I won't automatically suggest something as a solution just because I know how to use it.

3. ### Prefer industry best practice methods

	Launching small and iterating can lead to ugly code if you are not careful. Maybe a small application doesn't need automated tests, but eventually it will.
	
	"Duct tape coding" is necessary sometimes, but I will always prefer to do things in manners which are considered best practice.  In order to do this, two things are required
	
	1. Stay up to date on what best practices are
	2. Build in time to refactor and review your code as the project iterates along

4. ### For clients and users, things should "just work"

	A client should never have to clear their cache in order to see updates.  A client should not have to configure their browser a certain way.  Solutions should be as effortless as possible.

	However, simplicity for end users very often means complexity within software, and the "just works" principle should be subject to the previous principles listed above. [^3] 

[^1]: Example: Send emails worded like "We need to upgrade the computer at the store.  I'm going to go on Monday unless I hear otherwise from you.  Is this ok?" Don't send emails like "We need to upgrade the computer at the store. When is a good time for me to go?" As much as possible, clients should be able to respond with "yes" or "no".

[^2]: If a company already has an exisiting technology stack the client has technical prowess, it may not be appropriate to choose or suggest a new technology.  I still believe that I should thoroughly understand the business before any discussion of feature implementation occurs.


[^3]: Example of handling inherent complexity for a feature that you want to "just work": For an online store with physical locations, a program that ties a user's address to a physical location in order to locate the nearest store is much more complicated than displaying a list of all stores and asking the user to choose the closest store. The primary business need is likely getting people to shop at the online store at all, so it takes precedence over the "just works" principle.  The automatic location can be added while users are actually using the site.

