# ScienceThoughts
Mike posts his thoughts on COVID and other science-y topics

# COVID test types:
Effectively, there are 3 kinds of questions we often ask about COVID diagnosis and 3 kinds of tests. 

Question 1) Does someone have COVID virus particles in their body? 

To answer this, we use Nucleic Acid Amplification Tests, also known as PCR tests or RT-PCR tests. These directly target the actual viral sequence of COVID19. These are the most sensitive tests, and the most specific tests--effectively, the most accurate *for detecting whether someone has virus particles in their body*.  However, from the formal name ("amplification"), these tests can take a very very small amount of virus particles and amplify them a ton, including *dead virus pieces that can't infect anyone*. NOTE: these still detect Omicron and all COVID variants because the virus is mostly the same despite the variants. In general, for COVID and many other viruses, you can detect viral particles from various bodily samples for weeks and weeks after infection using PCR tests, long after they recovered fully and can't infect other people. That leads us to:

Question: 2) Does someone have ENOUGH virus particles to likely infect someone else? 

This is a different question than 1)! Infectiousness mostly corresponds to the amount of virus someone has. PCR tests CAN give you a rough quantitative estimate of how many viral particles there were, by looking at just how much amplification you had to do--this is called the Cycle Threshold (Ct)--but most PCR tests are configured to give people a Positive or Negative, without an estimate of how much amplification took place and therefore without an estimate of how MANY viral particles there were. This means that most PCR tests may NOT actually answer the question of infectiousness. 

As it turns out, however, there's another kind of test entirely that does a much better job of answering this question of infectiousness: Rapid Antigen tests. These evaluate a piece of a protein created by the virus. Like PCR tests, this is still sensitive to different variants because again the protein is mostly the same. This is the test a lot of urgent cares in the US use, and are often done at home. They take 15 minutes, and the most common one is BinaxNow, but there several other FDA-approved tests. These are less sensitive to virus particles than the PCR tests, but they're sensitive ENOUGH that they are often positive when someone has enough virus particles to pose a good chance of infecting someone else. That said, as you can imagine, they're not perfect tests--sometimes they're going to be positive when someone ISN'T infectious, and sometimes they're going to be negative when someone IS infectious. Serial rapid tests over days can help address this limitation.

(You might wonder, how do we know the above? The answer is: by correlating positive and negative antigen tests with how many people in a group had a positive PCR at what Cycle Threshold, as well as correlating antigen test results with viral culture testing)

3) Has someone previously been exposed to COVID? 

To answer this, we'd look for antibodies in their blood. AntiBODIES are molecules created by the body's immune system in response to the viral antiGEN (a piece of a protein the virus makes). Antibodies target cells infected with the COVID virus and help destroy them. They're not the only piece of the immune system (we also have T cells which are crucial as well), but they're a really important piece of the body's response to covid. Antibodies are easy to detect and design tests for, which is why you've heard of this test. T cell tests are very difficult to make and design, which is why they exist only as specialized lab tests used very, very rarely. Antibodies take weeks for the body to make, and only hang around in detectable quantities for a few weeks to several months depending on the type of antibody. 

In general, antibody tests aren't very useful clinically. They're therefore uncommon, and your doctor's office won't often use them nor will you find them at CVS. That's for a few reasons: 
1) From the timing of when you can detect antibodies described above, it means that there's a short "window period" when you can expect the test might detect exposure, and lots of time on either end when the test is simply useless. It's often very difficult to know when someone was actually exposed to COVID, so you're never really sure exactly what the relevant window period is. 2) Just because you've had COVID once and developed antibodies to it doesn't mean you can't get it again! Sure, it means you're less likely to get it again (depending on your antibody levels, maybe a LOT less likely), but antibody tests only measure PART of the immune response. 3) There are lots of different kinds of antibodies--IgM, IgG, and different subtypes (neutralizing, binding), just as examples -- so two antibody tests may not be directly comparable, assuming they are even accurate. 

TL;DR:
- PCR tests are great for detecting virus particles, but not necessarily measuring infectiousness
- Rapid Antigen tests are great at detecting infectiousness, because they're just sensitive enough to detect actively replicating virus. They're not perfect, however, and can still miss infectious people--but that's what serial rapid tests over days can help address. 
- Antibody tests are not very useful except in a few situations. 

# Cool, so which test do I use?
I'd argue that this should be driven first by your use-case (personal vs. am I contagious to others?), then by how likely it is you think you actually have COVID (your "pre-test probability")--if the use-case is personal, get a PCR, and if the pre-test probability is high, Examples might be:
Ex1: "I've lost my sense of taste and smell, feel super sick, and mildly short of breath, and I'm wondering if I might need me some of those Regeneron antibody cocktails"-- In this example, the use-case is primarily personal as treatment would differ radically based on a positive vs. negative test. In addition, in this particular example, the pre-test probability of not only infection but also infectiousness is also very high. Thus, the most sensitive test for viral particles--a PCR test--is probably best, as this reduces the chances of a false negative result and maximizes the chance that you would receive appropriate treatment. 

Ex2: "I have a mild sniffle brand new this morning but otherwise feel fine and am about to meet friends later today" -- here, the use-case is primarily determining whether you'd get others sick. If you weren't visiting friends, the result (positive or negative for COVID) wouldn't make a huge difference in your life and the treatment would be the same: rest and feel better. Of note, in this example, the pre-test probability that you have COVID is much lower-->so the difference between a "pretty good test" and "the best test for viral particles" also makes less of a difference. Thus, I'd use a rapid-antigen test. 

Ex3: "I have a known COVID exposure a few days prior, feel fine, but won't see anyone in the next week either way" --> use-case is personal, pre-test probability is moderate. Following the principles above, I'd get a PCR test in this case.

Ex4: "I have a mild sniffle, no known exposures, and I won't see anyone any time soon"-->use-case is personal, but because the pre-test probability is very low, I'd argue for a Rapid Antigen test as it's cheaper and avoids healthcare exposure and a negative test is going to be very reassurring (the "post-test probability" of COVID is very, very low).

