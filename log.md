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

### Day 05: 2019-01-04, Fri

**Today's Progress**: 0601 field generation done. Next is the filtering out infinite fields.

**Thoughts**: Programming while underslept is rather challenging. Still, some goo progress and some spaghetti. Might refactor later.

**Links to work**
[Day06 Puzzle01](https://github.com/SparrowBrain/adventofcode)

### Day 06: 2019-01-05, Sat

**Today's Progress**: 0601 Done.

**Thoughts**: Had some algorythm issues that my tests didn't catch before the very last task. I feel like adding a bit more abstraction could have helped with this.

**Links to work**
[Day06 Puzzle01](https://github.com/SparrowBrain/adventofcode)

### Day 07: 2019-01-06, Sun

**Today's Progress**: 0602 Done.

**Thoughts**: Really suffered from not having a 'field' abstraction. Advent of Code is getting kind of boring. Searching for a good project to switch to.

**Links to work**
[Day06 Puzzle02](https://github.com/SparrowBrain/adventofcode)

### Day 08: 2019-01-07, Mon

**Today's Progress**: 0701 Done.

**Thoughts**: Todays one was easy. Really clear abstractions, known problem to solve. Unit tests aren't clean, but were easy to write.

**Links to work**
[Day07 Puzzle01](https://github.com/SparrowBrain/adventofcode)

### Day 09: 2019-01-08, Tue

**Today's Progress**: 0702 Partially done.

**Thoughts**: Trying to cut a corner ended up in a spaghetti mess code, that I don't know if works. Unit Tests say it doesn't. TDD is good, after all..

**Links to work**
[Day07 Puzzle02](https://github.com/SparrowBrain/adventofcode)

### Day 10: 2019-01-09, Wed

**Today's Progress**: 0702 done.

**Thoughts**: Adding some abstractions made my life easy. Good tests work.

**Links to work**
[Day07 Puzzle02](https://github.com/SparrowBrain/adventofcode)

### Day 11: 2019-01-10, Thur

**Today's Progress**: I've been yet again captured by an idea to make an animated desktop/lock wallpaper. So instead of doing advent did research on this. After long search online found a prototype that shows promise.

**Thoughts**: Working on something that has grabbed my attention is exhilirating. Want to pursue this idea further.

**Links to work**
Nothing to show for, really.

### Day 12: 2019-01-11, Fri

**Today's Progress**: Started adding tests for player. Took some time setting things up.

**Thoughts**: Have a ton of ideas how to customize various skins for wallpapers. Excited about that. At the same time, working on this way too late - physically hard to learn anything new. And it's a nice project that will allow writting Unit Tests, maybe even some SPecFlow stuff.

**Links to work**
https://github.com/SparrowBrain/BackgroundPlayer

### Day 13: 2019-01-12, Sat

**Today's Progress**: Somewhat finished with player. Started implementing logic for the skin delay/offset calculations.

**Thoughts**: Trying to do minimal and clean unit tests is fun. It's challenging my habits. Hopefully this leads to a cleaner code, and smaller, testable units.

**Links to work**
https://github.com/SparrowBrain/BackgroundPlayer

### Day 14: 2019-01-13, Sun

**Today's Progress**: Started working on offsets.

**Thoughts**: It's taking some time. Hoping better abstractions will pop up

**Links to work**
https://github.com/SparrowBrain/BackgroundPlayer

### Day 15: 2019-01-14, Mon

**Today's Progress**: Finished with month/day offsets, pushed solution to rought completion (skin loading, etc).

**Thoughts**: It works!

**Links to work**
https://github.com/SparrowBrain/BackgroundPlayer

### Day 16: 2019-01-15, Tue

**Today's Progress**: Fixed a couple of issues, covered them with unit tests. Started working on integration tests.

**Thoughts**: It's nice to have a working solution and start improving on various aspects of code instead of coding in the dark and hoping things will work.

**Links to work**
https://github.com/SparrowBrain/BackgroundPlayer

### Day 17: 2019-01-16, Wed

**Today's Progress**: Added setup, teardown to integration test, added dependency injection, fixed a bug with adjusted skin start time being in the future.

**Thoughts**: Today was a blast. Stuff I did made the code better and it as rather easy to do.

**Links to work**
https://github.com/SparrowBrain/BackgroundPlayer

### Day 18: 2019-01-17, Thur

**Today's Progress**: Added a image file validator.

**Thoughts**: Wow, not much done. I think last couple of days might have been slim on sleep - it's rather difficult tomake things tonight.

**Links to work**
https://github.com/SparrowBrain/BackgroundPlayer

### Day 19: 2019-01-18, Fri

**Today's Progress**: Managed to build .NET Core 3.0 preview WPF project.

**Thoughts**: Most of the time was spent reading up and figuring out what was needed to run 3.0 .NET Core. Getting ready to build some UI for my BackgroundPlayer.

**Links to work**
https://github.com/SparrowBrain/BackgroundPlayer

### Day 20: 2019-01-19, Sat

**Today's Progress**: Added Stylet, Made Exit button work, started working on user stories for skin pool/playlists, etc.

**Thoughts**: So codewise, it's not much. But I'm thinking it could also be fun to do some basic user stories, with acceptance criteria and capture the criteria as AcceptanceTests (testing viewModels probably) with SpecFlow. Right now there's a lot of ideas about features this thing could have, and I can see myself starting to work in 50 different directions without any real gain. So scoping it out sounds fun. And practicing SpecFlow.

**Links to work**
https://github.com/SparrowBrain/BackgroundPlayer

### Day 21: 2019-01-20, Sun

**Today's Progress**: Added feature file. Started working on setting up view models.

**Thoughts**: I'm a bit confused on how to apporach injecting stuff into view models right now. Also, my background player app was all async, and Stylet stuff isn't... So I'm going to look into this more.

**Links to work**
https://github.com/SparrowBrain/BackgroundPlayer

### Day 22: 2019-01-21, Mon

**Today's Progress**: Added skin name. Working on WPF.

**Thoughts**: I think I need more sleep.

**Links to work**
https://github.com/SparrowBrain/BackgroundPlayer
