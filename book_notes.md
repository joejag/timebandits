# Talk ideas

* Visually show how far through the slides are. Circles filled in like a progress bar
* Lean is flow, Agile is XP practices and hugs
* Avg flow efficiency is 15%
* Standup is just 'system is stable'.

# Foreword

* "Everyone has the same 24 hours in their day as Richard Branson"
  * His control over those hours differ significantly
  * Musk can delgate, depriotize and say no
  * Bezos doesn't need to seek direction from a convultued beuarcracy

* __Parkinson's Law__: Work expands to fill the time available for it's completion
  * Ask any student about when they complete things before a deadline
  * We are constantly doing, coming home exhausted without making a dent in our TODOs. Like the lost sock, where does time go?
  
* Control over work is for health benefits
  * Our culture loves overwork and productivity over effectiveness
  * We can create habits that create a circle of healthy, sustainable and improvable work.
    * Understand where we spend our time through throughtful work systems
    
# Introduction: Work and Flow

* "Do not squander time for that is the stuff life is made of - Benjamin Franklin"
  * Losing time to avoidable problems is expensive and dispiriting. Wasted time cannot be regained. Life is short
  * We overload ourselves and we overload our teams
  * Context switching kills our ability to settle into work and makes us unhappy with the quality of our work

* Why?
  * We are dealing with a dysfunctional process which tries to keep everyone busy (it's the elephant in the room)
  * "Busyness is an addiction, which doesn't equate to growth or value. It usually means doing a bunch of things that all turn out crappy"

* Kanban
  * Kanban is for helping balance our work demand: "The aim of Kanban is to make troubles come to the surface" - Ohno
  * Ranting doesn't work, but presenting data to leadership does
  * Work spends most it's time in __wait states__ (approval, other teams), while we wait we start new things
  * It's hard to manage invisible work - as you can't tell if the system in overloaded
  * Lean: "a strategy of flow efficiency with key principles of just in time and visual management"
  * Limit what you say 'yes' to to just the most important thing at the time + make it visual
  * We want a workflow system that does five things
    * Make work visible
    * Limit WIP
    * Measure and manage flow of work
    * Prioritise effectively
    * Make adjustments based on learnings from feedback and metrics
    
# 1. The five thieves of time
  
"Stealing of course, is a crime, and a very impolite thing to do" - Lemony Snicket

* "If you wallet was stolen, you'd notice. If someone stole your lunch you'd shout about it" DdG
  * But we don't when they steal something more valuable - our nonrewable time - we allow this everyday
  
* Five theives that leave clues - we need to take back control from them
  * Too much WIP: work that's started that's not finished
  * Unknown Deps: Something you weren't aware of that has to happen before you finish
  * Unplanned work: Interruption work
  * Conflicting Priorities: Multiple projects are you are uncertain what the most important thing to do is
  * Neglected Work: Work that sets idle

# 1.1. Too much WIP

 * "Beware the barrenness of a busy life" - Socrates
 
 * "more no, less wip"
   * Hard to say no, especially if we like the person who asks.
   * Reasons folk give
     * Team players
     * Fear: Criticized or fired by boss
     * New and Shiny: more fun
     * Realising the size: "just a couple of hours"
     * We like to please people
  * Vanessa Bohns (Waterloo social psychologist) says we have a fundamental motivation to stay connected, we don't want to reject people or them to think poorly of us. We are __managaing the impression other people have of us__. Also boss's don't realise this power they have over people (most of the time).
  
* too much WIP = Demand > Capactity
  * Issues caused: delay delivery, increasse costs, decrease quality, change priorities, irratable staff
  * Cycle time measures this. It's the time a work item spends in WIP.
  * Cost of Delay goes up, which is a concept used to communicate value and urgency of a task. Such as our product selling this month rather than next.
  * If we wait the customers go elsewhere. When folk hijack features it delays getting things done.
  * Customers being internal and external

* Measures
  * Lead, Cycle time and Throughput are trailing indicators, it only let you know how long things that are finished have taken.
  * __Little's Law__ tells you what to expect now. It's avg.cycle time = avg.wip / avg.throughput.
    * WIP is primary factor

* Indicates of too much WIP
  * Context switching is common: This kills the flow needed for focused motivation. You need a do not disturb ethos.
  * Customers wait a long time: If we start a blog article and while it's editted by someone else we start another one it slows things down
  * Quality is suffering: You lose the time to learn with so many things to do
  * Irratated staff: Mastery cannot happen. We want Mastery because it is elusive as we don't get long enough to deeply think before getting interrupted
  * David Rock says that it can take 20 minutes to get back to the same thinking spot after an interruption
  * You say 'yes' when someone asks for 5 mins
  
 * Kanban (Japanese for signal card)
   * If WIP limits are set the system cannot become overloaded
   * THe limits are liberating as it keeps the amout of work healthy
   * When you say 'yes' you've just authorised work over everything else.
   
 * Key takeaways
   * We say yes regardless of how busy we are
   * Too much WIP stops working getting done, quality and irratates staff
   * WIP and Cycle time are related. High WIP means more waiting time
   * Context switching wastes time and is a consequence of too much WIP
   * Say no if your schedule is full

# 1.2. Unknown Dependencies

"The definition of freedom is that there is no dependency" - Dada Bhagwan

* Three types of dependency:
  * Software/Hardware
  * Expertise: person with specific knowlesge is needed
  * Activity: Something needs to be done first
* Examples: authoritsation, a databse restore to test.
* Example unknown: API changes, cloud providers (99.95% - 22mins a month) and you won't know when and lose time investigating

* Why it matters: "Every dep doubles your chances of being delayed or late" - Troy Magennis
  * Remove one dep and you half total possible dealy combinations are removed
  * Two inputs needed, one in four chance of delivering. 2^n. Binary is either 1 or 0.
  * Example with two inputs: 00, 01, 10, 11. There's only one chance everything is on time.
  * Dinner reservation with four people making their own way. 16 possible outcomes. Not 25% chance of doing wrong, it's 93% situations where things go wrong.
  
* Indicators of unknown deps
  * Coordination needs are high with folk running around trying to align everyone
  * People aren't available when you need them
  * Changing one part of the code/plan unexpectedly changes something else

* Small teams
  * Nothing beats a cohesive group who communicate well
  * But if they depend on other teams the impacts of integration cost can be destructive
  * Improving the perf of one small team can make the rest of the org move slower
  
* Key takeaways:
  * It's expensive when teams don't know about deps
  * Arch, expertise, activities on hold are the common ones
  * Every dep increases chances of being late. Remove them to halve the chance
  * If demand if high on an expert then they won't be available
  * Small teams with tight deps can ruin company wide perf
  
# 1.3. Unplanned Work

* Unplanned work sets back planned work and increases uncertainty in your system: ruining predictability
  * Examples: Expediated work requests and failuredemand
  * Not all work has to be preplanned, we live in a complex world
  * Unplanned work brings with it high WIP

* Key takeaways:
  * Unplanned work eats predictability for breakfast
  * High performing teams spend 28% more time on planned work (State of Devops 2016)
  * The remedy is making it visible amd planning for it, reduce your WIP
  
# 1.4. Conflicting Priorities

"Focus is a matter of deciding what things you're not going to do" - John Carmack

* Example of an overworked department
  * Standup feet shuffle, many lists everywhere
  * invisible work and projects hamper the alignment needed with devs, managers, buz folk to make effective progress - make work visibile
  * folk can look busy, but if nothing is getting finished it's a red flag. You can't sell 90% complete
 
* Many priorities
  * 33 projects and 41 devs. Half were priority number one.
  * Often no one paying attention to how long things are taking - folk start new projects rather than finishing
  * These projects need to be set aside

* "Productivity isn't about being a workhorse, keeping busy, or burining the midnight oil. It's about priorities and fiercly proteting your time - Margarita Tartakovsky"
  * Often folk have more projects than people to work on them, so they need priority meetings
    * Reduce the projects and they'll have better focus and meetings will be shorter. Less interuptions.
    * WIP bites again
  * Longer cycle times delay important feedback
  * If everything is priority one, nothing is. It could be the best thing you can do is go help someone else deliver

* Indicators:
  * When will my thing be done?
  * My thing is high priority!
  * If my thing doesn't get done by X, then Y

* Key takeaways:
  * There is one most important thing - let folk know what it is
  * Conflicting priorities happens when folks don't know what's highest priority - then WIP
  * Priorities can clash
  
# 1.5. Neglected Work

* Aging software is like an old car, with regular maintainace (oil change) it'll function correctly. Old software isn't a problem, unmaintained which is hard to deploy is.
* Maintainace is the most neglected type of work (folk chose more revenue rather than protecting). Types include
  * Improving quality, reducing bugs and technical debt payments
* It's important but not urgent.
* Zombie low value projects go around. Kill them as they take away important work.
* Sunk Cost Fallacy: Only consider more investment in comparison to it's economic return

* Indicators:
  * Delayed tasks become emergencies
  * Metaphor: Anniversary dinner batching up
  
* Key takeaways:
  * If not dealth with, important neglected work becomes an emergency
  * Beware of invisible tech debt piling up
  * Kill zombies or make them a priority.
  
# 2 How to expose time theft to optimise workflow

* We acquire more info through vision then the rest of our senses combined
  * Two thirds are visual-spatial learners - we don't engage or learn unless we can see patterns - not a preference
  * We want to physcially display mental labour - which you can't see
  * making things visual makes it easier to make decisions
  
# 2.1 Make Work Visible

 * Quadrants example: Visible, Invis, Positive, Negative. Easy on the eye, accurate, meainful and efficient
 * Start with Todo, doing, done - so simple it doesn't need explanation
 * Don't put everything on there as it distracts you, plus things will change. Less than 15 skip unless
   * Only one person knows it, the work impacts other teams. all tasks are small for the person
 * Folk usually complaing about interuptions and conflicting priorities
 * You need to discover your work categories
 * Don't overengineer your Kanban up front, it'll become self-evident through usage
 
 * Key takeaways
   * Folk prefer pictures over words - it helps us see patterns
   
# 2.2 Ambush the ringleader

 * Remember the five reasons we take on work. Number one being we get endorphins by saying 'yes'
 * Too much WIP means work is arriving faster than you can complete it
 * To help with communication you can categorise the work do decide what to do: management, biz, internal
 
 * WIP Limits
   * You can set them by: column, swim lane, work type, or person (if new - but don't as it goes indiv goals rather than team)
   * Add tension to the system - they are the constraint that enables completion of work
   * Waiting on feedback is a big waste usually
   * Like rotten fruit, knowledge decays faster then we'd like
   * Limit WIP to the teams capacity
   * More WIP means more interruptions
 
 * Key takeaways
   * Many ways to set WIP limits
   * WIP limits create necessary tension
   
# 2.3 Expose Dependencies

 * By the time you see them you are already in deep water, there is always hope though
 * Happens more often when you have mutilple teams on one big system
 * When you heard "oh btw, you need to do this today" it's got you

* Diagrams to help
   * Matrix of teams being impacted by another
   * SAFE string one
   * Swimlanes
   * Tags on stories with dependencies
   * Kanban of deps
* Start simple is better than not starting
* Ask what actions can be taken to reduce the risk of breaking or negatively impacting another team
 
 * Product teams > project teams
   * If they can design, build, deploy then you win
   * Project teams are short lived tempoary teams, they move all knowledge to the Ops team expensively, who then have to interuppt them, creating WIP
   * Project teams are on big monolothic batch with high coordination costs
   * Product teams keep the people with the expert domain knowledge consistently involved
   * Use the visulisation to help have the discussion about 
   
 * Key takeaways
    * Small teams are fast unless they slow others down
    * Boards need to highlight deps
    * Make them visual
    * Visualise deps between
    * Go product teams
    
# 2.4 Unplanned Work

  * Run an experiment to capture interupttions (stickie note, one week), one team added a mark to a story
  * We need to plan for unplanned work. If you don't record it you can end up saying "we've been busy" to stakeholders when they ask where their stuff is. With no evidence it's the perfect crime
  * Know the ratio of unplanned work and set the WIP limit. This gives you the capaity to handle it
    * I've often heard allocated 50% to X, 25% to Y. Life does not break down that way. Total BS!
    * This minimises the damage caused by unplanned work
    * Use the unused unplanned work to work on important not urgent tasks

  * Handling interruptions
    * Concierge, office hours / DND hours
    * Experiment: Ask teams how they can reduce the impact, what works and why? Try for a week.
    
  * Key takeaways
    * Always will be unplanned work
    * Know the ratio to help set WIP limits
    * Size of tasks doesn't matter when folk only work on one thing at a time
    * Office hours helps minimize damange from unplanned work
    
# 2.5 Prioritize, Prioritize, Prioritize

 * When priorities are unclear - people take on more WIP
 * Methods:
   * HIPPO
   * Cost of Delay
   * First-in, First-out
   * Weighted shortest job first (WSJF)
 
 * Problem with HIPPOS
   * It's possible they are right. But Cognitive bias, misaligned goals and over confidence. We are often confident even when we are wrong
   * Make rules explicit or they'll be made by the loudest or most aggressive person or highest paid
  
 * Line of commitment
   * Backlog are options, once it goes into 'todo' then it will be done
   
 * Exercise questions:
   * What is your priority policy and how it it visulatized?
   * Where is your line of commitment?
   
 * Key takeaways
   * People take on more WIP when there are unclear priorities
   * Use A3 to help have the conversation around change
   * Many ways to priortise: Cod, FIFO, HIPPO, WSJF
   * Visualise priorities
   * Lines of commitment
   
# 2.6 Preventing Negligence

 * "Never let something important become urgent" - Eliyahu Goldratt
 
 * High WIP means bad stuff happens: context switching increases bottlenecks, dependencies arise, lose opportunities and holidays arrive

 * If work sits around untouched for weeks then we forget the details, and it takes time to get back into it.
   * A half-completed bridge brings no value
 * Good time management means spending time on important things and not just urgent things
   * Spend some time on fire prevention so you spend a lot less time putting out fires
   * We avoid going to the doctors until something is really wrong
 
 * Call out neglected work
   * Flag items on the board that haven't been updated for 30 days
   * Ask what we can do to close it? Is it worth saving? Is there a quicker way? Is it a zombie?
   
 * How to deal with neglected work:
   * Acknoledge the neglected work
   * Create soace ti fubusg the most important work. Lower WIP to discuss the priorty of others, do, kill, move it back to backlog
   * Stop starting, start finishing
   
 * Exercise: Create an aging report
   * Find a number of work items that haven't been updated for over 30 days, foreach:
     * Get the number of days
     * The average cycle time for similar cards
     
 * Key takeaways
   * Important work that is neglected becomes urgent
   * Visualize delays
   * Call out neglected work and purge low-value projects
   
# 3. Metrics, Feedback and circumstances

# 3.1 Your Metrics or your money

* Making work visible is the secret to exposing time theives

* Some teams use abritrary due dates, but we should be smarter with probabilistic approaches
  * World cup is a due date, HMRC have real due dates. CRM system live or UX enchancements, they can wait without much damange
* If expectations are set, you don't need due dates, predicitability is what counts. It makes leadership happy too
  * The biggest complaint is that things take too long. But why? Often the probelm starts with the due date.
* Hofstaler's law. Everything takes longer than expected, even if you take the law into account. How often do things come early?
* The delays start once the due date is set. The thieves go about with dependencies, the DB may not scale and folk get sick.
* It is tought to make decisons about delivery timelines and dates without compelling evidence. The lack of data means folk use opinions rather than good date.
  * Imagine flying a plane without a fuel guage, compass and speed indicator. Hard for the flight tower too. We are blind to problems in IT because we don't have anything that tells us how we are doing.
 
* The best metrics are flow metrics: lead time, cycle time, WIP and aging reports.
  * When asked how long X will take folk usually add up how long each step in the process will take plus a buffer.
  * We are always optimisitc when thinking when things will be done.
    * It's vunerable when things are complex, and time thieves will come in
* Flow metrics: quantify the probability of completing x% of the work in so many days.
  * We can report that there is a 90% chance this type of work will be complete within 10 day
    * This helps our customers are we become more predictable.
  * Lead and Cycle time measure flow: Pizza order example. Internal teams try to reduce the wait time to be more efficient.
    * It differs, but in software it tends to be when they start working on it.
  * Predicatbility goes away when WIP increases and the flow times elongate.
  * WIP is a leading indicator given __Litte's Law__
    * Law's have assumptions to work (Litte's: Measurement is consistent, stable system, balanced, all finishes)
    
* Queueing Theory
  * 100% capacity utilisation with doctor. 10 hours or 7 hours. Sick patient gets seen faster, knocking all the other customers.
  * Higher utitization the longer the wait. Especially with things with high variability like IT
  * Computers stop responding at 100%. Motorways clog up and slow down.
  * Single most important factor in queue size is capacity utilisation. __Kingsman's formula__.
    * 80-80% queue doubles. 80-90, 90-95. It goes nearly exponential after that until things grind to a halt.
    * Slack time is one way of a company ensuring things aren't at 100%
    * We don't let our computers get to 100%, don't do it to humans
    
* Watch the work, not the people
  * Aging reports are good
  * Nice visualisation on page 150 for flow efficiency
  * "Well will it be done" does not take into account queing time. Wait time is the longest
  * Batch sizes
    * Boeing get econmies of scale as their transaction costs are high for a single plane
    * For knowledge work this doesn't scale as coordination costs grow non-linearly with batch size
    * Bannanna example: buy 6 months, transaction cost is low, they spoil. Buy everyday, transaction high, no spoilage. Somewhere in between is the right amount.
    * Small batches are great in Lean as they reduce WIP, accelerate feedback, improves cycle time, quality. Code can spoil too.
    * Small batches is an enabling constraint as you get faster feedback
    * Small batches give predictable lead times in most VS. Which is why we focus on creating smooth flow
    
* Key takewaways
  * Delays are common, use flow metrics to help make good decision on priority, WIP limits and capacity utilization
  * Don't let yourself get to 100%
  * Look for optimal batch size to help you be efficient with low transaction costs
  
# 3.2 The time theif o'gram

* Intent is to look at metrics that increase risk. Velocity, bugs, deployments don't revewl much about risk
* Measure the cause the problems in the first place, which affects delviering quality work quickly.
* WIP is a leading indicactor that signals problems early

# 3.3 Operations Review

* Meeting to share data about how teams are performing and suggestions
* Five mins per manager to present then 2-3 for questions and comments.
  * Metrics to present
    * Throughput (CFD)
    * Cycle Time (visual)
    * issues and blocked work items
    * One of the time thieves
    * Also perhaps: aging reports, card type distribution, failure load, flow effieciency
  * We want to improve these to help deliver predictability

* Train example
  * Land slide (unplanned work)
  * Freight train priority (conflicting priorities)
* These are the things the Ops Review would get to discuss

* Key takeaways:
  * Ops review lies the foundation for improvment
  * Flow metrics work well
  * Track things over time
 
# 3.4 The Art of the Meeting

 * Lean Coffee by Jim Benson
   * Doesn't just change the tone, it changes culture around them
   * Listen more than you talk
 
 * Stand-ups
   * Wrong the room standup is boring and uneccesary. Folk just figure out what to say rather than listen to others fully
   * New questions
     * What work is blocked? Risk of getting blocked? Any work that isn't on the board
 
 * Key takeaways:
   * Lean coffee is good. Scrum standups are boring
   
# 3.5 Beastly practices

  * Red flag cheat sheet
     * Flow metrics must include weekends of they can be challenged
     * High activity does not mean high biz value
     * Gantt charts don't include wait times due to high utilization of the workers
     * Instead of due dates, reduce WIP, use CoD and reduce batch size. Decouple architectures and remove the need for specialists
     * Individually named swimlanes
       * Stand ups focus on individuals rather than the work
       * Perception of poor performance of folk that aren't moving work. Unplanned work can do this
       * People don't touch work outside their own lane. Causes greater specialization which creates unknown dependencies
       * Prevents collaboration as everyone fully utilized.
       * Alternative is by work type

# Conclusion

  * Any change, even a good change, impact performance. See J Curve
  * eBay bright yellow background, customers complained when they made it white. So they put it back and dropped the yellow over time.
  
  * Challenges with rolling out new ways of working:
    * WIP limits are scary and unituitive. It means not saying 'yes'.  Select a doable initial WIP limit that says 'no' some of the time.
    * There's always more demand than capacity. Stay strong
    * Visualisation can make some people afraid. Leadership should rlive the fear. No punichsing people, change the system
  
  * How you can veer off course
    * Focusing too much internally and not enough on stakeholders/customers. Strike a balance
    * Being perfect, deliver early to get feedback
    * Visualise your current rather than desired reality
 
  * Scrum vs Kanban
    * Super similar, just different constraints
    * Scrum uses two week time boxes, Kanban uses WIP limits

  * Make change in a series of small changes steps.
  
  * Somerset roads example. Need to research this
  
  
   
  
