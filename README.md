# sf-tri-city-restaurants

This is a personal project that I started on 4/12/2023.

Each day, my dad and I constantly struggle with deciding *what* to eat for dinner. Having come from SoCal, the food up North, in our humble opinion, is just barely *edible*. So we constantly struggle with decision paralysis when trying to decide where to eat. This particuarly became an issue during mid-Feb to mid-April as my mom, the main decision maker, was living out her life in Taiwan/Japan.

So we often resorted to opening up Yelp and reading through each restaurant until we found that one establishment that just happened to appeal to our already-degraded tastebuds. But many times, we just kind of give up and end up eating classic fast food. Yeah, they suck, but sometimes, you just *crave* that suckiness.

But within these two months of scrolling through Yelp pages, I've come to notice that classic, or should I say commonly *franchised* fast food restaurants have ***atrociously*** low ratings on Yelp. Not just one, but literally ALL of them. Just take a look at the [McDonald's near my area](https://www.yelp.com/search?find_desc=mcdonalds&find_loc=Newark%2C+CA+94560); an average of **two** stars. Yes McDonald's is probably one of the lower tier fast food restaurants, but I don't recall them tasting THIS bad when I lived in Southern California. Maybe because I was younger then or my taste buds weren't as developed. Regardless, it made me come up with the following question:

Are the ratings of commonly franchised fast food restaurnts in the Bay Area Tri-Cities an accurate representation of their customers' sentiments, as in does their food *really* suck? Does their service *really* suck?

But what are commonly franchised fast food restaurants? And what does it mean to be an *accurate representation of customer sentiment*? Unfortunately I do not think there is a right answer to these questions, so for the purpose of this project, I will define them as follows:

Commonly franchised fast food restaurants will be defined by the following list:

`["Burger King", "Carl's Jr", "Chick-fil-A",  "Chipotle Mexican Grill", "McDonald's",
                 "Firehouse Subs", "Five Guys", "Jack in the Box", "KFC", "Panda Express",
                 "Papa Johns Pizza", "Popeyes Louisiana Kitchen", "Subway", "Taco Bell",
                 "Wendy's", "Wienerschnitzel", "Wingstop"]`

This list is by no means exhaustive, but I think it is exhaustive enough to catch most if not all of the commonly franchsed fast food restaurants in the Tri-City area. 

As for being an accurate representation of ther customers' sentiments, I'm sure this question, if people really wanted to get into it can become quite a debate. But for my purposes, I'm just going to give ratings the benefit of the doubt, if your rating is low, your food is horrible and your service sucks; rating high, then the opposite is true.

With these definitions, I propose an A/B test with an $alpha=0.05$. The following are my hypotheses:

**Null Hypothesis:** In the Bay Area Tri-City area, the distribution of ratings is the same for regular restaurants and commonly franchised fast food restaurants. The difference in the sample is due to chance.

**Alternative Hypothesis:** In the Bay Area Tri-City area, the commonly franchised fast food restaurants have a *lower* rating, on average, than regular restaurants.

With all that said, let's see where this project takes me.

Final results and conclusions can be found in `analysis.ipynb`.