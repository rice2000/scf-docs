# How to Vote in the Stellar Community Fund

## First Let’s Login
Let’s talk about how voting works in the Stellar Community Fund. It’s a little fancy but it should be easy and fun once you get the hang of it.

First off all voters must be registered with the voting site via a phone number which can receive SMS messages from the Twilio service.

**_We don’t store raw phone numbers in any database, these numbers are cryptographically hashed as a fingerprint for your account but you keep the finger. Wait… no yeah that analogy works. Right? Security is important, but so is a fair voting environment, with this we aim to achieve both._**

To begin simply “Login“ with your phone number and the code which is sent via SMS to your device.

Once logged in you’ll be ready to vote!

**_Public community voting is only open for a set period of time for each round so ensure it’s the right time for the round you’re attempting to vote in._**

## How to Vote
Voting in the SCF happens via a mechanism we call flaggable quadratic voting or FQV. It’s a system of credit allocation which allows voters to indicate preference intensity.

Community voting in the past has been one-dimensional, and tends towards a linear distribution that makes it impossible to recognize — either positively or negatively — exceptional projects. Quadratic voting adds velocity to votes, which better captures community sentiment and enables the community to police bad actors, thwart manipulation while still rewarding those projects they deem most exceptional.

It may sound complicated but we built a test quadratic voting interface and it's actually pretty intuitive. [Try it out](https://fqv.vercel.app).

Once you’ve got a bit of a grip on what FQV is trying to achieve the actual process for voting is quite straight forward. When you first land on the homepage with all the eligible projects you’re given 100 credits to divvy up amongst the projects as you see fit. As you vote successively on a single project your credits will be spent quadratically. 1 vote = 1 spent credit, 2 votes = 4 credits, and so on and so forth all the way up to a max of, if you only voted on a single project, you could vote 10 times spending all 100 credits. 

But what about the flaggable bit you say? Good question. A flag will cost roughly enough credits that you could conceivably flag 1/3 of the entries before running out of credits. The idea though is to only use the flag to express your concerns that a project may be over or underperforming as a result of foul play. If something seems fishy, give at least one vote up or down and then you can flag. The reason for the flag is so that you don’t need to use all your credits to try and counteract potential bad actors, just throw a single credit and a flag and use the rest of your credits allocating as you please.

