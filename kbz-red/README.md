# Kanban-Zai Extension "Red"

Kanban-Zai RED is a delivery process that optimises for delivery speed.

It achieves this by managing a Technical Debt backlog rather than a product backlog.

Technical debt is identified and ordered constantly in a queue.  The top of the queue is worked on at a rate defined by the speed limit and new work is considered at a rate defined by the teams cadence and speed limit.

A useful property of this strategy is that technical debt can be amortized.  That is to say things with high uncertainy can be pushed to the bottom of the queue until such time as there is more certainty around them OR they become redundant and drop of the queue completly.

It is best used in the situation where there is the potential of changing landscape of technology and requirements 
where there maybe unknowns and worse, unknown unknowns.

It can be imagined as a funnel.  The wide end of the funnel represents the beginning of a project, where there is a lot
of setup and investigation to be done and the work estimates are always large.  Whilst the narrow end can be thought 
of as feature complete or ready for a B.A.U team to take over, and work esitmates are always small.

Running for a few weeks at small work esitmates is the clue that you are about to move to B.A.U, with the caveat that some technical debt may not be amortized as expected, in which case some large chunks of work may start to appear and be tackled by the team.

The primary benefit of a RED team is you can start development without to much process overhead and introduce more 
process if it becomes required.

# Technical Owner

An interesting feature of RED is the inclusion of a Technical Owner, whose purpose is keep the quality output of the 
delivery team high by helping the business owner and product owner write relevant value proposals.

A technical owner can give 2 different types of advice.  Opinion and considered opinon.  Considered opinion is a best 
guess based heavily on past experience and is formal advice given to the team.  Opinion is not formal advice.  

A technical owner does not give expert advice or any advice on Artifical Intellegence except where they have explicitly
stated that they are an "expert in a niche" or have explicitly stated they enough experience in the articifial 
intelligence domain to give a considered opinion.

# SETTINGS

### CADENCE

Use cadence as your projects TICK.  Aggree as a team to change directions or prioritize or add work only on a tick.

### DELIVERY QUEUE

A list of all work sorted by weight ASCENDING.

# NORMS

### WEIGHTING

Team members must continually weight cards.  The higher the number the more weight they have therefore lower weight cards are done first.

### FAILFAST

In a rapid release environment you are not always going to have the best value proposition, so a good strategy is to
try, and then find out really quickly that you are wrong. This will enable you to pivot quickly.
