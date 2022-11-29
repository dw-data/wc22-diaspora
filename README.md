# World Cup Diaspora

In this repository, you can find the methodology and source code that supports DW's [story](#) on the disconnection between World Cup players and their local football clubs and leagues.

**Idea, research, analysis, visualization:** [Rodrigo Menegat Schuinski](https://twitter.com/RodrigoMenegat).

## Data sources

Player information and transfer data was collected from the German specialized website [Transfermarkt](https://www.transfermarkt.com/). Data was collected on November 14th, when all the squad lists were first published. It wasn't updated afterwards, so the analysis includes players that were eventually cut out of their teams due to injury, such as France's Benzema and Senegal's Mané.

## Methodology

The story relies mostly on the transfer information for each player which was published in Transfermarkt. There are some caveats, though.

In order to determine the share of the career a player spent in home country clubs, we looked at how many days he spent under contract for local clubs since he turned 16 – an arbitrary age, since we don't know exactly when each player career started. 

However, it's very unlikely that I player has started his professional activities before this age. Just as an example, the youngest player to ever feature in a World Cup nas Norman Whiteside, from Northen Ireland, who appeared at the 1982 World Cup when he was 17.

Since starting a professional career so young is unlikely, this decision will probably **overestimate** the ammount of time a player spent in his home country. Even if he's under contract at 16, he's probably part of a youth team at this point.

Alternatively, in order to determine in which age a player first left the country, we look at the first time he signed a contract for a foreign team. This may lead to some counterintuitive situations.

For instance, Lionel Messi left Barcelona at age 13, after playing for some years at Argentinean Newell's Old Boys youth squads. However, since he never spent a single day under contract for a local team after 16, we'll consider he spent his whole career abroad.

Similarly, we consider that Germany's Jamal Musiala first left the country at age 7, when he was playing for the youth academy of English club Southhampton. However, we went back to his country before turning 16 and never played for a foreign club afterwards – so we consider he spent 100% of his career at home, despite having left the country for the first time young.

Those edge cases, however, are rare, and don't have a significant impact in our findings.

## Interview partners

I'd like to thank our interview partners for the story. Not all of them were featured in the final text, but they were all tremendously helpful.

- Gerard Akindes, Hamad Bin Khalifa University
- Wycliffe Njororai, University of Texas at Tyler
- Rodrigo Koch, State University of Rio Grande do Sul
- Sebastian Chitaddini, journalist, writer and an Uruguayan national team (or, as he would prefer it, La Celeste) fanatic.