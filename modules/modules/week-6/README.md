# Week 6: Conversational Interfaces

## Making Effective Conversations

While some of the rules of "good" and "bad" conversation apply to dialogicly scripted bots, some of the others do not. For example, while we might want a bot to be polite to us by saying "please" and "thank you" as these are part of the scripts that we expect in social exchanges. However, when we are enaging a chatbot to see if our internet service is working, or to schedule an appointment, we are probably less interested in talking about "how our day is going." 

We'll get some language for thinking about the specific kinds of conversational "moves" we want to design into our bots. Specifically, we'll be thinking about our conversations along the "relational" and "instrumental" goals of commuication. 



### Instrumental Communication

> "Hey did you get the notes from our last meeting?"

Some of the reasons that we communicate with one another are instrumental. We have to exchange messages in order to get dinner cooked, to complete a long drawn out project at work, or even to successfully negotiate a crowded city bus. Such communication exists where the communication is attempting to get somethign done. Communication, in other words, is a _tool_. 

{% hint style="info" %}
Instrumental communication is communication work meant to accomplish external goals, meaning that our conversation with someone is a _means to an end_. I am talking to so and so in order to get a better grade in the course. I am phoning the call center to get my computer to work. 
{% endhint %}

Everyone has differnet thresholds of patience, but suffice it to say that in some contexts there just simply isn't time for "dilly dallying," or getting "off track." These are moments where the instrumental goals of the situation are suffering because the messaging is not being specifically applied to the instrumental goal. 

> "We're supposed to be getting this done, not talking about our weekend."

On the other hand, there is certainly the phenomenon of people feeling negatively about interactions, or perhaps even feeling outright "used." This has to do with a balancing act that has to happen between instrumental communication and our other category, relational communication. 



### Relational Communication 

> "How was your weekend?"

In contrast to instrumental communication, we humans also yearn for connection, affirmation, and respect. These are what we are talking about when we say there are relational goals in communication. 

{% hint style="info" %}
**Relational communication** is communication work meant to convey appreciation and positive regard to accomplish intrinsic goals, meaning that we treat people as _ends_ in and of themselves. 
{% endhint %}

> "Wow, you sound like you know how to have fun!"

Too much emphasis on the instrumental and we risk our users feeling slighted. Too much emphasis on the relational and we risk our users feeling annoyed. This a paradoxical tension that we must traverse in our bot designs. 



### The Paradox of Instrumental/Relational Communication 

For us and our making of bots, it is extremely important to remember that there are multiple ways to say the same thing. That is, no matter the instrumental goal, there are certainly ways to include messaging that does not lose site of one's relational goals. 

At the other end of that claim, is the idea that if a bot is too trivial or jokey \(depending on the context\) our users will probably be more annoyed than pleased. Hence the paradox of relational/instrumental communication: that we yearn for relational connection, but, in tension with that is that we also want to get things done. 

We like small talk but not too much. And, we like getting things done, but we also like to be appreciated and respected. Check out Purna Virji's presentation on conversational interfaces. She doesn't use our language of instrumental/relational directly. She is, however, helping us think about the kinds of chit chat that we want, as we accomplish our goals. 



#### The Four C's of Designing Conversational AI

{% embed url="https://youtu.be/nCH8b1pUyG4" %}



Continuing to build on our work from last week, we'll extend our persona planning into some conversation trees. But, first we'll need to think about the kinds of instrumental and relational goals that are appropriate to our particular context and purpose, and make sure that they are a good balance. Let's revisit our examples from last week. 



### Automating our Conversations 

#### Health Care \(Specifically about Cancer\) 

| Context & Purpose | Appropriate Characteristics | Register | Examples of Communication |
| :--- | :--- | :--- | :--- |
| Health Care/To Answer Questions about a Particular Facility | Capable; Optimistic;  Dutiful | High | "I can absolutely help you with that"; "Let's see what we can come up with"; "I am here to help."  |



So now lets continue our planning along the lines of relational/instrumental goals. 

| Type of Goal | Goal\(s\) | Examples of Phrasing |
| :--- | :--- | :--- |
| Instrumental | Learning more about the facility; Scheduling visits to the facility.  | "I can absolutely help you with that"; "Let's see what we can come up with." |
| Relational  | Making sure that people know that they are valued as people \(not just patients, or paychecks\).  | "I am here to help."  |

Because this bot is being designed to help facilitate information sharing and scheduling for the facility, I want it to focus more on the instrumental goals. 

However, I did notice that the original "I am here to help phrasing" might actually be misconstrued more as instrumental communication \(e.g., "I am here to help you find info"\) rather than relational \(e.g., "I am here for you emotionally"\). While I don't want to get into the weird space of having my bot act as if it is a true social entity \(that has capacity for empathy\), I do want to re-word to sound more relational in the sense that the organization is "speaking through" the bot. As such, I'll update as: 

> "We care about you, and are eager to help you anyway that we can."

You can imagine how these phrasings would be different for promoting a video game or some other instrumental goal that deserves less reverence. 



### Closed and Open-Ended Interfaces

Believe it or not, what we are designing in this class are interfaces. Only instead of designing thoughtful arrangements of icons on a webpage, we are designing the thoughtful flows of questions and response paths. A useful distinction that helps us design these interfaces we borrow from the area of survey design: closed and open-ended questions. 



#### Close-Ended Questions

When someone is given a closed-ended query they are usually being asked a question with a finite, often one-word answer. 

> Bot: How old are you? 
>
> User: 25
>
> Bot: Are you a member of this bank? 
>
> User: No.

This kind of information is useful to us as it helps us serve the user. The way this will translate into our conversational interface designs will be "arrays" of choice, built out of possibliities of closed-ended answer. 

Our interfaces will largely be composed of closed-ended questions. 



#### Open-Ended Questions

Open-ended questions leave it to the responder to choose how to answer. 

> Bot: What is your favorite movie? 
>
> User: Jurassic Park
>
> Bot: What would you describe as the ideal vacation? 
>
> User: Being at home with my cat and dog.

This kind of information is difficult to deal with in an automated fashion \(though in our reading for this week, we will learn little bit more about natural language processing as a means for doing so\). But, because it is so  natural, this kind of information is also desirable in conversational interfaces.  

Just like any other kind of professional writing, crafting conversational interfaces happens through reiteration within a feedback loop between you \(the author\) and the user \(the readers\). As such, we'll be taking what we built last week and improving it through that process. 

## This Week's Readings and Assignments

#### Readings

**Chapters 7 and 16 of** [_**Designing Bots**_](file:///autocomm/~/edit/drafts/-LO_Kxqem2Og_1VNlU53/syllabus/syllabus-1/course-text)**.** Think about the conversation you will script. What are your relational and instrumental goals? Will your interface incorporate open-ended or closed questions? 



#### Assignments

Building from our [Chatbot Persona](../week-5/chatbot-persona.md), we will **make a** [**Chatbot Prototype**](chatbot-prototype.md)\*\*\*\*



#### Further Reading

{% embed url="https://chatbot.fail" %}

