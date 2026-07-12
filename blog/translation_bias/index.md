---
layout: projects
---

# Same Bias, Different Treatment: Gender Stereotypes in Machine Translation for Indian Languages

Advances in language modeling have significantly impacted machine translation capabilities, improving both the quality and accessibility of translation services across hundreds of languages. Yet, frustratingly, gender biases in translation continue to be a seemingly unsolved and underattended problem.

What has been known for a while now is that [translation services frequently introduce gender stereotypes](https://www.cell.com/patterns/fulltext/S2666-3899(25)00105-9) through their choice of pronouns, verb forms, and noun inflections. This is true across language families, translation directions, and model architectures, from early statistical systems to today's large neural models. Translation services seem to strongly favor a "traditional persona"; to them, doctors are men by default, nurses women, engineers are masculine, and secretaries are feminine. 

While gender bias in translation is somewhat well-known, I thought of writing about some of the examples I have been seeing of this phenomeon with Indian languages. And let me start by acknowledging the wonderful research that many have already done on gender bias in Indian language tech; see [this paper](https://dl.acm.org/doi/abs/10.1145/3600211.3604672), [this one](https://link.springer.com/article/10.1007/s00521-019-04144-6), and [this one too](https://dl.acm.org/doi/abs/10.1145/3630106.3659017). My goal with writing this note is to simply document some of the more curious examples of translation biases I have been coming across with Indian languages and, in doing so, maybe complement the research in this space.

### Gender Stereotypes in Translation from Indian Languages

The first time I encountered an example of this was around 2017. A Turkish friend showed me a viral tweet where someone translated “She is a doctor” to Turkish and then back to English and got back “He is a doctor” (Tommy Shaffer Shane documents the fallout [here](https://aitrouble.wordpress.com/2022/08/16/situation-2-gender-bias-on-google-translate/)). With the tweet going viral, my friend and I (as I am sure all others who encountered the tweet) tried out own examples to find the “neat” pattern that Google Translate consistently associated produced pronouns that were stereotypically associated with the corresponding occupations. And unsurprisingly, there were many such examples for translation from/to Indian languages.

Another interesting thing happened as a result of the tweet going viral was the response from Google. Acknowledging the complex social nature of the exhibited biases and the role that translation plays in propagating these biases across cultural contexts, Google Translate laid out a [research agenda](https://research.google/blog/a-scalable-approach-to-reducing-gender-bias-in-google-translate/) to fix the problem. The very visible result of this investment is that we now see gender-neutral translations when translating from Turkish to English. Yay right?

Sadly, that’s only part of the story. The supposed technical progress resulting from this research did not “translate” (sorry) to other gender-neutral languages like Bengali, like the example below shows.

![BE_to_EN_example](https://raw.githubusercontent.com/vijaykeswani/vijaykeswani.github.io/refs/heads/master/blog/examples/be_en_example1.png)

In fact, we can find similar examples of gender biases in translation for many Indian languages. Here's an example for English -> Kannada -> English.

![KN_to_EN_example](https://raw.githubusercontent.com/vijaykeswani/vijaykeswani.github.io/refs/heads/master/blog/examples/kn_en_example1.png)

And another for English -> Urdu -> English.

![UD_to_EN_example](https://raw.githubusercontent.com/vijaykeswani/vijaykeswani.github.io/refs/heads/master/blog/examples/ud_en_example1.png)


### Is this a problem with gender-neutral Indian languages only?

It was initially suggested that this problem is specific to translation between gender-neutral and gender-specific languages. After all that’s where there is missing context in translation that these automated tools choose to fill with syereortpical information right? 

However, even from the simple examples above, the problem of gender bias in translation appear much more pervasive and complex, and extends generally to other “technologically under-represented” languages (this category overlaps with “low resource” languages, but that term is vague and seems to only represent the resources of those who hold the power of making models). 

Let me show more examples of cases where even translating from gender-specific languages to English introduces gender stereotypes. Here's one for English -> Tamil -> English.

![TN_to_EN_example](https://raw.githubusercontent.com/vijaykeswani/vijaykeswani.github.io/refs/heads/master/blog/examples/tn_en_example1.png)

And another for English -> Marathi -> English.

![MR_to_EN_example](https://raw.githubusercontent.com/vijaykeswani/vijaykeswani.github.io/refs/heads/master/blog/examples/mr_en_example1.png)

So the technical issues don’t seem limited to gender-neutral languages. Wherever the translation AI has to infer context in these examples, it seems to prioritize the gender-stereotypical context. And this missing context doesn’t just to have related the structure of the language itself, as in the case of languages that don’t gendered pronouns like Bengali and Turkish. This missing context could reflect lack of data or modeling structures that are better curated for English than other languages. In either case, the problem underlying the introduction of gender stereotypes seems more complex than thought before (at least by me).


And, by the way, this is not just an issue with Google Translate. Bhashini, which promises to improves language modeling capabilities for Indian languages, reproduces the gender biases shown in most examples presented above. 

![Bh_example](https://raw.githubusercontent.com/vijaykeswani/vijaykeswani.github.io/refs/heads/master/blog/examples/bhashini_example1.png)


### Also this is not just a technical problem

There is visibility meta-bias to this issue; fixes get prioritised for languages whose speakers have the loudest voices in spaces that technology companies pay attention to. Google Translate was quick to address gender bias for many European languages following the viral tweet. Yet the very same examples of gender bias continue to exist for Indian languages. Interestingly, we are seeing another reproduction of what this visibility bias.

The same dynamic is playing out again with Google's recently introduced "Show Alternatives" feature (probably [Gemini powered](https://www.androidauthority.com/translate-show-alternatives-3632048/)) which shows gender-neutral translation options for Hindi, but is absent for all other Indian languages. I am sure considerations associated with costs of running LLMs to produce these alternatives is probably a concern here. But still the prioritization of some languages over others for this feature seems strange. 
Language has always been entangled with power, [as is language tech](https://aclanthology.org/2020.acl-main.485/). At a time when this entanglement is more contested than ever, disparate treatment in access to language tech only deepens existing divides. 

I have created a tool for people to play around with similar examples to see how gender stereotypes manifest in translations from different Indian languages. Feel free to reach out with suggestions for other examples that come to mind!!