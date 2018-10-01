# INTRO: Time bandits: don't let these vampires get you

* ?

# Book

* Dominica book, my own with Nancy Van Schooenderwoert
* End of this talk: know the five theives and how to tackle them, and inspired to make work visible

> But why care about this?

# Why care

 "Busyness is an addiction, which doesn't equate to growth or value. It usually means doing a bunch of things that all turn out crappy" - DDeG

* Our culture loves overwork and busyness and we overload ourselves - effectiveness & even efficiency be damned
* By doing so, we lose time to avoidable problems by switching and neglecting work, which is expensive & dispiriting. It's also a correlated to Burnout in the state of devops report.
* We can create habits that create a circle of healthy, sustainable and improvable work.

# Five Bandits

* If someone stole you wallet you'd notice. If someone stole your lunch you might send an email to all your colleagues trying to find the culprit. But if someone steals your time?
* (Foreach: What it is & how it appears, how it steal time, clues it leaves at the scene)

# FB: Too Much WIP

* What: Demand > capactiy -> delay, costs, quality & irratable staff
* Why: 'yes' -> team, fear, shiny, unsure size, please people
* How: Context switching, neglected, wait times
* Clues: Switch, quality, 'yes', cycletime, mastery missing (it's elusive)

# FB: Unknown Deps

* What: 3 types: Software/Hardware (API, cloud), expertise/authorisation, Activity(db restore).
* Why: "Every dep doubles your chances of being delayed or late"  - Troy Magennis 
* How: Blocked work, Unplanned work -> it's expesive when you don't know
* Clues: High Coordination, folk aren't available when you need, unexpected changes to code/plan causes another thing

# FB: Unplanned Work

* What: Work that you didn't expect to be doing. It's important but skipped the planning stage
* Why: Increases uncertainty & removes predictability. Eats planned work for breakfast
* How: High WIP, which is often invisible
* Clues: You've not your planned work 2 weeks later

# FB: Conflicting Priorities

* What: Many prorities. Most number one. Folk aren't paying attention to long things take
* Why: Prioritisation isn't happening. Starting without finishing
* How: More priority meetings for all the projects. WIP bites again. Longer cycle times.
* Clues: "My thing is high priority!", if X not done by Y, multiple when will my thing be done?

# FB: Neglected Work

* What: Like maintainece work to patch servers & tech debt. Old car -> not a problem unless you don't maintain.
* Why: It's important but not urgent. No time for important.
* How: When you least expect it.
* Clues: important neglected work becomes an emergency

# How to catch a thief

* How to we go about catching these thieves as obviously as if our wallet was stolen?
* The problem is that you can't see this theivery. We need to expose it.

# KILL: Make Work Visible

* Get it out of the shadows. It's hard to manage invisible work - as you can't tell if the system in overloaded
* Workflow system that: Make work visible, Limit WIP, Measure and manage flow of work, Prioritise effectively, Make adjustments based on learnings from feedback and metrics
* Ranting doesn't work, but presenting data to leadership does

* KT: Folk prefer pictures over words - it helps us see patterns

# Flow Metrics

* ???????

# KILL: Ambush the ringleader

* Reminder: Endorphins from saying 'yes' -> more context switching -> more interuptions -> less done
* Scrum has a planned WIP limit enforced by the iteration length, Kanban has limits
* Limit WIP: 
  * add tension/enabling constraint. 
  * Limit to team capacity (current-, team size) -> get to 'no'
  * Set by: col, swimlane, worktype, person (don't as drops collaboration)

* KT: Many ways to set WIP limits. WIP create necessary tension

# KILL: Expose Dependencies

* Often too late. More likely with mutliple teams on one system.
* Visualise it: Make a diagram, use swimlanes, tags on stories, org level kanban
  * Now ask what you can do to reduce the impact
* Product teams > project teams
  * If they can design, build, deploy then you win
  * Project teams are on big monolothic batch with high coordination costs
  * Product teams keep the people with the expert domain knowledge consistently involved - use them

* KT: Highlight deps, make them visual, try product teams

# KILL: Unplanned Work

* We need to plan for unplanned work. To do that we need to know the ratio. Then we set a WIP limit to give you the capacity to plan for it.
* Run an experiment to capture interupttions (stickie note, one week), one team added a mark to a story
* Why: This minimises the damage caused by unplanned work, Use the unused unplanned work to work on important not urgent tasks
* Handling interruptions: Concierge. Experiment: Ask teams how they can reduce the impact, what works and why? Try for a week.

* KT: Always be unplanned work, Find the ratio & set the WIP, you can find it and prevent it by an experiment

# KILL: Prioritize, Prioritize, Prioritize

* When priorities are unclear - people take on more WIP. 
* You need to have an explicit priotization policy. Otherwise it's the loudest that decides
* Strategies: HIPPO, CostOfDelay, FIFO, WSJF
* Line of commitment: Backlog are options, once it goes into 'todo' then it will be done

* KT: Unclear priotise == WIP+, few methods to decide, make a line of commitment

# KILL: Preventing Negligence

* Good time management means spending time on important things and not just urgent things
* Spend some time on fire prevention so you spend a lot less time putting out fires
* Call out neglected work: flag 30 days, acknowledge, Create space to finish the most important work. Lower WIP to discuss the priorty of others, do, kill, move it back to backlog.            
* Stop starting, start finishing

* KT: Important work that is neglected becomes urgent, Visualize delays, Call out neglected work

# The LEGO Experiment

* We had visualised the work, reduced WIP and completed all the neglected work.
* After a rocky start, We were building confidence in our ability to delivery bigger bits of work
* But at our retros we felt like a lot of our time was distracted on unplanned work
* Wanted to show stakeholders and management that we were drowning

# Calculate it

* Our challenge was how to make the nature of each week’s work more visible. Show ‘Failure demand’ and ‘Ad hoc’ work and time spent in meetings against planned work.
* Tried whiteboard, tried spreadsheet -> It was a chore
* Development should be fun or your doing it wrong

# Lego

* Each block represents one hour of dev time
* Those blocks are made into a 3d bar chart
* Previous weeks are kept to show the variance after we try new things

# Close up

* Each work represents
* Ran out of orange!

# Daily Review

* Create bricks through the day. 4pm Review
* How can we stop this happening. use 5whys.

JOKE: Glasses. Also lego creating sad children faces.

# Glasgow interlude

* We had been collecting the data for over four weeks when a board room request went out
* They wanted the team to tackle two large projects. The last project had been a disaster that involved the team working the day after Christmas to tidy things up.
* The tech lead of the project said nothing. He walked up to a whiteboard, picked up a pen and wrote a number on the board.

# 23.2%

* If I say something will take 12 weeks. It means you'll get it this time next year.
* There was a stunned silence. Never had the directors been given such insight into the system of work.
* Next they came running down to the work area to see the Lego. They had the most serious conversation ever about lego bricks.

# The stats April

* They asked: How do we get the Orange away? We said it was reports. They found a way themselves to collate their reports without asking us
* They asked: How do we get the red down? We asked for a tester, as it is complex to handle this code. Also we asked for better access to folk who want things since we weren't getting the code right and revisiting work.

# The stats November

* Half a year later and the team spent most of their time on planned work. I reckon this is about average for a team.
* The failure rate was massively cut by the tester and improving the way we picked up work. We added more stakeholder demos to make sure we got things right before they hit production.
* Ad-hoc came down as we introduced a rule saying we were interruptible in two time blocks of 30 minutes during the day.

# Glasgow

* But yes. We managed to improve this team two fold. It was by concentrating on improving collaboration by working as a team.

* Please note. Our team was in a safe context. I could understand if some people didn't want their work tracked

# eBay Background
