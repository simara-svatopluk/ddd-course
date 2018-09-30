# Language

Language is a communication tool, a tool we use to express ourselves and to understand others.

Let's take a look how do we usually assume communication works:

IMAGE: person's brain communicates with other person's brain via mouths

An optimal scenario is when we express ourselves exactly how do we think and the other one understands our words exactly as they are said.
But this scenario is never true. We all have different experiences, different feelings, different flow of ideas, different assumptions.
Language is also in compare with our thoughts, limited. It doesn't allow us express everything.

So if I want to express something, I ve to use language. But because the language is limited, I have to express a little bit less than I want and also I have to express something a little, a little bit different. This process is called translation. In short, I translate my ideas into language.

The other person understands the language, but as discussed earlier, the other person hears something a little bit different than what was said.
Again, because the person have to translate the language into own ideas.

So, this is what happens when two people communicate in a common language:

IMAGE: a person translates ideas into language, the language is accepted by the other person and translates the language into own ideas

We experiance double translation even with a common language. And as we can imagine, translation means possibility of misunderstanding, a possibility of error.

## Translation problem

When we speak with a foreigner, we have to use a language that we understand both.
Let's say I'm Czech, the foreigner is German and we both sort of speak English.

IMAGE: I have to translate ideas into Czech language, then language into English, the other one have to translate English into German and then language into ideas.

We ended up with four translations! This situation definitelly causes misunderstandings and problems.

We can go back to software sphere. In one team we usually speak by the same national language, but we have different professions, and even we speak by the same language, we imagine something different by the same terms.

I'm a programmer, I use programmers' dialect to describe problems. You would hear something like "server, version controll system, code, system configuration".
A project manager uses his own dialect, something like "goal, bussiness, deadline, meeting". When I speak with the project manager, we face as same problem as Czechs and Germans, we have to agree on a common language, and translate into it our dialects. So again, we end up with four translations during everyday conversation.

## Translation in an application

A typical application nowdays looks like:

IMAGE: User -> UI -> JS -> API -> PHP -> SQL -> PHP -> API -> JS -> UI -> User

Usually the UI is designed by UX/Graphics guy, JS is done by frontend developer, API is designed by agreement between JS guy and PHP guy, PHP is done by backend developer and SQL is managed by a database specialist. When we count the user, we have 5 different people who have different ideas and think flows. We ended up with enormous amount of translations between people and also between system parts. In this kind of project it is almost impossible to not make a misunderstanding nor translation error. This kind of project is always a never ending story of "idiotic users that don't understand the system".

## Ubiquitous language

As we see, the most important problem in communication are translations and misunderstandings.

The solution is to use one language withing the project, all team members and users. A language that comes from the underlaying domain, from domain experts' language.

As we discuss problems with people who really understands the domain, with domain experts. We hear them using terms for domain concepts over and over again. We have to focus on understanding and learning these terms and also focus on using these terms in our standard communication. Once we adapt these terms, we use them in documentation, in speech with different team members, in code while everyone understand them. And suddenly we don't have to translate these terms anymore, because they became ubiquitous. Terms created a small language, the ubiquitous language, and this language became backbone of the project.

Once we use the ubiquitous language, translation count drastically decreses, communication and code become naturally straight forward. And what more - when a new programmer joins our team, there is no need for senior developer to introduce everything. An underlaying domain can be explained by any team member, or user, by using terms of ubiquitous language.

## TL;DR

Ubiquitous language is a subset of domain language used by all team members, domain experts and users. It clears communication between people, interaction between system and users and programmers' work.
