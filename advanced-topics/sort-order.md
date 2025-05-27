---
icon: arrow-down-9-1
---

# Sort order

Most lists of Ideas or Solutions--including search results--use a default search order of either 🔥 _interest_ or  🍬 _sweetness._

## Ideas

### 🔥 Interest

The default sort order for Ideas is 🔥interest. 🔥Interest is the sum of the _shares_ of all positions in an Idea. Shares are the amount contributed multiplied by a linear growth factor (called the _accrual rate_) and the number of cycles since the contribution.

$$
Shares_{position} = contribution * accrualRate * (currentCycle - contributionCycle)
$$

$$
interest = \sum_{i=0}^{numPositions - 1} shares_{position_i}
$$

{% content-ref url="../basics/ideas.md" %}
[ideas.md](../basics/ideas.md)
{% endcontent-ref %}

## Solutions

### 🍬 Sweetness

The default sort order for Solutions is a hidden field called 🍬 _sweetness._ 🍬 Sweetness connotes a good deal for Solution funders. 🍬 Sweetness is calculated by multiplying the current amount staked in the Solution by the funder reward percentage offered by the Solution drafter.

$$
sweetness = funder RewardPercentage * stake
$$





{% content-ref url="../basics/funding-a-solution.md" %}
[funding-a-solution.md](../basics/funding-a-solution.md)
{% endcontent-ref %}

