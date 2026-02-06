---
layout: post
title: After my first paper submission at Cornell
date: 2026-02-05 22:57:00-0500
description: a short reflection about my first paper submission at Cornell and future research directions
tags: reflection research
categories: research
giscus_comments: false
related_posts: false
toc:
  beginning: true
---
Today is February XX[^1], and four days have passed since my first paper submission. I'm writing this to remember what I learned through this submission process but also organize my thoughts to understand where I am right now and where my future research directions should head.

## Self-feedback
### I need to change the whole way I've been using AI as a writing tool
I realized that the language barrier matters more during the submission process. Since things got more hectic as the deadline was approaching, I have less capacity to think about how I articulate my thoughts on ongoing experiments or differenct pieces of the paper. This was a nontrivial problem because unclear communication delayed the process. I strongly believe that this happened because I've become too reliant on AI as a writing tool. I used to use them "just to check the grammar" in my writing. But now I find myself writing even incomplete sentences and throwing them into AI. I believe this has become a bad habit. I don’t pay much attention to how I phrase my thoughts anymore. And I suspect this has also significantly slowed down my progress in spoken Ensligh.

And I came up with one solution on my own which is what I’m already doing here. From now on, I won’t dump all my writing and asking AI, “Can you polish this?”. Instead, I’ll write all the sentences on my own first and use very specific prompts like “Do you think this verb sound natural in this context?”, “Should I add ‘on’ or ‘in’ after this verb?” or “Sould I add ‘the’ before this word?” and will edit each sentence by myself. This way, I can get feedback from AI sentence-by-sentence, and eventually I’ll be able to write without any help from AI. It may take more time to write at first, but I’m pretty sure that this will save me time on writing in the long run.

I also realized that I’ve never really learned how to write professionally in English. But the same is true for my first language, Korean. I did take mandatory writing courses in my freshman year—both Korean and English—but I don’t think they were very helpful. Instead, I’ve read enough Korean writing over my childhood that my writing skills have been developed naturally. In contrast, a year and a half in the US is definitely not enough time to build those skills in English. My solution to this problem is simple. I bought a book called “Rules for Writers” and it’s arriving next week. I’ve heard that this book is widely used in college writing courses to teach the basics. So I’m going to teach myself how to write professionally in English from the ground up. I know I don’t have to start from scratch—my Korean writing skills are already strong[^2]—but I do need to learn the conventions and rules of English writing.

### Double-check my understanding (and let others know what I’m doing)
Two days before the deadline, we found out that there was a missing counterexample part of the paper that looks very critical for the paper’s acceptance. Now, I’m trying to understand why that happened and why I failed to find the counterexample in the final two days before submission.

One main reason was that I thought I had already found the counterexample, but it turned out not to be the one we needed. I should have asked others to verify whether it showed the behavior we expected. This left me only one day to find the counterexample, and I panicked, so I couldn’t think as clearly as I normally do. I only fully understood the purpose of this counterexample and the correct experimental setup about 12 hours before the deadline. And I don’t want this to happen again.

### Think realistically about what I can get done
Another reason the counterexample felt so important was that some of the experimental results came in very late. In short, it was a domino effect. Looking back, I spent most of the weekend right before the deadline working on something that didn’t even make it into the final paper. One of our collaborators suggested a new setting just before the final weekend, and I thought we could run the new experiments over the weekend and end up with a stronger paper—even though we already had results from the previous setting. After running the experiments, I realized that the new setting required more work than I expected, and that it would be better to stick with the previous results. So I went back, ran the remaining experiments with the earlier setting, and then realized how crucial the counterexample was.

I should have thought more carefully about what was realistically doable during that period, especially given how fatigue accumulates. If I hadn’t run the experiments over the final weekend, we could have obtained the late results sooner and spent more time on the counterexample. And after I had fully recovered from the deadline crunch, it took me several minutes to come up with a better counterexample idea.

### Step back and think about the paper’s overall flow
Another reason was that I didn't think carefully enough about the whole structure of the paper during that time. If I hadn’t focused on the performance of the results until the last minute, I could have focused more on the paper’s overall flow and gotten the late results sooner. So here's another lesson I learned: in the final few days before a deadline, I should stop obsessing over performance and instead focus on the paper’s narrative based on the results I already have. I need to identify what’s missing in the story and use the last few days to strengthen those parts. That way, I can write a better-quality paper.

### How do I feel now after this paper deadline?
Of course, there are some parts that could be done better. But overall, I feel like I’ve finished weaving this huge textile, named “Research in theoretical machine learning”, but still rough and loose in places. I’m happy that I went through the entire process—from theoretical discussions to paper writing—but I can still see so many holes in this textile. Now, I need to think about what I want to do with it.

---

## My future goals for the remaining PhD
### Where am I
So where am I right now? I want to answer this question to think more concretely about my future research directions. But before I do, I want to revisit the goals I had when I started.

Before I started my PhD, many people asked me why I wanted to pursue one. I always answered by saying “I want to learn more”. Of course, PhD life involves many things beyond learning, but my two main goals were to shift my research from computer vision/deep learning to machine learning theory and build a stronger foundation in mathematics and statistics.

In that sense, I’m happy with where I am right now. During that transition, I found Bayesian optimization and have been wrapping up my first project in this area. This first stage of my PhD has involved lots of learning through classes, books, and group meetings. I’m happy with my current level of foundational knowlege—not in abolute terms, but relative to the time and energy I’ve had so far in my PhD. I’m confident I can build my mathematical skills faster than last year.

The main goal of my PhD is not just to earn a degree, but to become a useful person in both theory and applications. I often feel people in theory do not care about applications, while people in applications don’t engage enough with theory—which can sometimes lead to wasted time and resources. I’m not sure whether this goal will lead me to academia or industry after my PhD, but I do believe we need more people in the middle. With that in mind, I set up four goals for the rest of my PhD.

### Knowledge
I want to build a stronger foundation in mathematics and statistics than I have now. It’s hard to measure these skills and knowldege using an aboluste metric, but I’ve started my personal project: writing my own notes from David’s courses that I took. These will be combined notes from three classes—Numerical Analysis, Numerical Methods for Data Science, and Matrix Computations. I think once I finish these notes, I’ll feel much confident about my foundation.

Also, I expect to have more chances to give talks in David’s group meetings, especially on multi-objective optimization. I see this as a great opportunity to revisit optimization basics and strengthen my understanding.

### Mathematical reasoning
I want to get better at formulating real-world problems in mathematical terms and identifying (or developing) the most appropriate theory to address them. Untimately, I think this is the most important skill I want to build during my PhD. Whether I end up in industry or academia, if I became truly strong at this, I'll be able to survive in many different settings.

That said, this goal is still abstract. To do it well, I need enough mathematical depth to formulate problems correctly and connect them to the right theoretical tools, and I also need enough practical understanding to implement those ideas in real systems. Even so, I think it's useful to articulate this goal clearly before I move on to my next project.

### Topics
"A real-world problem" sounds too broad, so I want to narrow it down. First of all, I don’t want to leave the field of machine learning. In other words, I want to focus on projects that are a strong fit for conferences like ICML, ICLR, and NeurIPS. I left applied deep learning several years ago because, at that time, most of the researchers seemed focused on building fancier architectures while barely understanding the fundamentals underlying them.

After reading [Alex’s blog post](https://avt.im/blog/where-are-we-and-what-now/) and talking with him about the reasoning power of transformers, I started to feel a faint sense that I might need to return to this area. I'm still very interested in decision-making problems, since I think they are deeply correlated to our daily lives. Maybe I underestimated how transformers are. I should write a separate post about how I think about current (and past) AI and future of AI research in general so I can put this in a better context.

At the same time, I want to see how these ideas play out in real scientific settings. This could be optimization/decision making problems in many different settings in physics or computer science. This semester, I'm leading a reading group on ["An Introduction to Stellarators"](https://epubs.siam.org/doi/book/10.1137/1.9781611978223). I see this chance as a chance to explore other scientific areas that are rich with optimization problems.

### Records
At the same time, the world needs to know what I am doing. In the short term, my goal this year is to build a strong track record so I can apply for summer internships next year. “A strong track record” is still a bit broad, but at least I can show people what my current research area is and what kinds of problems I’m interested in.

### Are they doable?
I listed four goals for the rest of my PhD. Right now, I don't think it's crucial that each one is fully achievable; they're more like a compass in the dark that helps me navigate my PhD life. I think next year—or in my third year—will be a better time to turn them into more realistic, concrete goals.

Also, this question is closely related to how I work everyday. It connects to my work routine, habits or even my personal life, so I'll write about that in a separate post. Thanks for reading this long reflection about me. I hope it’s helpful to people who are interested in research in some way.


[^1]: It took me five days to actually finish writing this post.
[^2]: I have a personal blog in Korean where I post essays, poems, and short fiction. I also have a (not-so-)secret dream to publish an essay collection.
