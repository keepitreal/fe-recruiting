# StarsDraft Front End Recruiting Challenge

To continue with the StarsDraft recruitment process, we'd like to see an example
of how you approach, spec/design, and implement an application feature. Please read
the feature description and then follow the directions below.

## Feature Description
StarsDraft wants its users to be able to create lineups of athletes that they can enter
into an NFL fantasy contest. A lineup is a list of unique athletes that contains one athlete per position
type. An NFL lineup for this contest has the following positions: 
- Quarterback (QB)
- Runningback (RB)
- Wide Receiver (WR)
- Tied End (TE)
- Flex (selected athlete can be a RB, WR, or TE)

### Feature 1

To build a lineup, the user should be able to select a player from a list of available athletes. Selecting
a player adds that player to the user's lineup and removes it from the list of available athletes.

### Feature 2

Each lineup has a "salary cap", which is the max amount that can be spent on athlete "salaries". For this
NFL contest, the salary cap is $50,000. Each athlete has a salary that, when they are added to a lineup,
deducts from that lineup's salary cap.

Perhaps an example will help. With no athletes selected you have $50,000 available in your
"salary cap" to spend on athletes. You make your first selection: Antonio Brown (WR), who has a salary of $18,000. Now you
have $32,000 left in your salary cap to spend on the remaining positions you have to fill.

If a player exceed the salary cap, then they should receive a warning that their lineup is
over the salary cap, and they'll need to replace one or more athletes with cheaper athletes.

### Directions

1. First, fork this repository. This repository has a JSON file that has all of the data you'll need to create
your feature.
2. We want to see a minimal specification added to `SPEC.md`. 
3. Please use Vue as your view library. We use Vue at StarsDraft and would like
to see how you approach this problem using it.
4. All other library, build tools, compile-to-js language choices are up to you.
5. Please overwrite this `README.md` with instructions on how to run your app.
6. When you're done, please email us a link to your forked repository.