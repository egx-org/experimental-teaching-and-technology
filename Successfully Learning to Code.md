# Successfully Learning to Code

This is a list of observations about things that enable or inhibit learning of computer science for people with no prior exposure, applicable to all ages.

Current status: **DRAFT**

## License

This work is licensed under the [Creative Commons Attribution-ShareAlike 4.0 International License](LICENSE). If you have any questions, visit http://creativecommons.org/licenses/by-sa/4.0/ or send a letter to Creative Commons, PO Box 1866, Mountain View, CA 94042, USA.

## Preparation and Mindset

Programming is a massively wide and deep field with lifetimes worth of knowledge in numerous sub fields. It's far too easy to get intimidated and give up early. This can be avoided or minimized by getting learners into the correct mindset before embarking on this journey.

### Have a project

* Programming is non-linear. Learners need to realize that at some times they will get a lot done in a very small amount of time. Other times almost nothing will get done for days or weeks.
* Solving a real problem that you want to see solved will keep you going when you "hit a wall" and might otherwise give up.
* Don't compare yourself to others. You will always be better than some people and worse than others. These roles can reverse task to task, hour to hour. This is exactly why you want a team with diverse backgrounds, interests, and talents so that when one gets stuck, the others can pull them forward.
* Learn how to get unstuck. Find people you can ask for help, ideally more experienced, though sometimes just explaining the problem to someone (even a younger sibling) is enough to get you unstuck. See also "rubber duck programming".

### Language choice

* Don't get "married" to a single language. Each language has a different reason for existing. If you match that reason to the problem you are trying to solve, life will be good.
* Browse languages, libraries and frameworks. Get yourself familiar with the options you have.
* Learn how to evaluate your options effectively. Spend a little time getting an overview of each. Make a list of the more interesting/promising ones and then do a bit deeper dive on the top 3-5 of those.
* Understand the differences between different technologies and techniques. Critically, understand the limitations, weaknesses and drawbacks and how they relate to the problem you are trying to solve.
* Choose technologies that "fail fast". It's better to catch errors as early as possible e.g. type errors caught by the compiler take far less overall time to fix than runtime errors.
* Trust your instincts. Use the languages and tools in which you are most productive.

### Tooling

* It's important to choose good tooling i.e. text editor, shell, compiler, version control, linter, static and dynamic analyzers, debuggers, keyboard, OS, etc.
* Being "hardcore" is stupid. We built computers to make human lives easier. If the computer or program is getting in your way, toss it. You don't get "extra points" for fighting a non-featured editor like MS Notepad, choose tools that help you get things done faster.

### Collaboration is critical

* Learn how to collaborate, explain and share. Hardly any useful, non-trivial, real-world systems were built by a single individual.
* Use modern version control (Git, Pijul, Mercurial, etc.).
* Pair and mob programming are good ways to keep people from getting stuck.
* Use realtime collaborative editors when doing pair or mob programming remotely.
* Use linters to enforce consistent coding styles on a per-project basis.

### Be willing to make mistakes

* Early learners are worried about "breaking the computer". It's very, very hard to permanently damage a computer with software alone. If you have someone that can do this, they likely have phenomenal talent.
* Start learners with cheap hardware, or hardware that can be easily replaced if it does get broken.
* Stick to open hardware and software so people can take it apart to learn from it.
* Use explorable and visualizable systems. If learners can see what is going on, they can understand in faster.

### Learn where to put the blame

* Did you do something wrong? Far too many beginning learners are quick to blame themself when they run into problems. Many times the problem is actually due to:
	* a bug
	* a limitation of the system
	* a bad/confusing interface or error message
	* a poorly chosen analogy
	* confusing behavior of the system in edge cases
* Is the computer failing to do something it reasonably should?
* How do you tell the difference?

### Learn how to generalize problems

* When you write a story or article, you are writing a single "path" or about a single timeline.
* When writing a program we are solving as many incarnations of this problem as possible. This is why programs are configurable, because they may have different use cases or different users. They need to work for all of them.

## Process

### First, learn how to understand a problem

* If you don't understand the problem, there's no way you can write a program to solve it.
* Make sure you understand the full problem, not just a single instance of it.
* Understand the failure modes of the problem. Writing software for one path is easy, writing robust software for all cases is not.
* Try to thoroughly understand how people will use the software you intend to write.

### Start with unplugged learning

* Minimize unnecessary errors like syntax errors.
* Choose languages that give good and detailed error messages.
* Give users some early wins to build confidence.
* Make sure that learners understand that learning difficulty in programming is logarithmic i.e. it feels impossibly difficult when you first start, but once you gain a certain amount of knowledge it starts to get much easier, much faster.

### Continue with high-level languages

* It's hard enough to learn the general computer science concepts, language specifics, and how the lower levels of the stack down to the hardware
* Learn the basics first i.e. variables, mutability, conditionals, control flow, grouping code via subroutines and classes.

### Learn how to read docs

* Where are the docs for your language or tool?
* Official vs. "unofficial". Sometimes the "unofficial" docs are easier to navigate.
* How are the docs organized?
* Supplemental docs: books, videos, courses

### What are the different techniques to solve a problem

* Can we solve this without code?
* Can we do a pure mathematical equation?
* What type of language is best for this problem: concurrency, logic, fuzzy/probabilistic?

## Next Steps and Career Path

### Get involved in the community

* Attend meetings and conferences, virtually or in person.
* Find groups is the various textual communication channels for a given community or technology e.g. forums, IRC, Slack, Discord, etc.
* Share your knowledge and start giving talks before you think you are ready. It doesn't have to be a 2 hour deep-dive, do a 5 minute lightning talk on something neat that you just learned.
* Share confusing stuff so that you can help others move faster by not getting stuck.

### Build your CV

* Make software that addresses real problems that you, your friends, family and colleagues have
* Choose problems that are big enough to be useful, but small enough to get done in a reasonable amount of time (weeks to a few months at most)
* Early on, choose problems that are non-critical so that if you really get stuck and can't finish the project, it doesn't cause any major problems. (Internship project rules)
* Set expectations about how long this will take and what you are capable of doing
* Find open source projects that you use and like. Find bugs that you can fix and help make the software you care about better.

## Responsibilities and Impact

As learners gain confidence, it is important that they start to understand their responsibility to humanity. There are few other fields where one individual can have as far reaching impact as in programming. While this can be amazingly beneficial to humanity, poorly made code can and has taken lives.

When to make programmers aware of this responsibility must be carefully considered. Too early and promising talent might leave the field. However we must ensure that this responsibility is understood and internalized before people take jobs working on critical systems with potentially global reach.

Further, it's important to understand that "critical systems" is now a much broader category than military, medical, automotive and aerospace systems. Things as seemingly innocuous as advertising platforms, social media, and IoT (Internet of Things) have already had deadly global consequences.

### How does this make life better for other humans

* Programming was invented to save humans time. Does your program save people time?
* Is there anywhere your program wastes people's time. How can that be reduced?
* Make programs that can be composed to solve bigger problems when combined with other software.

### Understand your responsibility

* Programming should be considered engineering. Building robust, secure, and maintainable code is critical.
* Doomsday machines: this can cost lives
* You can impact the whole world.

### Understand your priorities

1. Make it correct and secure
2. Make it fast
3. Make it easy to use and document it

See also: The Pony philosophy

### Understand the role of robustness and security

* Adversarial thinking (CTA?)
* Connection and damping are important
