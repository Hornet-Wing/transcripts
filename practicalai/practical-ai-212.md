**Daniel Whitenack:** Welcome to another episode of Practical AI. This is Daniel Whitenack. I'm a data scientist at SIL International, and I'm not joined by Chris today, but we have a very exciting guest. Today we have with us Jay Alammar, who you might know from a bunch of great content out there, including the Illustrated Transformer, and other articles, also with co:here. Welcome, Jay.

**Jay Alammar:** Thank you. Great to be here. Thank you for having me.

**Daniel Whitenack:** Yeah, it was great to see you at EMNLP back in December. We tried to sit down and have a conversation then, but it didn't quite work out... But still, really great to see you there. What were your impressions, just generally, about the experience at EMNLP, and the NLP crowd gathering there, and what they were talking about? It was just after ChatGPT came out... So yeah, what was your impression and some takeaways?

**Jay Alammar:** Yeah, these are incredible events. The amount of condensed download that you get in a conference like this, of so much research... A lot of it you've caught up to, a lot of it is new and for you to explore... And also, a lot of people to meet, that, in my case, most of them I've never met before; a lot of them I've connected with online, but then having the chance to sort of go deep into some of these topics, and think through with people what they're thinking about... And also observing what themes are sort of coming in, let's say, multiple poster presentations, or workshops... So yeah, definitely awesome running into you. I'm glad we're catching up after that. I'm glad we got to shoot also one of your works in a video we've rolled out...

It's part of my excitement - when I was there, I was like, you know, people who don't go to conferences, they never really get the sense of what happens inside... And so I'm glad that you weren't doing a bunch of these interviews during the conference to cover it for people who were not there. And I think there's room for a lot more sort of content like that. So yeah, it was definitely interesting, and eye-opening, and quite intense in terms of just how much information and social interaction is done in five days.

**Daniel Whitenack:** Yeah. I love it, but at the end of each day, I'm so tired. I love being around people, I actually do enjoy that, but being an introvert, I am absolutely exhausted afterwards.

**Jay Alammar:** A hundred percent. And it's like on a weekend, so it's like also -- you're working through, and then you don't have a weekend, and so you're working through it... So yeah, you definitely need a day or two after to sort of cool down.

**Daniel Whitenack:** Yeah. And you mentioned some of the content that you've been creating. I think many probably know your name, or would have recognized your blog, and some of the blog posts... Like I mentioned, from like Illustrated Transformer, but then you have so much after that as well. You were just mentioning some recent things you put out about Stable Diffusion... Where did you start developing this passion for more of the educational side of this kind of state-of-the-art AI stuff, and what's your perspective on that? ...and what, from your perspective, are you trying to kind of achieve with some of the things that you're putting out?

**Jay Alammar:** \[04:08\] Writing publicly and learning publicly is maybe one of the greatest life hacks I've ever stumbled into. It started about eight years ago, when I was just getting into machine learning... Like, there was any event that happened, which was TensorFlow becoming open source. And I thought, "Okay, now it's a good time to jump into machine learning." I've been eyeing the field with interest, I've been seeing a lot of the deep learning developments, but I had no exposure to it previously. So I was not necessarily working in the industry, but I was extremely interested in it, and I wanted to learn.

It's very easy for you to spend some time learning about a thing, but then three months in, six months in, you need some sort of an artifact to point to that really gives you a sense of how much you're progressing in that field. And for me, some of these initial artifacts was writing a tutorial that sort of captures what I've learned in those two or three months. It also serves that me just writing down my notes, for me to learn a concept a little bit better. So I did that a few times, and it developed in so many different ways. So it opened so many doors that pulled me closer to machine learning... And it helped me learn more and more and more.

If I'm to understand a new paper that came out, I can read the paper and maybe understand or grasp, let's say, 20% of it. But if I'm to explain it, I really have to go much deeper into it; or if you're going to implement it as well. Because if you're writing about it, or explaining the work, you don't want to write something out there that is incorrect. So in a way, it forces the social circuits of my brain to exert that pressure for me to learn... And so that's been extremely useful, and that's opened so many doors.

So through the blog, Udacity reached out to me and I worked with them for about two years, creating lessons on their deep learning and NLP nanodegrees, which includes creating a bunch of videos and code examples, which I continue to do after. So that included, let's say, the YouTube channel that I've been creating some of these videos on, that explain a bunch of these models... But yeah, it's a very fast-moving field, and there's so many exciting things happening every couple of months. And when I get some time and I sort of have my eyes on something that is especially interesting - yeah, I would sit down and try to sort of do a write-up. So some of these milestones of let's say models have been -- so yeah, the Transformer was a major one, GPT-2 was a big one, GPT-3, BERT... Retrieval-augmented transformers - I have written about that... I'm really interested in multimodality, so when a language model has the ability to read, or look at images, or generate images... So I have a write-up about one of these models.

And then yes, the latest has been image generation models... So Stable Diffusion, how these models work, and how text language models factor into their composition is also a sort of another sort of fascinating component for me in that. So yeah, definitely one of the most useful things that I do, and just, I'm really excited to see people finding that content helpful in their journey. People love that visual aspect of -- you know, don't assume that the reader knows everything about the topic.

A lot of people jump into the field - either they jump from computer vision to NLP, or they jump from being a Python backend developer to becoming... And so just thinking about some of the content pieces as being gentle on-ramps for them is something on my mind as I write these, and I encourage people to write whatever they learn. Look, we need so much educational content out there that it's the most useful life-hack I can think of.

**Daniel Whitenack:** \[08:02\] Yeah, I totally agree with you. I think generally, the podcast as Chris and I have developed it over time, our focus is mostly on sort of like community, and like bringing guests in, and all that... But the one sort of like selfish, amazing thing that I've found also is having conversations about all of these topics, and occasionally, Chris, and I do like just episodes, him and I, where we dive into a topic... We did one on ChatGPT, we did one on Stable Diffusion, and others, where like having to talk about these things in a time window, and try to also not say that many inaccuracies... It is a challenge, but it's been really useful for my own learning, that's for sure.

Do you have any tips or sort of cheat codes for those that are like "Oh, I would really like to kind of get into this arena of creating educational content around technical topics, around AI, or NLP, or whatever it is"? Because like you say, there's such a need for good content around these things out there, more so than -- the research paper is great, but follow-ups to that and educational content around things is really useful. So any tips or things you'd like to share for those out there that are thinking about either blogs, or videos, or whatever it might be?

**Jay Alammar:** Yeah, so the first one is start. Just pick a medium and start with it, whether it's audio, whether it's video, whether it's short tweets, or tweet storms, or a blog, or a TikTok video. So just pick something, or experiment with a bunch of them until sort of you find the channel that you're comfortable with. But definitely, what I see a lot of people do is waiting, and waiting, and waiting for them to have, let's say, their Magnum Opus, and have that sort of masterwork be the first thing that they release... Which is the wrong way to go about it.

So you'll definitely improve a lot quicker; people will not judge you harshly for sharing something that you've learned out there... And a lot of people are held back by some sense of impostor syndrome, because they're learning something, and there are so many experts out there about this thing... So they're like "What can I add to this conversation?" And in fact, you can add a lot. You're seeing it with fresh eyes, you're seeing it at a different time, when there are different resources. Even if the only thing that you're doing is putting together a curated list of resources that you've found helpful is a useful thing in its own sort of regard.

So definitely starting, and with time, finding your own voice, and finding your own comfort, and improving your craft is something that will come with practice. You'll definitely not be happy with your first output, but as long as you're putting it out, you're learning and you're sort of nudging your way closer into that place.

To me, it's always useful to sort of - yeah, emulate your heroes. What kind of content do you consume? What kind of content did you find helpful? What exactly about it was helpful to you? So in my case, coming into machine learning, I can identify a few writers and bloggers, whose code or articles really were helpful to me. So Andrej Karpathy, for example, had this article about RNNs, The Unreasonable Effectiveness of RNN - that was one of the first times where text generation really clicked for me, and that it's finally really possible for software to generate text that is somewhat coherent.

I learned a lot from just the styles of Chris Olah, from Andrew Trask, and sort of writing a neural network tutorial with just 13 lines of Python. And that was really one of the first times where machine learning sort of really clicked for me.

\[12:01\] So yeah, that would be, I think, the second one - see the sense of what connects with you; try maybe to emulate it. Don't be shy of stealing. The Beatles spent years and years just doing covers until they were comfortable with their own sort of sound. And so that would be the second one. But it really comes down to just create, put out there, get some feedback, continue creating, and just move the cycle.

**Daniel Whitenack:** I remember at EMNLP when we were chatting a bit, one of the things you mentioned was how you were really enjoying -- I forget the exact words you used, but it was something like "Making NLP boring", or something about applied NLP, or something like that. What did you mean by that, and what are your kind of passions around your day to day work at this point?

**Jay Alammar:** Yeah. So we're blessed to be working in a field that is very hot, very rapidly moving... And every now and then you see something that is super-impressive, beyond the capabilities of what you think software should be able to do. Now, you can see a demo out there, or you can come across social media posts that show that "Model X does Y", which is mind-blowing. But then how reliably really is the model able to do this specific task?

So a massive GPT model is able to, let's say, answer a question about programming. And you can see a demo or a screenshot online of it answering a question correctly. But then is this really reliable for you to build a product around for this specific use case? And the example here is that for some use cases, it is, for others it's not. But if you're just seeing these demos, you have to really ask yourself, "Is this a cherry-picked example, or is this reliably something that the model is able to do?" And for this example, which is answering questions about programming, that is a large class of complex problems that models are currently not able to really be reliably good at, as evidenced by StackOverflow banning the posting of answers from GPT models.

So that's one example of use cases where - yes, you will see flashy demos, but the reliability isn't there. But there are other use cases where the models can reliably generate sort of use cases. And so I work with and collaborate with a lot of developers in companies who are trying to roll out these models, and they would come in with a specific understanding, but then when they try to use it for a use case where the model is expected to reliably be correct, they find that the demos in the real world are a little different.

And so yeah, there's a little bit of education, and let's say a learning curve of how to best roll out these models, and how to think about the various use cases and how they differ, for example. So yeah, I'm really excited in these, let's say playbooks of how to roll these models out reliably, which ones are ready to be used now for various use cases...

One example here is, let's say, neural search and semantic search, and using embeddings to create search systems that go beyond just keyword search systems. So that's a very -- that's a reliable and mature use case of AI. It's not part of the generative AI hype out there, but it really shouldn't be. And so that's a little bit of the example that I feel we as an industry owe the people who are just catching up to these developments to have a discerning eye of "Yes, there are a lot of exciting things here. Let's not get sort of tricked by the hype across everything and have some non-realistic expectations for some use cases that are still futuristic." The models are still able to do incredible things right now, but some of them will continue to be developed... Yeah, that's a little bit of how I think about it in the -- I mean, that is definitely prefaced by saying that there is something really special happening here. And software being able to "understand" and generate text coherently has potential that is beyond what we can really fathom. So it's right to be excited about it, and yeah, go deeper, be a little cautious, be discerning of cherry-picked examples versus reliable use cases.

**Daniel Whitenack:** \[16:23\] When I started first consuming your blog content and other things, and thinking about transformers, and then like going over to a notebook, trying to do a few things, at a certain point it was quite difficult to overcome that barrier and start to integrate some of these things into your applications... And we moved to a time when it's so easy to pull these models in. Now the problem is not so much like good tooling around this, because it is fairly easy to do this at this point in terms of like an integration, but more so around like the workflows, and best practices, and how to judge "Is this model a good fit for this use case?" or "How could I use this model?", that sort of thing. Would you say that's also how you're seeing it? And I'm also wondering - you mentioned talking to clients, and customers, and people building up new applications around these technologies... Have you seen a shift in terms of like most of those people being now like software engineers, instead of let's say data scientists, or that sort of thing? And if so, how does that influence kind of how we think about building AI tooling, and who we're building it for, maybe?

**Jay Alammar:** For the first point, definitely there's a lot of playbooks being created. So first, it started out with prompt engineering. So how do you get the model to do some behavior that is useful for your use case? And they're definitely capable of doing it. But then that's really not enough of a competitive advantage for you to build a product around. And so your playbook will need to include a bunch of other components. So can you have access to some proprietary data that others cannot have?

And then one of the, let's say, also differentiating factors here is can you fine-tune your own models, so that you just improve upon just the baseline model that is publicly accessible, or even open source, in some cases? How can you continue to improve the quality of your own fine-tunes, and continue to collect the data that improves that model? ...and let's say observing the generations of your own model. If you're a company or a product that is, building around a specific model, there are dynamics there that really affect the economics.

In image generation, for example, it's extremely useful to have a public gallery of your model's generations. So Midjourney has one of these, where if you want to create a specific kind of image, you can give the model a few prompts, and explore that generative space. But you're really helped by the model having a massive gallery of hundreds of thousands of examples that really nudge you towards the best way, direction, visual space, kind of prompt type, or description of style... And so that's another example of one element of a generative AI playbook.

Keeping on top of the research is also another source of really good ideas for how to roll out a lot of these models. So two, three years ago there was a lot of these demos, when let's say GPT-3 first came out, of the model answering something factual, and bringing, let's say, a specific fact. So asking it a question, and the model... And it's surprising when that happens, but then you know with time that that's not a necessarily reliable use case for these models, up until now. But there is a way towards one, where you're not just asking the generative model for the information stored inside of its parameters, but you aid it with a search component. There's a part of your system that goes and searches a database, or the web, and then retrieves relevant articles, and presents those in the prompt to a generative model, and in this process sort of improve what kind of a model.

\[20:19\] So that's another sort of element of if you want to tackle this use case, don't just rely on the pre-trained model's parameters and information stored there, but let's say augment it with a retrieval component. And a bunch of companies are figuring out a bunch of these, and I think as a community, we're also sort of working on that together. I'm working on some write-ups to try to codify and make public some of the sort of gray knowledge that's coming together across generative AI use cases in both the text and image space.

Definitely the last few months - to address the second part of your question - there has been an absolute explosion in the public's excitement of text generation models. So yes, ChatGPT is one of these models, and then the generative chat battles happening between Google and Bing, and these product rollouts, and sort of the waves that they're making throughout the industry are definitely putting text generation and language models at the tops of the minds of a lot of people, and a lot of developers are sort of trying to figure out how they can start using these models, how they can think about them... Yeah, it's been an absolutely tremendous couple of months to see that growth, which is not just developers, but it's like people in the street, just -- your parents coming up and saying, "Okay, we finally sort of get what you do", which has been absolutely surprising.

**Daniel Whitenack:** Yeah, I really like how you highlighted this sort of like gray area, or gray matter, whatever you described around this knowledge of how to put these various pieces together into a solution. I guess it's sort of like solutioning with a certain set of potential pathways forward, with state of the art models. So when there was sort of data science hype before all the AI hype, it was like "Okay, you need training data, you're going to train a model." That was sort of like the playbook. Now you're in this scenario where you're like "Okay, well, I have a pre-trained model. Am I going to do some type of fine-tune?" So that's something there. Am I going to focus on prompt engineering? Am I going to chain multiple things together? Am I going to do some retrieval, and pull in like external knowledge into that?

So there's so many of these things where like the chaining and the assembly of the solution is actually where the value comes out, which I think is a really good thing for people to think about. I'm wondering -- because you've in this all the time, you're seeing new problems, and I know you've even showed me cool solutions you put together around like topic modeling, and like labeling topic names with generative models, and that sort of thing. When you come to something like that, how do you parse through this intuition around "Well, is this a situation where I'm like chaining multiple models together? Is this a situation where I really need to focus on prompt engineering? Is this a scenario where maybe I should be focused on fine-tuning?" Any sort of guidance or thoughts around how to develop the intuition around that sort of solutioning? Maybe part of it is just experience, but any suggestions around that?

**Jay Alammar:** Yeah. I'm in complete agreement to what you said. There is this frontier forming between where you train models, and where you're just a user of models... Because of just the very high quality of pre-trained models, and their ability to solve general problems. So they're general problem-solving. The vast majority of my work is above this frontier. So not on the modeling layer. I would want to explore what is possible with pre-trained models, generally without a fine-tune. And that is aided by just the surprising thing of these large generative language models. They do few-shots generation really well. So if you give them three or five examples of a type of generation or a style of generation that you want, they tend to catch on to that, and give you something that is good enough for a lot of use cases.

\[24:32\] And then I know that fine-tuning would be the next step to that. So if that is not enough, and if there's a use case where "Okay, I have 500 labeled examples, or 1,000", that's when I would sort of try to reach to fine-tuning. But in a context of just providing a few examples to the model really helps solve a lot of use cases.

And so yes, this solutioning sort of aspect is where the headspace sort of -- you know, tried to think about just using the APIs of these models, and how to chain them together, how to think about fine-tuning -- not fine-tuning, but let's say embeddings, and then using those embeddings for specific tasks, for retrieval, and then chaining that with generation. So this is a vastly under-explored, and let's say new frontier... Because you can completely spend 40 years just learning the training layer, and the various model architectures, and the various ways to improve the data, and fix of the data. So we need people in all heights of the stack. But then the engineers right now have this widely available and underexplored area of what can you do with pre-trained models, a lot of them served via APIs... And you can definitely do a lot.

**Daniel Whitenack:** Could you just give people maybe who aren't familiar with co:here some general intro to what co:here is trying to do, and what they offer?

**Jay Alammar:** Absolutely, yes. Glad to hear that. Co:here offers an API for large language models. And the goal there is to make using language models easier for every developer or company out there, without thinking about hiring an army of people to train large transformers. Our founders came out of Google Brain, and one of them was the co-author of the Transformers paper... And we have teams that are focused on training, let's say two kinds of models. So the generation, large GPT models - we train, let's say, both of these families in-house, and continue to develop and improve them. And the other family is text embedding models. And these are the ones that can power use cases like neural search, semantic search, text classification... So if you want to classify messages by topic, or by sentiment, they're very sort of capable in that. And the latest release has been the multilingual embedding model that supports over 100 languages. So if you want to do semantic search or neural search, you don't have to build 100 different pipelines for each language that does (I don't know) stemming, and very language-specific pipelines; you can just throw it all at the embedding model and just retrieve the best results.

And so that's the core tech, and the company offers all of that via API. And yeah, we invest a lot in the content and educational side. It's still an area that is quite new. Large language models as a service is a new brand of company; it's only been around for two years, and so we focus a lot on the educational side of the various concepts that are needed there to help both developers, but also your general audience, capture and build those intuitions. And that's something that companies had to do throughout the development of technology.

\[27:52\] So the majority of executives now would know what an API is, for example, but 15 years ago, or maybe 20 years ago, API, or big data, or cloud hosting were all sort of deeply technical words, or words that didn't yet develop. And that is the same now with things like embedding, and fine-tuning, and base model, language model. And so yeah, definitely the education is a part of that. And a lot of it is just us learning with our developer community and sharing the common lessons, so developer number 10,000 doesn't have to repeat the mistakes of the previous developers. We're really passionate about that as well.

**Daniel Whitenack:** Yeah. Part of the advantage of having some of this -- and I'd be curious to hear your thoughts on this as well. So going back to like something I said earlier, when I was first learning about transformers and trying to get hands-on with these things, there was no easy cloud API for me to just access and use. I think now even for open models that's shifting a lot, where you can host things on Hugging Face's inference API, or you could use any number of these services. So you could use co:here's large language models, you could use like Replicate, and what they have in their cloud APIs, and that sort of thing. So a lot of these are available now, where it's a small number of lines of code, and you're able to access the API.

What do you think are the implications of that for how people are thinking about using models maybe differently than they thought in the past because of these access patterns? Maybe it's less people are thinking about the training side, and just like chaining -- I don't think it's an accident we've seen a lot of like chaining things recently... But yeah, I don't know, I'm curious to hear about your thoughts on the implications of how this landscape is changing to where we've kind of gone from, "Oh, let me download model weights" to "I could chain this API together with this API", and that sort of thing.

**Jay Alammar:** I mean, definitely, it makes it a lot easier for a much more larger group of people to start experimenting with these models, because it just lowers the barrier of entry so much, and it enables people to not think about moving tensors across GPUs, and watching out for GPUs running out of memory, and updating model weights... It's just another abstraction, and you can think about it just like every other cloud service out there. So if you want to build a new website, you no longer need to buy a physical machine, ship it to a data center, maybe go physically to that data center and sort of put the code on; it's been abstracted away as a service you can reliably access. Somebody else has the world's foremost experts making that service reliable for you, and you can focus on your core business problem, the core sort of product that you want to do, knowing that these other pieces are there, and are being handled by people whose sole job is to maintain the quality, and increase the quality of these models, and the uptime.

This is especially a factor when these models are massive; they need to be on so many different machines and GPUs, and it's such a hassle to deploy your own models. You need a PhD maybe to really wrap your head around everything that is involved in something like that. And so yeah, it just frees up people to think about, "Okay, this is an API. Think about the frontier, of the next level of services that are now finally possible, that weren't possible before." And let's say we saw new industries come out of these developments in AI.

\[31:47\] AI writing assistance, for example, is a type of industry where there's so many companies now that didn't exist before... And these companies just in general rely on APIs, and they can focus on really creating the best domain knowledge for them to help out their customers. So it really helps in the specialization and sort of that abstraction of not having to worry about this lower layer in the stack, where others are sort of handling it for you, and fine-tuning becomes as easy as uploading a text file, rather than a process of babysitting a model for a week to see what happens. And so that definitely increases the cycle of experimentation, but also the ease of deployment accelerates, let's say, the coming of the next generation of products that are just now possible.

**Daniel Whitenack:** Yeah. And one of the things that we talked about before we started recording was some of your excitement around like multimodal models, and where those are going... I know that's also increasingly easy to kind of tie different modalities together. I think the light bulb is going off for a lot of people. I even just had a conversation yesterday where someone was talking to me about like "Oh, a large language model - could it do this, or that?", like for their use case... And I said, "Yeah, but what if you just add the image component on as well?" You can generate the copy for your ad, and the image for your ad, with generated text, and that sort of thing... Which I know a lot of people are trying, and a bunch of other things, too.

So what's on your mind in terms of kind of multi-modality? I know you've written a lot about Stable Diffusion and other things recently... Where's your mind with respect to that, and what are some of the use cases that that you're thinking of, or the sort of applied things that are interesting to you in that space?

**Jay Alammar:** Yeah. So on the research front, I've written about DeepMind's Gato model that does images and texts, and a lot of other modalities, which is an interesting research development. On the more applied side, we've released a notebook that does a little bit of prompt chaining... A few researchers from DeepMind had this paper called Dramatron, where they shared a system and a bunch of prompts that uses language models to write a screenplay. And it doesn't write it from one prompt; it's seven different prompts that do different things of the story, and then you end up with this screenplay. So there's a prompt to generate the characters, and a prompt to generate the setting, and then the beats of the story. And so you build this knowledge hierarchy. And so we have a notebook that showcases how to do that with co:here's models, but also plugging some calls to Stable Diffusion models to generate "Okay, so these are descriptions of the characters. What might these characters look like?" So that is an AI image generation sort of flow. This is a description of a setting where the part of the story takes place. How can we sort of visualize it enough? ...and these are sort of the flows. And we see libraries, kind of like LangChain, that are empowering a lot of this chaining of the various text models, but also potentially image generation models.

So yeah, that's the most use case that I went down... And it was only really possible for me to have a quick time to experiment with them because there are APIs that do them. So on the Stable Diffusion front, I can share this code because it's an API call to Stability AI's Stable Diffusion models... But I've been wanting to do that with Midjourney, but Midjourney does not have an API that you can call. You have to do it through like Discord, for example. And so that's also that's a differentiating factor for these various products, which ones support API access, which don't... So it will factor into the developer adoption for them on the infrastructure layer. But yeah, that would be specifically the one that I've experimented with the most.

**Daniel Whitenack:** Awesome. As we kind of wrap up here, usually we ask our guests sort of what's on their mind moving into the next six months or so? What are you most excited about? What have you not explored yet, but what's like on the top of your list to dive into? Any thoughts?

**Jay Alammar:** Yeah, I'm really excited about use cases that use both generation and embedding in the same sort of flow. That's one area where I think about a lot, and let's say the topic modeling, and let's say cluster naming use case is one of them. We've open sourced a library called Topically, that does exactly that. So that's one area where I'm working closely, and I think these models can help us really understand large collections of data using that, and create interesting visualizations of them as well.

So yeah, for me it's mostly the interaction of these sort of two systems... Hopefully, let's say, supporting multiple languages as well. So multi-modality is interesting. Also multilinguality is interesting for systems that can support even more and more data that's out there. I think these are most likely the ones that are just top of mind for me at this time.

**Daniel Whitenack:** Awesome. Well, thanks so much for taking time to chat, Jay. I'm glad we got to do this, and I hope to have you back on the show in a year or so we can talk about all the fun things you've explored in the interim... So thanks a lot.

**Jay Alammar:** Amazing. Thank you so much. So good to catch up with you and chat about all of this. I look forward to speaking again.