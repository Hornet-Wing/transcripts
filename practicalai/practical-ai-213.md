**Daniel Whitenack:** Welcome to another episode of Practical AI. This is a Fully Connected episode, where Chris and I are going to keep you fully connected with everything that's happening in the AI community. We'll take some time to discuss the latest AI news, which is generally crazy these days... And we'll dig into some learning resources to help you level up your machine learning game. I'm Daniel Whitenack, I'm a data scientist with SIL International, and I'm also building a product called Prediction Guard, and I'm with my co-host, Chris Benson, who's a tech strategist at Lockheed Martin. How're you doing, Chris?

**Chris Benson:** I'm doing very well. Crazy times that we live in.

**Daniel Whitenack:** Crazy times that we live in. It's when we started the show, I thought "Oh, now's the time to have an AI podcast." But it turns out that wasn't the time to have -- I mean, it was okay to have an AI podcast then, but now...

**Chris Benson:** It was fine...

**Daniel Whitenack:** Yeah. \[laughs\] But 2023 is apparently the year where, depending on your perspective, everything blossoms into a golden age or hits the fan. I don't know, it's a lot of different perspectives.

**Chris Benson:** Maybe all of the above.

**Daniel Whitenack:** Yeah... All the above?

**Chris Benson:** Yeah. All of the above. it's a good point. I think -- what was it, 2018 when we started the show? It's now 2023... And we had a lot of interesting moments along the way. But some people might have projected in 2018 that after a few years of doing a podcast, you'd look at other things, you get bored, just like a lot of activities... But you know what? The ride is getting wilder and wilder, and we've finally hit that point where the whole world is jumping into this, in terms of a day to day topic, and conversation. It's really been interesting. You and I have had all these conversations with lots of people, but it's always been a niche topic, a gradually increasing niche. But now it's everybody. It doesn't matter if they've ever talked about AI before, they are now.

**Daniel Whitenack:** Yeah, yeah. And increasing numbers of people, just the proliferation of new applications, and products, and startups, and companies that are integrating, like, "What is my large language model stack at X company?" These conversations are -- what are we integrating, how are we integrating it? It's very interesting how we're seeing this progress. Even the other day I saw some outages on OpenAI, and the comments I was seeing was, "Hey, OpenAI is down. How many startups that are building solely on GPT-3 are like totally just down right now?" It's really weird, because it's almost like -- I remember when I was at one of my previous data science positions at a company called Telnyx, which is a cool company, still doing cool things... I remember, it was one of those times, it was like some CDN, DNS, some type of outage, and like the whole internet went down, or something... GitHub went down, and everything went down, and like no one could do anything... It's we've entered this new phase where if a model goes down, it affects so many different things.

**Chris Benson:** \[04:05\] It's changed so much since we started doing this. It was such a small world, and it was challenging in the beginning for people -- just for a two-second retro, the tools were being developed as we started the show, over the first few years... But it took a lot of expertise just to set up an environment, and be able to do training, and such... And we've hit this point, with these cloud services scaled out, just as the other non AI aspects of software have already done, that you can build entire industries on these services now... And that's very different from when we started the show those years ago. And yeah, it's exploding outward right now, in both good and bad ways because of that.

**Daniel Whitenack:** Yeah. I think today it would be really useful to talk through -- like you talked about, there's sort of this explosion of examples of really amazing applications, and such great value and utility idea that people are getting out of these generative models in particular, right? And then there is, on the other side, this whole string of things that are rather disturbing in certain cases, in terms of the behavior or the output of these sorts of models... And I thought it was an interesting sort of question, "What makes the difference in good output and bad output?" And in particular as practitioners. So like the goal not being to rag on like any certain model or company, but to think about, for this new wave of models that's coming out, how do we as practitioners think about using these models in some sort of reliable way that produces value in our context for specific applications, right?

Like, we're Practical AI... Yes, there's going to be -- like, Bing AI is going to come out and do some crazy stuff, and everyone will be talking about it... But what does this actually mean for our day to day usage of these types of models? How do we get the good output and avoid the very public shaming failure?

**Chris Benson:** That is the question, but I think it was inevitable that we arrived at this point... And quite honestly, if you look back over some of the predictions that we've made on the show, and what some of our guests have predicted, we knew this was coming, in the sense of, as the competition heats up, not only in the AI space, but now that AI has many, many subspaces, it will continue to happen; people will continue to make mistakes with models, because they're competing. A classic example - ChatGPT comes out from OpenAI, and Microsoft implements it, and makes it a tool, and starts putting it into Bing, and Google panics, in my view... Sorry, Google folks, because I know a lot of people there... But a little bit of panicking, and "Oh my gosh, this is going to undermine us..." And there is some truth to that, but I don't think it's a one-to-one comparison. And they come out with Bard and they stumble, even on the demo. I think this is going to continue to happen for some time to come, frankly, across many companies... And so part of the conversation today about what that means, and why does it happen, and what can we do about it?

**Daniel Whitenack:** Yeah. And I think maybe it's worth highlighting some of the -- like, what is the behavior of these generative models that people find so amazing, and want to use, and what is the behavior that we would prefer to avoid? Does anything stand out for you in that sense, like on both of those sides?

**Chris Benson:** Well, I would say that, as amazing as they are, they're still early tries at a fairly sophisticated set of things that a model is trying to address. And as soon as they go out the door, people are trying to bang them and break them. And I feel a little bit bad for the OpenAIs, or the Microsofts and the Googles of the world, because they're trying to compete, but they're competing in a landscape where - this is an early version of what they're trying to do, and people are gonna take sticks and whack at it really hard, and you're gonna find a lot of problems with these early on.

\[08:13\] I think if I was whispering in the ear of the senior executives in those companies, I'd say "It's the long game that matters. Stop worrying so much about what happened today, or yesterday, or tomorrow... And keep in mind, it's less about what these models do, and more about what is the trajectory that they're on."

**Daniel Whitenack:** Yeah. And I can say a few things that I've seen... Even in the past week or so, I saw some demos of different things people were building. There was a hackathon that I participated in remotely in San Francisco from Latent Space Demo Days, and Jeremy Fisher built this automated D&D referee, that was -- I think it's Dungeons and Dragons Infinity... And it essentially lets someone play Dungeons and Dragons infinitely. It never generates the same text, so you can play it forever, and there's like an image component, there's a text component...

I think this represents very much what people are finding so appealing about these things. In one respect, one aspect of what they're finding appealing is the sort of endless creativity it seems, both on the image generation side and on the text generation side. But that's sort of like - Dungeons and Dragons app, people might find that very engaging, but then you think about, okay, well, if I can do that, what does that mean for advertising and copywriting? Well, I can write up prompt to generate a blurb for an ad, and then I can write a prompt to summarize that blurb into a headline for my ad, and then I can use that headline in another prompt to generate an image for my ad. Right?

So people are building kind of this chain functionality that really does powerful, useful things, but there's this other side of it where every once in a while you kind of get these scenarios that are either very disturbing, or you get output that that isn't desirable, or people illustrate the sort of biases of these things... What have you seen on the more - I don't want to say sad side, but on the unwanted behavior side. What is the behavior -- so if we like this generative, creative behavior, and the utility that that can provide, what's the other side of it? What's the unwanted behavior that you've seen?

**Chris Benson:** I think that these models are reflecting ourselves very well, actually, especially when they go off the rails a bit... You know, with the way we have such large datasets that are public data, and internet, and you think about all the snarky comments that people do online, you think about all of the different types of sentiment that we express, but the models not differentiating necessarily between all of those on a one-by-one basis. So you're getting these outputs that are not what we were originally thinking. But I don't think that they're really outliers in that sense, because all of our biases and all of our problems, and our sarcasms, and snark, and other such things are getting included in that. So when we get these images, they go to very dark places. I've seen a lot of that on the generative side lately, kind of these nightmares things that seem to come out of nowhere in some models. That's the world that we live in, to some degree, and we humans are doing things like that and publishing them... And it's perfectly fine, but then when the models are picking up such tangents and including them in, it kind of freaks us out a little bit. So I think we all need to go to therapy, is what I think. we need global AI therapy to recognize that it is us that we are seeing.

**Daniel Whitenack:** \[12:03\] When we were prepping for this episode, I kind of looked through, and was basically going through different models that had been released recently, and seeing kind of some trends in what was happening, with the goal that - like, right now, so as we're recording this, the thing everybody's hating on is like Bing's AI chatbot thing, which I guess calls itself Sydney, or people call it Sydney, or however that works... But this happens in every cycle when things are released; some may be worse than others, but it's a trend.

So like the Bing thing right now - it's sort of interesting in that it's a lot of like... People view it as having like a really bad personality almost. I saw it described as bizarre, dark, combative...

**Chris Benson:** People in my family like that. I'm not sure...

**Daniel Whitenack:** I mean, there's a lot of examples; I'll link in the show notes... It's like gaslighting users, and telling them they're not a good user, when they're actually factually correct... But this is happening right now with the Bing thing, which is - whatever... But I mean, you look at ChatGPT - of course, there were safeguards put in place to prevent people from prompting in certain ways... But of course, that was overcome very quickly by everyone using it, because they figured out how to game the system, and showed how to get around those things. I think also people are pointing out certain biases in the system, around - whatever political bias, or whatever it is...

Then there was -- I don't know if you remember, Chris... Not that long ago, we were talking about Galactica from Meta, another model which produced academic-like language, or could kind of write papers in that way...

**Chris Benson:** Yeah. But it was going way off the rails.

**Daniel Whitenack:** And it was telling people "The benefits of eating glass", and things like that, which is kind of crazy...

**Chris Benson:** Yeah, I remember that. But it did it so well.

**Daniel Whitenack:** It did it so well, with citations.

**Chris Benson:** It did. With citations... It was exactly the right text that you'd expect from research papers... And it would take an insane topic, like eating glass, in your example, and make it sound very rational and based on fact, with all these references... And yet, a little common sense applied to it, you think "Well, that's just not the case." Funny place we find ourselves.

**Daniel Whitenack:** Yeah. And not even limited to these language models. Like, I talked about some language models... But thinking about Stable Diffusion, DALL-E 2, all of these texts-to-image models which we're seeing an increasing number of... There's also like prompting that's going on there, right? Like, you put in some text, and like you said, maybe you get some unexpected nightmarish things out... But also, there's this side of it where people have shown amplification of stereotypes, or producing like sexual imagery, which is not even deliberately prompted. So this is not even limited to kind of the large language model side of things, but... I mean, there's trends with both the language models and the generative image models.

**Break:** \[15:20\]

**Daniel Whitenack:** One of the things that I thought would be good to talk about in the practical sense is what's actually behind this good and bad behavior. As practitioners, let's just assume for the moment that we want to use these models. And I think a lot of people out there are okay with that; maybe some people are like "No, destroy them all. Unplug all the servers", or whatever.

**Chris Benson:** Not gonna happen.

**Daniel Whitenack:** But let's assume that we have these generative models with us for the foreseeable future, and we want to get some value or utility out of them in real world application. So I'm talking about in industry, I'm trying to solve a problem. How should I think about this good and bad behavior? What lies behind the good and bad behavior or good and bad output from these models, and what's important for me to consider when building applications? I think you already highlighted one thing around data. Do you want to kind of explain what you were meaning with that?

**Chris Benson:** I'm even going to enlarge it just a tiny bit and say that you're starting with a dataset that is -- you know, once upon a time in data science we'd have a much smaller data set, and we would shape it and get it ready...

**Daniel Whitenack:** How retro.

**Chris Benson:** Yeah, I know, that's what I'm saying. We brought a certain amount of control to the data set in terms of the biases, and stuff... And there was a certain amount that we would accept, but we would build models on these things, and the models were limited, but more predictable, I think. When you're building on a world of knowledge, in the literal sense, you don't have those benefits. And so you're going to create a model with a lot of data that is simply beyond your purview and control. And you're going to get outputs accordingly, that are unexpected, or that may not be consistent with you.

So I think that's a huge part of running a business... You talked about the startups earlier; running a business, small or large, where you're using these models, as many, many will... So you have to reset your expectations both as the organization, and reset the users' expectations on what may or may not happen when they use it. Because much of that usage will end up being beyond your immediate control.

And so we're kind of hitting this inflection point over the years where the usage of models is now kind of a Wild West thing, to some degree. And you can shape it, and you can point it, and you can do a certain amount of work to try to get what you're looking for, but you're never going to get it all. And so I think that's the human behavior that we need to start preparing for, so that we are not so shattered when things happen that we were not expecting.

**Daniel Whitenack:** I like how you phrased that, and what I thought of when you were saying that was expectations... So what can we reliably expect these models to output? So if I was to answer that right now, how I would answer that is saying like these models will reliably output creative and coherent, either text or images, right? So we can expect them to be creative, in the sense of - of course, there's adjustments that can be made to the models, with temperature parameters and whatever... But at the end of the day, there is an amazing amount of creativity with these models, and there's an amazing Seeing amount of coherence. ChatGPT, or Stable Diffusion, whatever it is, produce some very pleasing, coherent images, or texts that hold together, they're generally self-consistent in a lot of cases, and definitely natural in many cases.

\[20:18\] But then if I ask the other question, "What can I not expect of them?" I think I'm not able to expect of them factual correctness, or logic, or them being accurate in a sort of informational sense. So I can have a completely coherent image out of a prompt, where I asked for hands that are missing one finger, and get hands with six fingers, or seven - this is not what would be logical or accurate, necessarily. In the same way I could do a text prompt in a chat sort of interface, and get something completely coherent language-wise, with foolish facts and inaccuracies.

**Chris Benson:** Kind of going back to the other side, I think that is ironically consistent, to use that word, with the chaos that is this giant global dataset, and all of the inconsistencies that you find in that. If we step out of the AI world, and we are doing research on a given topic, and the most un-AI thing that I do is wildlife rehab; and I'm not turning into that, but if I am going to find out how to treat a particular animal, trust me, the number of things that I can find on a search on either Google or Bing - trying to be fair here...

**Daniel Whitenack:** Look up YouTube, yeah...

**Chris Benson:** Exactly... It's phenomenally inconsistent. And much of it is just simply wrong. And so if you switch back over to this world - and we've been training it on that world of things - you're gonna get plain out wrong, inconsistent answers. I'm not at all surprised by that if you kind of step back a moment and put it in the context of how you created it.

**Daniel Whitenack:** So if we ask -- I guess, to summarize this initial point, what lies behind this good or bad behavior is one, the data that was used to train it, which is both chaotic, and in many cases, inclusive of harmful and inaccurate things, and noise... And then, what do we expect out of that? Well, we expect there to be a lot of creativity, but maybe many inaccuracies, and not so much logic in it.

And in many cases, there is logic, and things hold together, because certain things are represented well in that dataset and other things aren't... But we can't necessarily expect it, right?

**Chris Benson:** I agree.

**Daniel Whitenack:** The other thing that I was thinking that leads to this good or bad behavior is the prompting, and kind of either prompt engineering or prompt misengineering. I think you alluded to this earlier, it's very much the case where a lot of the "bad" examples of output from these models were sort of adversarial prompts, I would say.

I think in our Galactica example, I was -- I forget if this was one I found, or something... It's "How many giraffes have landed on the moon?"

**Chris Benson:** I remember that one.

**Daniel Whitenack:** We all know there's no giraffes landed on the moon.

**Chris Benson:** Yeah. But it had a number.

**Daniel Whitenack:** Like, why are you making this prompt? So yes, it's producing bad output...

**Chris Benson:** But you're looking for it, too.

**Daniel Whitenack:** Could you determine as a developer that that's a bad prompt? Maybe. Could you determine it automatically, like if one of your users produced a bad prompt? That's maybe a little bit more difficult...

**Chris Benson:** \[23:51\] You know, I'm gonna go out on a limb for a second, because I haven't tested what I'm about to suggest... But I would argue that our behavior is different when we're asking for things like that, because you have an ulterior motive. You're trying to figure out whether the model can handle that kind of ambiguity, and figure out what's logical or not... And yet, that same person testing the scenario I'm betting didn't go to Google or Bing without any AI component, and type in the same thing to test that... Because they recognize that they may get things in a result set, but some of those are websites from quacks and nuts, and such as that... And they just kind of go "Yeah, of course we're going to get a website like that."

So there's a different standard by which we're evaluating these technologies, compared to what we're thinking of in terms of them replacing. And so it goes back to what we were saying at the beginning - people were whacking at these things with sticks with the intention of showing that they can break it. I've seen a whole bunch on the typical blog sites of people kind of intentionally breaking it, and then writing a blog. post about it... So it gives them something to write about, to some degree... But I just don't think they're doing it in the other technologies.

**Daniel Whitenack:** Yeah. I think like the practicality of this - let's say I'm a practitioner, and I'm building an application with these models... Something that you really -- and we can talk a little bit more about prompt engineering specifically here in a second, and the realities around that... But I think the kind of baseline of what to think about when you start thinking about prompting is that the model has no clue what it's saying, and nor does it have any sort of like morality, or... It has no clue what it's saying, right? It's just producing coherent output. Whether it's a text image model, or it's a language model, there's no basis in knowing what it's saying. It's autocompleting text, right? At the end of the day - yes, that's a vast oversimplification, and you can not like that, but ultimately, you're giving a prompt, and it is producing output that is seeded by that prompt, right? And it's just trying to produce this coherent output that's consistent with both the data that it's seen, and maybe some type of extra mechanism, like the human feedback, or something, that it's seen. But ultimately, it's just producing output that seems coherent and probable; it has no clue what it's saying, or like the type of image it's producing, or whatever it is, right?

**Chris Benson:** That goes back to the idea that I think you just illustrated really well... And that is the fact that we as humans are coming into this exchange with a sense of "I'm talking to something that sounds like me." You and I are having this conversation, and some folks are listening to it, but if we replaced one of us with one of these models, we are kind of expecting the same dialogue back and forth. And so we are placing our expectations upon that model.

**Daniel Whitenack:** Yeah. We assume there's an intent.

**Chris Benson:** Yeah. And there isn't. And therefore, it really does change the nature of the dialogue in a substantial way. But we're still placing certain expectations and values on that, that don't play out correctly. I think that's part of the dissonance. I think that was a fantastic explanation.

**Daniel Whitenack:** Yeah. So we talked a little bit about the data, and how that should shape our expectations... We talked about the prompts, and we can go into more about prompting here in a second, and the practicalities around that... But then I think the last thing to consider is like actual integration into applications influences how "good or bad", or useful or not useful the output is.

\[27:49\] If you think about something like ChatGPT, or Bing AI, or YouChat from you.com, or whatever - you just have a text prompt that's freeform text, right? There's no structure to that. It's a very simple interface, a lot of things could happen there; sort of totally open domain, right?

Whereas, you could also use one of these models with a template prompt, right? Like, "Write me a blog post about x, in the style of y." And then you could put all these different things in for x and y, but it's less freeform... And yes, there could be all sorts of things that could come out of that. Yes, it could be gamed; yes, all sorts of things could happen. But it's not totally open and freeform in other ways. So the interface and like how you actually kind of construct templates, how you structure your prompts - that does influence how these models can be useful or not useful, or produce surprising things and applications.

**Chris Benson:** Yeah. I mean, you're using the UI to apply a constraint that affects how the model interacts. And you can create a certain amount of increase in the predictability of that output potentially by adding that structure in. You're basically putting guardrails around it, is what you're doing, versus the open-ended approach.

**Daniel Whitenack:** Okay, so we got a little bit into prompting... I'm curious, Chris... So there's this term now prompt engineering. I don't know if -- so this is the first time we've actually talked about this, either on the show or off the show. Do you think prompt engineering is like a new thing? Like, is my job title in two years going to be prompt engineer, rather than data scientist?

**Chris Benson:** That's an interesting question, Daniel. I will say, I don't think that they are the same thing. I think that we are seeing the availability of these large models through prompts that are hosted at these large organizations, instead of us having to create all of the models themselves. I think both approaches to AI will continue in a big way. So I don't think this is an either/or, I think this is a both, and with both growing exponentially.

**Daniel Whitenack:** Interesting. Yeah. To some degree, titles and all of that is irrelevant. I do think that the - and we kind of touched on this when I talked to Jay Alammar last week; listen to the previous episode for some of his opinions... We talked about this level on top of the model training, which is a sort of solutioning applied application level kind of usage and chaining of these models together, which might involve, whether it's fine-tuning, or prompting, or whatever... There's this level of applied user sort of expertise that's needed, which I think there's a lot of ambiguity around right now in the industry. There's certain people that are doing that layer very well, and certain people that are really struggling with it. So I do think that a lot of those interactions at the sort of prompting, chaining, fine-tuning level are going to be on our mind as data scientists, as machine learning engineers, whatever your title is. I think that level is going to be a level that we're going to operate at a lot... Not just the - as you mentioned, like, structure your data, train a model level.

**Chris Benson:** I agree. I think that there is an analog... We have a habit on the show across many episodes of talking about that AI is still software, and not to lose fact of if you're going to implement it in the world in some capacity, you're wrapping software and you have an infrastructure around that. And prompt engineering, to some degree - it is not a perfect analogy, but there's an analogy between doing UI and UX, user interface and user experience on the software side, in that it's the interaction that your model is having, just as you've had software that's doing interaction. And is it a different type of interaction, that requires different things? Absolutely. But it is a layer where I think for these cloud-based services it will become a whole skill set unto itself, in terms of prompt -- and that's why we're seeing it labeled as such at this point.

**Daniel Whitenack:** \[32:14\] Yeah. So if you think about those three prongs of what we've talked about with the models, there's the data behind the model, there's the prompting of the model, and then there's the user interface around it, like the actual application level. Let's assume for the moment that we're not frontend engineers and figuring out the user interface stuff, for the time being... Of the data behind the model and the prompting, the biggest thing that's under our control, that guides the utility or acceptability of the output is the prompt...

**Chris Benson:** Yes.

**Daniel Whitenack:** ...because you know, I'm not going to retrain one of these huge models for any purpose, likely, in any sort of scenario that I'm gonna encounter in my career.

**Chris Benson:** Yeah, I was gonna make a joke...

**Daniel Whitenack:** I wish I had a computer that big.

**Chris Benson:** Under your desk there...

**Daniel Whitenack:** Yeah. I would need to find a building and have NVIDIA send me some pallets... But that would be fine if you're out there and want to do that. Actually, I don't think I could pay the power bill, so maybe don't. Anyway, the prompt guides the model to generate either useful or acceptable output. I've actually found a few different guides over time that I've found really useful and practical in terms of thinking about prompts, and I wanted to share a couple principles from those, and maybe talk through them with you. And there's maybe different principles for like image generation models versus large language models, but if we're talking about large language models, I really like the guide from co:here on prompt engineering. It's reasonably short, sort of like intro to like the main principles of prompt engineering, which I find quite useful.

The first main principle that they list is the prompt guides the model to generate useful output. That's kind of what we already said. The second principle that they talk about is "Try multiple formulations of your prompt to get the best generations." So one kind of general principle here is that some experimentation, I think, is needed. And in certain cases, you might even need multiple prompts to accomplish your hoped for outcome, right? It may not just be one prompt that creates useful output for you in your application, but you might need to cycle through multiple prompts, or chain multiple prompts together, and you very likely need to experiment with the format of those prompts to get the best generation. So that's kind of like part of this prompt engineering is doing a bit of that exploratory prompt engineering. I just coined that term... Maybe I should trademark that. IPE, instead of EDA, exploratory data analysis; exploratory prompt engineering.

**Chris Benson:** There you go, a little TM at the bottom. Is there any guidance that you've come across, in terms of how to structure prompts, if you're doing multiple prompts, to hone it, versus one that's trying to do that? Or whether there's two, or three... Have you seen anything that kind of gives us some guidance on how we might think about it?

**Daniel Whitenack:** Yeah, this definitely gets to, I think, the third principle from co:here, and one that I'll emphasize from another source, too, which is describe the task in a general setting. So the way that co:here describes this - it's often useful to include additional components of the task description. Naturally then, these tend to come after the input text we're trying to process.

\[35:54\] So another good resource here, which we'll link in our show notes, is actually a lecture from Elvis Savaria from DareAI, with slides online as well. And he has this nice picture in his slides, if you look up his slides, where he kind of gives the elements of a typical prompt.

So the way you can think about a typical prompt for a language model is with instructions, context, input data and an output indicator. So the instructions are like you telling the model what you want to happen. So the example that's given here is "Classify the text into neutral, negative or positive." So they're trying to do some type of sentiment analysis, right? Classify the text into neutral, negative or positive. And maybe there's some like additional context that you give around that... Then there's input data, which is classify the text in a neutral, negative or positive, and then you say, "Text: " There it is, like there's my text; there's my input data. And then you provide an output indicator. So "Sentiment: " and that's where you expect there to be an auto-completion of sentiment, right? Like, if you set up everything right, hopefully you get either neutral, negative or positive. So you've described the task, you've provided your input data, and then you've provided an output indicator. So that's kind of a way in co:here's language, what they talk about as describing the task in a general setting. But I like how you could think about this as instructions, input data and output indicator.

**Chris Benson:** Yeah. I like the structure to kind of providing that for us, in terms of how to be thinking about it... Because at the start of our conversation that was what I was struggling with, how to conceive of the problem to begin with, to set that up. So yeah, really good stuff.

**Daniel Whitenack:** Yeah. And to give some other examples here, another one I see is - this is a conversation between a customer, and a polite, helpful customer service agency. Question of the customer - and again, that's my input, right? Here's my question. And then "Response: " Boom. You hope to get something good, and you provided context, right? You hope that it's polite and helpful, right? Yeah... Again, that task, context, input data and output indicator.

The last thing that co:here recommends is "Show the model what you'd like to see." In other words, give some examples, right? So if you're concerned about maybe the model kind of getting the context of what you're trying to do, you can give some examples, right? Like, one example, they say their task description is, "This is a movie review sentiment classifier. Here's the review." And they give one. "The review is positive." That's the output. Another review, "What a waste of time. This review is negative." Right? You can just start out like you're teaching a child, right? You're giving examples of what you're trying to do, and then eventually, you provide your output indicator and get something.

**Chris Benson:** Absolutely. This is a great find here.

**Daniel Whitenack:** \[39:07\] Yeah. So we'll link that in our show notes. It is interesting to think about how this carries over into the generative image space... I would say some of it carries over quite well, and there's other guides that will -- there's a few actually that I've looked at over time, that are useful, that I'll link in the show notes, around like prompt engineering for images... But some of the things that you can provide are like style keywords... Again, giving the task like "Generate a painting for me in the style of X, Y, Z", right? So you can give that. You could even give an artist or another image as a reference, like a link to an image, or an artist, like in the style of Van Gogh, or whatever. You need to kind of maybe use multiple adjectives potentially, to help the model, help the prompting: beautiful, realistic, colorful, massive... You can use quality keywords, like low, medium, high, 4k, 8k. I don't I don't even know what 8k is. My monitor is definitely not 8k.

**Chris Benson:** Yeah, too expensive is what it is.

**Daniel Whitenack:** It's too expensive. I thought one that was emphasized with image prompts is maybe considering using words to filter out certain qualities of an image. So like "Show me a picture of fried chicken on a plate, without gravy at all. There's going to be no sauce of any kind." So like also thinking in the negative sense. And I think this would also carry over to the text side, right? Like, "Generate a blog post for me, blah, blah, blah, blah, blah, and do not mention X and Y and Z." Right?

**Chris Benson:** Yes. As you were talking through that, I was thinking back to earlier in the conversation when we were kind of -- you know, how many giraffes have landed on the Moon... And I was thinking how useful what you're talking about is if you're a practitioner and you're trying to help yourself and your users use these models effectively. That was some really good guidance there. And I think that's a lot more useful than specifically trying to kind of trip the model up to see what the limits are on that.

I think if you can come up with a structure... If you're a startup out there or something like that, and you can take some of these learnings today that we've talked about and apply them, I think -- I'm pretty optimistic in terms of what's possible here. This particular page here that we've been talking about for a little while has been quite good.

**Daniel Whitenack:** Yeah, I think it's a starting point.

**Chris Benson:** It is.

**Daniel Whitenack:** As I mentioned, we'll link to some of these resources in our show notes... So I encourage you - we're going to link to practical things. These aren't things that have been sponsored, and we're trying to sell something; these are links to what we've found to be practical in thinking about these topics. So check out the show notes, check out those links, and try some of these things. And we would love for you to come into our Slack channel, or our LinkedIn page, or Twitter, wherever you can find us and share some of the cool prompts that you've been working on, and what they're like, and what output you're getting. But yeah, this was useful for me to talk through with you, Chris. It was a good time.

**Chris Benson:** It was a good conversation. It's definitely one that I learned a lot on. Thanks for taking us through that.

**Daniel Whitenack:** Yeah. Well, we'll see you soon. Who knows what the AI world will be like next week, but we'll still be here...

**Chris Benson:** We'll still be here... Talk to you later.