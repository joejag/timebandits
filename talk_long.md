Time bandits: don't let these vampires get you

---

How much time does your team spend on planned work? The work that's going to propel your business further? 80%, maybe 60%? The reality is probably nearer 30%.

Failure demand, dependencies and unplanned work run amok in our organisations. If we want to improve performance, we need to find ways to expose this work and improve it.

During this session, you'll discover how different types of time bandits take you away from hitting your goals. Once we understand them better, then we'll look at ways to visualise them. Once exposed, we can focus on strategies for resolving them. Then finally we can get some work done.

We'll go over the 3 main types of work: planned, failure and ad-hoc. Then explore Dominica DeGrandis' time thieves of:
* too much work-in-progress
* conflicting priorities
* unknown dependencies
* unplanned work
* neglected work

We'll see how to visualise these in charts as well as how to use LEGO to create an engaging alternative.

-----

* Intro
    * Combination of work by Dominca De Grandis and my own applications of visualising work
    * Why care
        * Our culture loves overwork and productivity over effectiveness
        * We overload ourselves and we overload our teams
        * "Busyness is an addiction, which doesn't equate to growth or value. It usually means doing a bunch of things that all turn out crappy" - DDeG
        * Losing time to avoidable problems is expensive and dispiriting. Wasted time cannot be regained. Life is short
        * We can create habits that create a circle of healthy, sustainable and improvable work.           

* The Five Bandits Intro - Five thieves that leave clues - we need to take back control from them
    (Foreach: What it is & how it appears, how it steal time, indicators)
    
    * Too much WIP: work that's started that's not finished
        * What: 
            * Demand we work on > Capacity
            * Issues caused: delay delivery, increasse costs, decrease quality, change priorities, irratable staff
        * Why:    
            * We say yes regardless of how busy we are
                * Reasons folk give: Team players, Fear: Criticized or fired by boss, New and Shiny: more fun, Realising the size: "just a couple of hours", We like to please people        
        * How:
            * Context switching wastes time and is a consequence of too much WIP (20 minutes to get back to the same thinking spot after an interruption)
        * Indicators:
            * Context switching is common: This kills the flow needed for focused motivation. You need a do not disturb ethos.
            * Customers wait a long time: If we start a blog article and while it's editted by someone else we start another one it slows things down
            * Quality is suffering: You lose the time to learn with so many things to do
            * Irratated staff: Mastery cannot happen. We want Mastery because it is elusive as we don't get long enough to deeply think before getting interrupted
            * You keep saying yes

    * Unknown Deps: Something you weren't aware of that has to happen before you finish
        * What: 
            * Three types of dependency: Software/Hardware, Expertise: person with specific knowlesge is needed, Activity: Something needs to be done first (a databse restore to test)
            * Example unknown: API changes by a third party
        * Why:
            * "Every dep doubles your chances of being delayed or late"  - Troy Magennis
            * Dinner reservation with four people making their own way. 16 possible outcomes. Not 25% chance of doing wrong, it's 93% situations where things go wrong.
        * How: 
            * Blocked work (expert not available), unplanned work. It's expensive when teams don't know about deps
        * Indicators:
            * Coordination needs are high with folk running around trying to align everyone
            * People aren't available when you need them
            * Changing one part of the code/plan unexpectedly changes something else

    * Unplanned work: Interruption work
        * What: 
            * Unplanned work sets back planned work and increases uncertainty in your system: ruining predictability
        * Why: 
            * Unplanned work eats predictability for breakfast
        * How: 
            * Unplanned work brings with it high WIP
        * Indicators:
            * You find you've not progressed two weeks later despite being busy. When questioned you can't say what you were doing

    * Conflicting Priorities: Multiple projects are you are uncertain what the most important thing to do is
        * What: 
            * "Focus is a matter of deciding what things you're not going to do" - John Carmack
            * Many prorities. 33 projects and 41 devs. Half were priority number one.
            * Often no one paying attention to how long things are taking - folk start new projects rather than finishing
        * Why:    
            * If everything is priority one, nothing is.
        * How: 
            * Often folk have more projects than people to work on them, so they need priority meetings
            * Reduce the projects and they'll have better focus and meetings will be shorter. Less interuptions.
            * WIP bites again
            * Longer cycle times delay important feedback            
        * Indicators:
            * When will my thing be done?
            * My thing is high priority!
            * If my thing doesn't get done by X, then Y

    * Neglected Work: Work that sets idle
        * What: 
            * Aging software is like an old car, with regular maintainace (oil change) it'll function correctly. Old software isn't a problem, unmaintained which is hard to deploy is.
            * Maintainace is the most neglected type of work (folk chose more revenue rather than protecting). Types include
            * Improving quality, reducing bugs and technical debt payments
        * Why:    
            * It's important but not urgent.
        * How: 
            * When you least expect it.
        * Indicators:
            * important neglected work becomes an emergency

* How to kill the bandits:
    * Make Work Visible
        * It's hard to manage invisible work - as you can't tell if the system in overloaded
        * Kanban is for helping balance our work demand: "The aim of Kanban is to make troubles come to the surface" - Ohno
        * Ranting doesn't work, but presenting data to leadership does
        * We want a workflow system that does five things
            * Make work visible
            * Limit WIP
            * Measure and manage flow of work
            * Prioritise effectively
            * Make adjustments based on learnings from feedback and metrics

    (Foreach: )    


    * Ambush the ringleader
        * Number one being we get endorphins by saying 'yes' -> more context switching -> more interuptions
        * 'more no, less WIP'
        * Limit WIP
            * Add tension to the system - they are the constraint that enables completion of work
            * Limit WIP to the teams capacity, a few ways to do this, but it'll be wrong - start with the current WIP - an amount. You want to get to 'no' to something
            * You can set them by: column, swim lane, work type, or person (if new - but don't as it goes indiv goals rather than team)

    * Expose Dependencies
        * By the time you see them you are already in deep water, there is always hope though
        * Happens more often when you have mutilple teams on one big system
        * Diagrams to help
            * SAFE string one
            * Swimlanes
            * Tags on stories with dependencies
            * Kanban of deps
        * Once you have it: Ask what actions can be taken to reduce the risk of breaking or negatively impacting another team
        * Product teams > project teams
            * If they can design, build, deploy then you win
            * Project teams are on big monolothic batch with high coordination costs
            * Product teams keep the people with the expert domain knowledge consistently involved
    
    * Unplanned Work
        * Run an experiment to capture interupttions (stickie note, one week), one team added a mark to a story
        * We need to plan for unplanned work
        * Know the ratio of unplanned work and set the WIP limit. This gives you the capaity to handle it
            * This minimises the damage caused by unplanned work
            * Use the unused unplanned work to work on important not urgent tasks
        * Handling interruptions
            * Concierge, office hours / DND hours
            * Experiment: Ask teams how they can reduce the impact, what works and why? Try for a week.

    * Prioritize, Prioritize, Prioritize
        * When priorities are unclear - people take on more WIP
        * Methods:
            * HIPPO (It's possible they are right. But Cognitive bias, misaligned goals and over confidence. We are often confident even when we are wrong)
            * Cost of Delay
            * First-in, First-out
            * Weighted shortest job first (WSJF)
        * Make the policy explicit
        * Line of commitment
            * Backlog are options, once it goes into 'todo' then it will be done
    
    * Preventing Negligence
        * If work sits around untouched for weeks then we forget the details, and it takes time to get back into it.
            * A half-completed bridge brings no value
        * Good time management means spending time on important things and not just urgent things
            * Spend some time on fire prevention so you spend a lot less time putting out fires
        * Call out neglected work
            * Flag items on the board that haven't been updated for 30 days
            * How to deal with neglected work:
                * Acknoledge the neglected work
                * Create space to finish the most important work. Lower WIP to discuss the priorty of others, do, kill, move it back to backlog
                * Stop starting, start finishing
    


* Measuring and standups
    * Making work visible is the secret to exposing time theives

    * Flow Metrics
        * The best metrics are flow metrics: lead time, cycle time, WIP and aging reports.
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

    * Standup is just "What's unstable?"


* The LEGO Experiment
    * Glasgow
        * Calculate
    * Lego
        * Close up
        * Daily Review
    * Boardroom ask
        * 23.2%
        * Stat breakdown
        * November


* Any change, even a good change, impact performance. See J Curve
  * eBay bright yellow background, customers complained when they made it white. So they put it back and dropped the yellow over time.
  
  * Challenges with rolling out new ways of working:
    * WIP limits are scary and unituitive. It means not saying 'yes'.  Select a doable initial WIP limit that says 'no' some of the time.
    * Remind them there's always more demand than capacity. Stay strong
    * Visualisation can make some people afraid. Leadership should rlive the fear. No punishing people, change the system