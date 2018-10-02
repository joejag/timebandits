# INTRO: Time bandits: don't let these vampires get you

* Joe Wright, technical coach working here in Scotland.
* I have a strong bias for making whatever I'm trying to understand into something visual. Could be reducing escaped defects and failed deploys. Whatever it is, I find it easier to spot patterns and get control of things by visualizing.

> Last year I met Dominica who did a workshop on this topic and has since written a book this year.

# Book

* (read title): Categorises the thieves.
* End of this talk: know the five theives and how to tackle them, and inspired to make work visible
* Quite cheap and written in an easy to understand way

> But why care about this? Why care about viz and thieves

# Why care

 "Busyness is an addiction, which doesn't equate to growth or value. It usually means doing a bunch of things that all turn out crappy" - DDeG

* Addicted to being busy. 100% calendars - tetris, Taking on more. Quality goes out the window as we neglect and switch tasks while being chased for updates. Crappy.
* Reasearch is showing this behaviour as one of the causes of burnout - taxing our mental health
* So instead, I'd like to share habits that create a circle of healthy, sustainable and improvable work.

> Introduce the thieves We might not even realise are stealing our time.

# FB: Too Much WIP

* What: Demand > capactiy -> delay, costs, quality & irratable staff
* Why: 'yes' -> team, shiny, unsure size, please people
* How: Context switching, neglected, wait times
* Clues: Switch, quality, 'yes', cycletime, mastery missing (it's elusive)

# FB: Unknown Deps

* Known dependecies can get you too.
* What: 3 types: Software/Hardware (API, cloud), expertise/authorisation, Activity(db restore).
* Finding out late is the worst: API change, cloud drops a service, expert not available, db not restored
* How: Blocked work, Unplanned work -> it's expesive when you don't know
* Clues: High Coordination, folk aren't available when you need, unexpected changes to code/plan causes another thing

# FB: Unplanned Work

* Unplanned work sets back planned work and increases uncertainty in your system which ruins your predictability
  * Examples: Expediated work requests and failure demand
  * Not all work has to be preplanned, we live in a complex world
  * Unplanned work brings with it high WIP

* Clues: You've not your planned work 2 weeks later. High performing teams spend 28% more time on planned work (State of Devops 2016)

# FB: Conflicting Priorities

* What: Many prorities. Most number one. Folk aren't paying attention to how long things take
* Why: Prioritisation isn't happening. Starting without finishing
* How: More priority meetings for all the projects. WIP bites again. Longer cycle times.
* Clues: "My thing is high priority!", if X not done by Y, multiple when will my thing be done?

# FB: Neglected Work

* Aging software is like an old car, with regular maintainace (oil change) it'll function correctly. Old software isn't a problem, unmaintained which is hard to deploy is.
* Maintainace is the most neglected type of work (folk chose more revenue rather than protecting). Types include
  * Improving quality, reducing bugs and technical debt payments
* It's important but not urgent.

* Clues: important neglected work becomes an emergency (brushing teeth analogy)

# How to catch a thief

* How to we go about catching these thieves? And removing their control from over us.
* Which all starts with creating a Kanban.

# Aim of Kanban is to make problems come to the surface

* Get it out of the shadows. It's hard to manage invisible work - as you can't tell if the system in overloaded
* Workflow system that: Make work visible, Limit WIP, Measure and manage flow of work and adjust
* Ranting doesn't work, but presenting data to leadership does

# Flow Metrics

* Two metrics are super useful: first is cycle time
  * Cycle time includes waiting time. Despite the focus on the activity parts, it's the queues that dominate
* WIP: In this case for the whole system.
  * WIP is great as it's a leading indicator for when things are going wrong. you don't have to wait
* With Cycle Time and WIP data you can start forecasting how long it would take to deliver a bunch of work items. This gets us away from unneccesary due dates and allows us to be more predictable with our customers.

* KT: In all systems, Predicatbility will go away when WIP increases and the cycle times elongate. The key is adjusting to the point where it works for your team.

> How does this help get rid of the number one problem of too much WIP

# KILL: Ambush the ringleader

* Reminder: Endorphins from saying 'yes' -> more context switching -> more interuptions -> less done
* (JOKE): Look at Jim Carrey here, he's said yes so much he's flying.
* Be the No person. But how do we get there? "stop starting, start finishing" but that's hard.
* We need an enabling constraint to create the tension. Which we do by limiting the possible work allowed.
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
* Why: This minimises the damage caused by unplanned work, Use the unused unplanned work to work on important not urgent tasks

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
* Any change, even a good change, can impact performance.
* Challenges with rolling out new ways of working:
    * WIP limits are scary and unituitive. It means not saying 'yes'.  Select a doable initial WIP limit that says 'no' some of the time.
    * Remind them there's always more demand than capacity. Stay strong
    * Visualisation can make some people afraid. Leadership should relive the fear. No punishing people, change the system

# eBay Background

* In 2007 had this eBay bright yellow background, customers complained when they made it white. So they put it back and dropped the yellow over time.
* Big change is scary, take small steps to improve your work, remember; it's for our health.
* Thank you