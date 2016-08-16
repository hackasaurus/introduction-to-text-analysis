# Distant Reading

When Brandon was entering graduate school, an older student once summed up life as a sort of equation: 
> There is a infinite of material that one could read. 

> There is a finite amount of time in which you can read. 

His lesson was that there are limits to the amount of material that even the most voracious reader can take in. One's eyes can only move so quickly, one's mind only process so much. This might sound depressing, but it can also be freeing: if you cannot read everything, why feel the need to do so? Instead, what you can with care.

Computers flip the problem: the problem is not so much quantity of reading as quality. Computers cannot read with any particular nuance or understanding of what they are ingesting. Instead, technology might be best suited for helping us read at scale. We opened the book by talking about close reading, and some critics refer to this kind of analysis, when we use technology to get a bird's eye view of a corpus, as **distant reading**. If close reading gives careful attention to every word in a text, distant reading assumes that we can get new insight from thinking more broadly, by using computers to take in more texts than would otherwise be possible. Rather than carefully considering every element of passages in a few texts, we might have a computer give us schematic representations of thousands or hundreds of thousands of texts. In the last chapter, we worked with concordances, stopwords, and frequency analyses. We were mostly interested in the numbers of times that particular words or phrases didn't appear over the course of our corpus. Computers are especially good at reading for things just like this.

It might appear as though distant reading is less critical: after all, you could theoretically construct a beautiful program to analyze thousands of books for you without you having to ever crack open a single one of them. And some people do. As Matt Jockers, Ryan Cordell, and others have argued, however, even reading at this macro level requires attention to micro detail. Those same skills you were practicing with close reading earlier in the book? They are still deeply relevant. The work only begins once you have some results and a graph. We have to figure out what parts are meaningful and what they might indicate.

## Patterns

One way to begin thinking about developing approaches to using tools and methods like these is to take a step back. When looking at the results of distant reading, you are, more than anything else, looking for patterns and outliers. You could ask yourself a number of question when looking at the results of tools like the ones we have described in this book:

> Does anything clearly not belong or not make sense? What surprises you?

If you know your text is about the American South, and you find that the fourth most common token is 'France,' that probably says something interesting. You might need to revise your expectations and your research questions, and that is perfectly fine. The most interesting thing about a project is rarely the first thing we think it will be.

> How do the numbers that the tool spits out at you connect with underlying concepts in the text?

Our reading experience, our interpretations of a text, the way it makes it feel: these are the result of may things, but language plays a role in constructing all of them. Words form the basis for everything we get out of reading, so we can work backwards from word to concept. Think about what underlying concepts might be taking shape as a result of particular words. For example, if four of the top five words in a text are male names or male pronouns, that might say something about gender representation in the text. Personal pronouns might say something about what it means to be a self in your text. Four times more exclamation points than periods? That might say something about the rhetorical impression the author wants to convey. 

> What trends do you see in the data? Is anything clearly decreasing or increasing over time?

If you have a corpus where the dates are known, you can begin to draw inferences based around language use over time. The Google NGram tool is built on such assumptions, though you should take care to think about how changes in language itself might affect your results (the classic example of this is the [long s](https://en.wikipedia.org/wiki/Long_s), which computers frequently read as an 'f' in older texts). What's more, we experience individual texts over time, and we can exploit this with the computer. 

> What makes you want to investigate more in a particular direction?

You might need to revise your expectations and your research questions, and that is perfectly fine. The most interesting thing about a project is rarely the first thing we think it will be.

It is easy to think that the results given to you by the computer are correct, to take them at their word. After all, how could numbers lie? The truth is, however, that statistics are the results of the biases of the people who produced them. Seemingly good statistics can make anything seem like objective truth when there might not be anything more than a pretty picture:

![bad statistics make a dinosaur](/assets/distant-reading-dinosaur.png)

And a flashy visualization can just as easily show nothing:

![bad visualization](/assets/distant-reading-graphs.png)

The point being: you don't need to know anything about statistics or computer science in order to be able to say something meaningful about texts through distant reading. Knowledge about both of these fields can go a long way and give you more meaningful and interesting things to say, but these tools, methods, and ideas should not be beyond anyone. Take a tool out for a sping and see what happens.

You cannot read everything. Instead, focus on what humans are good at: reading with care and offering interpretation. The computer can work with big numbers much quicker than you. Your job is to help it do so in a meaningful way.