# RACExp Methodology

- **R**ealistic **A**gile **C**oncepts for **EX**treme **P**rogramming

> ![RACExp](./images/racexp-racetrack.png)

## TLDR

- uses the `race team metaphor` as the ontology of rapid prototyping/product development
  - Realistic: pragmatic organization & management approach for high performance developers, startups and enterprise teams
  - [Agile](https://www.metaltoad.com/blog/most-agile-thing-you-can-do-throw-away-agile): the practical parts of agile
  - [Concepts](https://en.wikipedia.org/wiki/Extreme_programming#Concept): overarching thereotical practices
  - [Extreme Programming](https://www.amazon.com/Extreme-Programming-Explained-Embrace-Change/dp/0321278658)

## [THE FIELD](https://en.wikipedia.org/wiki/Glossary_of_motorsport_terms)

- The competing races on a track.
  - `the pits` + `the grid`
  - all the tickets that could potentially be worked on

## [THE PITS](https://en.wikipedia.org/wiki/Pit_stop)

- In motorsports, a pit stop is a pause for refueling, new tires, repairs, mechanical adjustments, a driver change, as a penalty, or any combination of the above. These stops occur in an area called the pits, most commonly accessed via a pit lane which runs parallel to the start/finish straightaway of the track
  - tickets that require business + engineering attention

## [THE GRID](https://en.wikipedia.org/wiki/Glossary_of_motorsport_terms)

- The starting formation of a race, generally in rows of two for cars and three or four for bikes. The Indianapolis 500 traditionally has a unique grid of three cars per row.
  - tickets ready to be developed

## THE RACE

- I like to use 4 in progress tracks (see `THE GROOVE` below)
- depending on the drivers part of your team, and each developers capabilities, will determine the set of in progress tickets and how they are categorized in the 4 in progress tracks
  - e.g. a junior devs GROOVE is far different than a senior devs GROOVE
    - [you want to keep all of your engineers in their GROOVE](https://computus.org/7-tips-for-programming-in-the-zone/)
- The optimal path around the track for the lowest lap time. In drag racing it is about the center portion of the lane, where the cars can gain traction quicker.
  - `SLOW lane` too many of these and your drivers wont be happy, forecasts wont be accurate, and the _fast_ lane will be over utilized to compensate for poor finishes
  - `THE GROOVE` [the optimal ticket](https://en.wikipedia.org/wiki/Glossary_of_motorsport_terms): your team is successful, drivers are winners, races are predictable
  - `FAST lane` too many of these means all your trophies are gold plated, but hey - you can fill your team with cheap engineers and junior devs
  - `THE LAST LAP` if our users arent using it then its not providing utility, and usually not useful to consider the ticket done, so use the last lap for this usecase
    - there are a lot of stats and insights to glean from plotting tickets on these 4 dimensions over time...
  - `DEPLOYED`: refrain from the use of `DONE` status, DONE doesnt exist in the real world; this also supports the adoption of `refactoring as a lifestyle`

## [ADR-TYPES](https://adr.github.io/)

- for tracking architectural decision records of a particular type
- architecture is key to turning tech-debt into tech-features
- TODO
- complexity of [scale and scope](https://econproph.com/2019/05/20/scale-and-scope/)
  - complexity of implementation (i.e. normal story points)
    - just because a ticket has a high story point, doesnt mean it takes a long time to complete
  - complexiity of completion (a time dimension)
    - just because a ticket takes a long time to complete, doesnt mean its developmentally complex
  - complex solutions dont always require complex deployments, and straight forward requirements can be a pain in the ass
  - understanding the scale and scope of product reqiurements, and the scale and scope to which a developed product satisfies a customers needs, provides the two unanswerable questions in development: how difficult is this to build, and how long will it take to build it
- the RACE
  - each lane (slow, groove, fast, last lap) is the sum of implementation & completion complexity based on an individual/teams capabilities

## RACE Teams

> ![NIRVai raceteam structure](./images/racexp-raceteam.png)

### Research Team

- the most creative
- Visionaries, fearless, just dgaf

### Product Team

- the most performant
- can build anything... fast

### Fire Team

- the most knowledgeable
- the team part of every other team, can do anyones job, even yours

## etc

- [managing race teams](https://www.youtube.com/watch?v=c1n-rgqSTyY)
