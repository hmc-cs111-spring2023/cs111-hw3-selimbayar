# Free project 1

## The user and a language

This section describes who the project would serve and why a language might be a
good way to meet their needs.

I am not sure if this would be supported in this class, but this language would serve people who are new to sports betting and have trouble understanding how everything works. A language might be useful because sometimes writing out what you want to bet on can be easier than actually finding it if you are new to the subject, as some terms and concepts can be very hard to understand.

### What's the need?

_What need is met by your idea? Who are you helping? What is that person's
experience like now? What would their experience be like if you could help
them?_

The need that is met by this language is to help ease sports betting for everyone. It is mostly to help users who are newer, but also it helps everyone that is into sports betting. Sports betting can be extremely confusing for new users with concepts such as parlays, moneyline (ML), handicap, over/under, and a lot more. So, the experience now can be as easy as typing, "I want 'Team X' to win tonight by more than ... goals/points" and the language would create that bet for the user. As someone who is into betting, it can be difficult to find exactly what you want, or understand the payouts. So, this language would completely remove the confusion and make it easier. 

### Why a language?

_Why is a DSL appropriate for your user(s)? How does it address the need?_

A DSL is appropriate because, talking from experience, when someone wants to bet on a particular pick in a particular game, it can be a challenge to find the game throughout the thousands of games, and find the particular bet from the many there is in that game. So, a DSL would make that process much easier as the user can just type something like "Team X to win against Team Y" and it would be done, rather than finding it one by one.

### Why you?

_What excites you about this idea? How did you come up with it?_

It excites me a lot because I am also someone who is interested in betting and do bet a lot. I feel like it brings an extra excitement to sit in front of a TV and watch any game. So, I was thinking on what I could improve in the area of sports betting, and I thought this was a problem that needs a solution.

### Domain

_Describe the project's domain in five words._

Facilitating and typing sports betting

### Interface (syntax)

_How might the user interact with the language? What does programming look
like? Why is this the right way to interact with the problem domain?_

The user might get asked by the language on what game he would like to bet on, and then what type of bet in the game. The programming behind that would find the game and the bet the user wants, and it to his bet slip. I believe this is the right way to interact with the problem domain because it is much more direct as the user knows what he wants, and can easily create his bets from here without making a mistake.

### Operation (semantics)

_What might happen when a program runs? How does a program interact with the
user? What kinds of errors might occur, and how might they be communicated to
the user?_

The program can interact with the user in a way of question and answer. When the program runs, it will ask which game and what type of bet the user wants to bet on. It will then add that bet to the user's bet slip, and ask if he wants to add more games. In the end, the program will display the total odds of the bet slip, which will show how much the total payout is when a certain amount is placed.

There are a few errors that can occur. One is that if the match the user wants to bet on does not exist in the system, the program might display an error message saying that game is not in the system, and would ask the user to pick a new game. Another error is if the type of bet does not exist. Obviously, not everything can be bet on. For example, if the user wants to bet on something like "Player X from Team Y will have his hair combed to the right", I am almost certain that would not be in the system, so the program would ask again until a valid bet is given. 

### Expressiveness

_What should be easy to do in this language? What should be possible, but
difficult? What should be impossible or very difficult?_

Making a sports bet should be easy in this language. If anyone is using this language, they should avoid the confusing numbers and terms of any betting site, and use the language to create the bet. Combining matches from different sports in the same bet should be difficult, but possible. Creating illegal bets (i.e choosing both teams to win the same game) should be impossible.

### Related work

_Are there any other DSLs in this domain? If not, describe how you know there
aren't and conjecture why not. If so, describe them and provide links. How well
do they address the need? Are there any particularly admirable qualities of the
language? Are there parts of the language you think could be improved?_

I don't think there are any other DSLs in this domain, because bettings are mostly in websites/apps where you have to visually choose what you want from the thousands of options, instead of typing out what you want. I am not sure about it, but I doubt there are any other DSLs like this one.  

## The Project

This section examines whether the idea makes for a good CS 111 project.

I honestly don't think this makes a good CS 111 project because it promotes gambling, but I wanted to write it as one of my ideas because I am very into this domain.

### Suitability

_If someone were to work on this project, what percentage of their time would be
spent directly engaging in the **language** aspects of this project (e.g.,
making language design decisions), as opposed to "systems" aspects of the
project (e.g., implementing a complicated semantics that doesn't require a lot
of language design)?_

Their time would be spent more on the systems aspects of the project, maybe with a 75% to 25% compared to the language aspects, because the project has to primarily focus on working fully functional and in the best way to help the user, rather than the design of the language.

### Scope

_How big an idea is this? How ambitious is this project?_

I believe it is a big idea, because I still know people who use "bookies" to do sports betting because they do not fully understand all the concepts and terms. It is very ambitious as well because it would take an extreme amount of work to perfectly capture the user's requests and turn them into actual bets.

### Benefits and drawbacks

_Why might this be a good idea for a project? Why might this not be a good idea
project?_

This can be a good idea for a project because it would help so many people in the area of sports betting, even me by saving time and effort when creating my bets. However, this might not be a good idea because it promotes gambling, and I am not sure if people would want that in a CS class.
