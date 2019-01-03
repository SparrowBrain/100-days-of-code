# 100 Days Of Code - Log

## Goals
1. Practice TDD using [AdventOfCode](https://adventofcode.com)
2. Practice MWWM
3. Practice Unity

## Log

## TDD (AdventOfCode)
### Day 00: 2018-12-30, Sun

**Today's Progress**: Refactored some poorly written code to allow less granular testing, refactoring.

**Thoughts**: I've written some poor code, now it's difficult write something more functional. Today's progress felt slow.

**Links to work**
[Day04 Puzzle02](https://github.com/SparrowBrain/adventofcode)

### Day 01: 2018-12-31, Mon

**Today's Progress**: Finished refactoring Day04 tests/code.

**Thoughts**: The refactored code allows smaller methods, easier testing. The decision to consider the whole puzzle as a unit of work and the decision to inject same input into any part of the system is paying off, since it allows keeping the same input format for testing different components thus increasing work velocity, reliability.

**Links to work**
[Day04 Puzzle02](https://github.com/SparrowBrain/adventofcode)

### Day 02: 2019-01-01, Tue

**Today's Progress**: Solved Day05 Puzzle01. Started working on Puzzle02.

**Thoughts**: While working on 01, had a hunch that some refactoring might be needed (extracting polymer units into an actual class, which would help with filtering, etc.). Not following a hunch proved to be ok, since 01 was easy to solve. 02 threw a wrench into the wheels - I now see, that my previous idea of passing input reader everywhere while is quite easy for writing tests, doesn't allow for code flexibility when new requirements arrive (I cannot reuse code as easily as I wish). Need to find some happy middle ground between abstraction and configuration.

**Links to work**
[Day05 Puzzle01](https://github.com/SparrowBrain/adventofcode)

### Day 03: 2019-01-02, Wed

**Today's Progress**: Added Unit type for polymer units, solved the 0502 puzzle.

**Thoughts**: Adding the new type was not to difficult. Changing tests wasn't that painful. In some way it makes sense to delay such work until it is needed. Then again, maybe my unit tests are no longer real unit tests, since they run Unit factory method.

**Links to work**
[Day05 Puzzle02](https://github.com/SparrowBrain/adventofcode)

### Day 04: 2019-01-03, Thur

**Today's Progress**: Started on the 0601 puzzle. Haven't done much.

**Thoughts**: I think I'm leaning towards simple parsing within unit tests.

**Links to work**
[Day06 Puzzle01](https://github.com/SparrowBrain/adventofcode)

## Template
### Day 00: 2019-01-01, Mon

**Today's Progress**: xxx

**Thoughts**: xxx

**Links to work**
xxx

