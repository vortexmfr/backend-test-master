# Backend Tech Test

Hello candidate!!

## Mars Rover refactoring kata

We need to improve the existing solution that translates commands sent from Earth to instructions that are understood by our Rover on Mars

Currently, the code is very complicated and tangled, so we'd like you to invest some time to clean it up

### Functional requirements
```
Given:
 - a two dimensional map of Mars
 - the initial starting point and direction of the Rover
 
When:
 - a command is received
   move `forward` or `backward` or rotate `left` or `right` (90 degrees)

Then:
 - move the Rover
   if the Rover disappears over the edge of the map (the horizon), continue on the other side (remember, Mars is a sphere)
```

#### Bonus point

After ensuring that the functional requirements have been met, as a bonus point (not necessary but more than welcome), add a new feature:
```
Given:
 - a list of obstacles with their exact location
 
When:
 - Rover moves

And:
 - Rover encounters an obstacle

Then:
 - report back the obstacle. The Rover should stay in its previous position
```

## Your solution

### Must (These points are mandatory)

- Fulfill the [Functional Requirements](#functional-requirements) stated in this readme.
- Refactor the provided code, creating new classes, methods or whatever needed.
- Use any JVM language but, if you want to use one other than Java, please convert the initial codebase to that language.
- Be testable. This means that we should not need to run the main app in order to check that everything is working.
- Be self compiled.
- Be self executable.
- Have a SOLUTION.md containing all the relevant features of your provided solution.

### Should (Nice to have)

- Fulfill the [Bonus point](#bonus-point) section of this readme.
- Be bug free.
- Use any design patterns you know and feel that help solve this problem.
- Be extensible to allow the introduction of new features in an easy way.
- Use any package dependency mechanism.

## Our evaluation

- We will focus on your design and on your own code over the usage of frameworks and libraries
- We will also take into account the evolution of your solution, not just the delivered code
- We will evolve your solution with feasible features and evaluate how complex it is to implement them

Thanks & good luck!!
