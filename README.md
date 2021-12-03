# Power to the People
## Direct Democracy Re-imagined

Democracy, as it has been implemented so far, has been subject to several logistical constraints which got baked into the very design of the government. Centuries later, the world has changed drastically, but we are still saddled with this archaic system of government that is massively ineffective, however well-intentioned. Until now, it was not practical to gather and aggregate the opinions of every citizen on every issue before the government. Hence, there was a need to elect representatives. In the Internet age, however, we can have richly expressive input from individual citizens, and the need for politicians is greatly reduced.

The problems that stem from keeping an out-of-date system of government are many.

1. Government functions with the Consent of the Governed. Power is taken out of the hands of the people and concentrated in the hands of a few elected officials, entrusted to make the best decisions for all. It's apparent, however, that too many of our elected representatives do not act with the public's best interests in mind. Whether or not they're dishonest, or incompetent, is another question altogether.

2. Money influences and corrupts a representative democracy. The more money you have, the more your opinion affects the government's actions, which in turn, makes you even richer. Money concentrates itself in the hands of a few people.

3. The consent of the governed, is manufactured by Big Money. Influence over government is ideally 1 vote / citizen. However, due to money's excessive influence on government, what we have is more like 1 vote / dollar.

What we are left with is a travesty of democracy; a flawed republic, more like a plutocratic oligarchy than a democracy; a TV spectacle of competition between two teams; fodder for political junkies; distraction for the masses.

Our government has gathered much wonky junk ( e.g., gerrymandering, filibustering ), which serves as political theater.

We, the people, demand a system of government that works for all of us, and not just a few. It is time to reassess everything, systematically and thoroughly. It's time to apply some assertions and sanity checks to the system, to make sure it passes muster. It's time for a reckoning.

# Proposed Solution

The proposed solution is a system of government, where every citizen has equal influence on the government. Every adult citizen is president, all the time. Elections are not held periodically. Instead, people can specify their choices any time using a software application, 24x7 over the Internet.

This system could start out more like a "Fantasy Government" game app than a branch of government.

There should be checks and balances to prevent mob rule. For example, if enough people voted to lynch someone unpopular, then the other branches of government would enforce the individual's rights and prevent that.

The "co-decide" system lets citizens express their opinions with a high degree of specificity. 


## Design Goals
The new system must meet these criteria:
1. Ensure that every citizen of voting age has an equal amount of influence over the actions of the government.
2. Be reasonably secure.
3. Be auditable.
4. Protect voter privacy by letting voters choose if and how their data should be shared.


## Implementation

The proposed solution would function thus:

1. Each **voter** will be granted an equal number of **points**. e.g., say 1 million points per voter.

2. Each voter will be able to create **proposals**.

3. Each voter will be able to vote for/against each proposal, by **allocating** their points for/against the proposal.

4. The system will total the for/against allocations for each proposal. This score will determine whether or not the proposal will be implemented.

5. Each voter would be able to **delegate** some ( or all ) of their points to another voter to allocate to a proposal. This delegation is especially important because no voter has enough time or knowledge at their disposal to be able to make good decisions on all proposals before the government.

    5.1 **Example 1:** Delegating a specific allocation to a single expert. You could say, "This proposal is tagged **"security"**. Delegate 10,000 points, on this proposal, to [Bruce Schneier](https://www.schneier.com), whom I consider a security expert."

    5.2  **Example 2:** Delegating a specific allocation to a panel of experts. You could say, "This proposal is tagged **"security"**. Delegate 10,000 points, on this proposal. 10% to [Bruce Schneier](https://www.schneier.com) , and 20% to  [Matt Blaze](https://www.mattblaze.org/) , and 70% to [Brianna Wu](https://twitter.com/BriannaWu)."

    5.3 **Example 3:** "Make my vote the same as Joe Smith's, except take all the points he allocated to **"defense"**, and reallocate them to Healthcare ( 70% ) and Education ( 30% )".






### Implementation Notes:

### Approach #1: Use git under the hood
Each voter checks out a git repository, containing a file called **my_vote.xml**
The voter can make this repository private or public.
The voter edits this file to allocate points as they would like, and pushes it up to a government source.
One voter may use a **my_vote.xml** from any source they like, including other voters, if the other voters have published their vote. All of these operations ( git clone, git merge, git pull, git diff, git commit, git push ) happen under the hood. The web application will facilitate these operations, with a slick UI. A tree of pie charts, where each node is a pie chart, and each sector of the pie chart splits and becomes another smaller pie chart.


## Critique

### Pros:

1. **Power to the People:** This system gives political power back to the people.

2. **Fewer politicians:**  This system will result in fewer politicians, and thus fewer points of failure.

3. **Backwards compatible:** This system can grandfather the way the system worked in 2020. You could say, "Make my vote exactly the same as the one published by the Republican Party." This would be the equivalent of casting a ballot for the GOP. Your vote would remain the same until you edit it again. That is, all your 1 million points will be delegated to the GOP, until further notice from you.

### Cons:

There are several hard problems that I haven't addressed here. I invite you, dear reader, to provide your insights on these issues.

- The system is agnostic to the actual merit of the proposal. This means that celebrities without any expertise could gather more points delegated to them than actual experts in the field. We don't discern merit from popularity, which could be a pitfall. On the other hand, we trust the people.

- Can the system be hacked? ( Information Security )
In other words, how to secure authentication. There's no authorization. Everyone has equal access to the system. The entire process will be as transparent as possible.

- How can we expect the average citizen to manage their private key? Will every voter be issued a smartcard/Trezor type device?

- Is mandatory 2FA too draconian or just right?

- Can the system be gamed? For example, by using perverse incentives, or tactics like astroturfing? ( Game Theory, Mass Psychology )



## Thanks & Acknowledgements:

1. [We the People, and the Republic we must reclaim](https://youtu.be/mw2z9lV3W1g) - Lawrence Lessig speaks about what is wrong with the government.

2. [RALLY.org](https://rally.org/onlinegovernment) - cogent video with ideas about online government.

3. [Cory Doctorow](https://en.wikipedia.org/wiki/Cory_Doctorow), for introducing the concept of "Whuffie" ( a social currency ).

![guillotine.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1637309778869/FbS-JYxG1.png)
