# Reflection on The Bitter Lesson

Themes 
* generalization
* inductive biases
* scientific progress in ai 
	* building machines with minds
	* short term vs long term goals
	* aligning goals with the growth of resources
* how to view the world 

I think many people that read The Bitter Lesson latch onto the first sentence and drag that through the rest of the document: "General methods that leverage computation are ultimately the most effective..."

In this document I will do two things, I will give my interpretation of The Bitter Lesson, and then I will give my thoughts on it. The article is a call for AI researchers to set their sights on longer-term projects. Given that computational resources are increasing every day, we should adjust our way of reasoning about tractability to one that looks to the horizon and what is possible with tomorrow's resources. This may sound like we're just 'kicking the can down the road'. How can we ever say what is tractable tomorrow given the resources of today? I won't posit what I believe is a perfect solution to this issue here. But it suffices to say, prediction is one way to approach the issue. More importantly, the main point here is that AI researcher should be approaching their studies in a way that isn't tied to the capabilities of modern computers.  The methods we give birth to today shouldn't be buried in the graves dug by our current resources.  

One positive data point that supports this argument comes from robotics. Describe the project of visual odometry on a chip (Karaman)

Another theme this article centers upon is generalization. Sutton describes his idea of what it means for an algorithm to be general. He says that generality comes from the amenability of a method to scale with computation. We can ask what is there to be gained by giving our algorithm 10x, 100x, etc more computation? A method would not be general if it made marginal improvements to a solution after it was given an abundance of computation. General methods from search and learning however, as he argues, tend to scale well with more computation. These are the methods we should strive to develop as future-minded AI researchers.

Sutton cautions against making systems that work the way we think our own minds work. He mentions several examples of how putting our knowledge into a system caused it to become less general. This is Sutton taking a stance on inductive bias. He's saying that the more inductive bias you add to a system the less general and less scalable with computation it becomes. These thoughts are echoed in a recent paper by his colleagues at DeepMind, On Inductive Biases in Deep Reinforcement Learning. Folks get hung up on this point, because he also praises the use of convolutions and invariances, which of course can be interpreted as inductive biases as well. But this is a false critiscim because he's not claiming that all inductive biases are bad, just that we need to understand the tradeoff between generalization and specialization when we use them. As AI researchers, we want to find general methods that allow us to build generally competent agents. Therefore, understanding this tradeoff is important. 

I think Sutton could have chosen different words when he said that building in how we think we think does not work in the long run. A fraction of us are trying to understand how we think for this precise reason. If we better understood some of the complexities of the mind, then it stands to reason that we could get closer to AI. Instead, I think he should have just used the words inductive bias to be precise about what he meant here. 

