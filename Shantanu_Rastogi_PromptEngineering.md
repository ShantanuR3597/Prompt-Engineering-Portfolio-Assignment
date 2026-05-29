# Prompt Engineering Portfolio
Name: Shantanu Rastogi
Date: 2nd June 2026
LLM Used: Gemini 3.5 Pro


## Part 1: Prompt Design & Iteration

### 1.1 Scenario A: Technical Explanation

#### Version 1 Prompt

Explain neural networks to a 10-year-old.

#### Version 1 Output

Imagine you’re trying to teach a computer how to recognize a picture of a cat.

Normally, computers need very specific rules, like "if the picture has a triangle on top, it's an ear." But cats come in all shapes, sizes, and colors, and sometimes their ears are flat or hidden! It’s too hard to write a rule for every single cat in the world.

Instead of giving the computer strict rules, we can build a **neural network**. A neural network is a special kind of computer program inspired by how your own brain works.

Here is how it works, using a team of tiny detectives as an example:

### The Team of Detectives

Think of a neural network as a giant stadium filled with thousands of tiny detectives. They are organized into different rows.

* **The Front Row (The Observers):** These detectives only look at tiny pieces of the picture. One might look at a single pixel and say, "I see black!" Another might say, "I see orange!" They pass their clues to the row behind them.
* **The Middle Rows (The Thinkers):** This is where the magic happens. These detectives take the clues from the front row and put them together. One detective might say, "Black and orange together? That might be a stripe!" Another might say, "I see a curve that looks like a tail." They pass *their* bigger clues to the next row. There can be lots of middle rows!
* **The Back Row (The Bosses):** These detectives take all the big clues—stripes, tails, pointy ears—and make the final guess. They shout, "It’s a tiger!" or "It’s a cat!"

### How Do They Learn?

At first, the detectives are terrible at their jobs. They just guess randomly.

But every time they guess, you tell them the right answer. If they see a picture of a cat and guess "dog," you say, "Nope, that was a cat!"

The detectives then talk to each other and say, "Okay, the clues that led us to 'dog' were wrong. Let's not listen to those clues as much next time."

If they get it right, they say, "Great job! Let's trust those specific clues even more next time."

By looking at thousands of pictures of cats and making thousands of mistakes, the team eventually figures out exactly which clues are important. They *learn* from experience, just like you do when you practice riding a bike!

---

Let's try a simple interactive version. Instead of a picture, let's give the network some clues about an animal and watch how the "detectives" pass the signals to make a guess!

---

#### Version 2 Prompt

Explain neural networks to a 10-year-old using simple language and a real-world example. Avoid technical jargon and keep the explanation under 200 words.

#### Version 2 Output

### The Detective Team

Imagine a neural network as a stadium filled with a team of tiny detectives trying to guess a mystery animal.

* **The Front Row (Clue Finders):** These detectives look for small details: "Does it have fur?" or "Does it bark?" They pass their clues backward.
* **The Middle Row (Pattern Matchers):** These detectives combine the clues: "Fur plus barking usually means it's a dog!"
* **The Boss (The Output):** The final detective listens to all the patterns and shouts the final guess: "It's a dog!"

At first, they guess randomly. If they see a dog and guess "bird," you tell them they are wrong. The detectives talk to each other and say, "Oops! Let’s not trust those specific clues next time."

By practicing and making mistakes on thousands of pictures, they figure out exactly which clues matter most. They learn from experience, just like you do when you practice riding a bike!

---

#### Version 3 Prompt

You are an expert elementary school teacher.

A 10-year-old student is curious about how artificial intelligence works.

Explain neural networks using:

* Simple everyday language
* A relatable analogy
* A step-by-step explanation
* One short example
* A fun conclusion

Keep the explanation engaging and under 250 words.

#### Version 3 Output

Imagine a neural network as a stadium filled with a team of tiny detectives trying to solve a mystery, like guessing an animal in a picture!

Here is how they work together step-by-step:

1. **Clue Finders (The Front Row):** These detectives look at tiny details. One asks, "Does it have fur?" Another checks, "Does it bark?"
2. **Pattern Matchers (The Middle Row):** The front row passes notes backward. The middle detectives put the clues together: "Aha! Fur plus barking usually means a dog!"
3. **The Boss (The Back Row):** The final detective listens to the patterns and shouts the final guess: "It's a dog!"

**For example:** At first, they guess randomly. If they see a dog and guess "bird," you tell them they are wrong. The detectives talk to each other and say, "Oops! Let’s not trust those clues next time." By practicing on thousands of pictures, they figure out exactly which clues matter most.

Just like you learn to ride a bike by making mistakes and trying again, the computer learns from experience! Your own brain is actually a giant, super-smart neural network, making you the ultimate learning machine!

---

### 1.1 Scenario B: Professional Email

#### Version 1 Prompt

Write an email declining a job offer.

#### Version 1 Output

Subject: Job Offer - **[Your Name]**

Dear **[Hiring Manager Name]**,

Thank you very much for offering me the position of **[Job Title]** at **[Company Name]**. I truly appreciate the time you and your team took to interview me and share more about the work you are doing.

After careful consideration, I must politely decline the offer. While this was a difficult decision, I have realized that this opportunity is not the right fit for my current career goals.

It was a pleasure meeting you and learning about **[Company Name]**. I wish you and the team all the best in finding the ideal candidate for this position, and I hope our paths cross again in the future.

Sincerely,

**[Your Name]**
**[Your Phone Number]**
**[Your Email Address]**

---

#### Version 2 Prompt

Write a professional email declining a job offer while expressing gratitude for the opportunity and maintaining a positive relationship with the company.

#### Version 2 Output

Subject: Update regarding the **[Job Title]** position - **[Your Name]**

Dear **[Hiring Manager Name]**,

Thank you so much for offering me the **[Job Title]** position at **[Company Name]**. I greatly appreciated the opportunity to meet with you and your team, and I enjoyed learning more about the role and the company's vision.

After careful consideration, I am writing to let you know that I will not be accepting the offer. While it was a difficult decision, I have realized that this opportunity does not completely align with my current career goals.

It was a pleasure getting to know you during the interview process, and I was particularly impressed by **[optional: mention something specific you liked about the company or team, e.g., the team's collaborative culture]**.

I wish you and the rest of the team all the best in finding the ideal candidate for this position, and I hope we have the chance to cross paths again in the future.

Sincerely,

**[Your Name]**

**[Your LinkedIn Profile URL - Optional]**

**[Your Phone Number]**

**[Your Email Address]**

---

#### Version 3 Prompt

You are a professional career advisor.

Write a polite and professional email declining a job offer.

Context:

* The candidate has accepted another opportunity.
* They genuinely appreciate the company's time and effort.
* They would like to stay connected for future opportunities.

Requirements:

* Professional tone
* Express gratitude
* Clearly decline the offer
* Maintain goodwill
* Keep it between 150 and 200 words

#### Version 3 Output

Subject: Job Offer - **[Your Name]**

Dear **[Hiring Manager Name]**,

Thank you so much for offering me the position of **[Job Title]** at **[Company Name]**. I sincerely appreciate the time you and your team spent speaking with me and sharing insights about the company's exciting goals. It was a pleasure learning about the impactful work your team is doing.

After careful consideration, I am writing to let you know that I must politely decline this offer. I have recently decided to accept another opportunity that closely aligns with the specific direction I am taking in my career at this time. This was a difficult decision, as I was highly impressed by everyone I met during the interview process.

I am truly grateful for the opportunity and the generous offer. I would love to stay connected and follow your team's success. Please feel free to reach out if our paths cross again in the future.

I wish you and the entire team at **[Company Name]** the absolute best in finding the ideal candidate for this role.

Sincerely,

**[Your Name]**
**[Your LinkedIn Profile URL]**
**[Your Phone Number]**

---

### 1.1 Scenario C: Creative Content

#### Version 1 Prompt

Create a marketing tagline for an eco-friendly water bottle brand.

#### Version 1 Output

Here is a selection of marketing taglines for an eco-friendly water bottle brand, categorized by the specific "vibe" or messaging angle you might want to project:

**Action-Oriented & Impactful**

* Hydrate with purpose.
* Save the planet, one sip at a time.
* Carry the change.
* Drink sustainably. Live beautifully.

**Clever & Playful**

* Make waves, not waste.
* Thirst for a better world.
* Un-bottle the future.
* Zero waste. Infinite taste.

**Minimalist & Pure**

* Pure water. Clean earth.
* Hydration without harm.
* Simply sustainable.
* Refresh naturally.

**Focus on Longevity & Reusability**

* Your daily drop of good.
* The last bottle you'll ever need.
* Refill. Rejoice. Repeat.
* Designed for you, mindful of the Earth.

---

> **Tip for choosing:** The best tagline depends entirely on your target audience. If your brand is outdoorsy and adventurous, lean towards the action-oriented options. If it's a sleek, modern lifestyle brand, the minimalist or longevity-focused taglines will resonate best!

---

#### Version 2 Prompt

Create 10 marketing taglines for an eco-friendly water bottle brand. The taglines should be memorable, modern, and emphasize sustainability.

#### Version 2 Output

Here are 10 memorable, modern taglines for an eco-friendly water bottle brand, emphasizing sustainability:

1. **Refill the future.**
A short, punchy, and modern tagline that connects the simple act of refilling a bottle to creating a better tomorrow.
2. **Leave no trace, just taste.**
Plays on the popular outdoor mantra of "leave no trace" while ensuring the consumer that the quality of their water remains pure.
3. **Unbottle your impact.**
A clever play on words that encourages users to think about the positive environmental difference they make by avoiding single-use plastics.
4. **Zero waste. 100% you.**
Appeals to the modern, lifestyle-focused consumer by blending environmental responsibility with personal identity.
5. **Your thirst, earth first.**
A catchy, rhythmic tagline that establishes a clear hierarchy of values: keeping you hydrated while prioritizing the planet.
6. **Refresh yourself. Restore the planet.**
Uses balanced phrasing to highlight the dual benefit of using the product—it's good for the user and good for the environment.
7. **Clear water, clean conscience.**
A sleek, minimalist tagline that speaks to the emotional reward of making an eco-friendly purchasing decision.
8. **Drink deeply. Step lightly.**
Evokes a sense of mindfulness, contrasting the act of staying fully hydrated with leaving a minimal carbon footprint.
9. **The planet's favorite way to hydrate.**
A confident, slightly playful statement that positions your brand as the ultimate standard in sustainable drinkware.
10. **Hydration without the footprint.**
Straightforward and impactful, immediately letting the consumer know exactly what the brand stands for.

---

#### Version 3 Prompt

You are an award-winning advertising copywriter.

Create 10 creative marketing taglines for a new eco-friendly water bottle brand.

Brand values:

* Sustainability
* Reusability
* Environmental responsibility
* Modern lifestyle

Target audience:

* Young professionals
* College students
* Environmentally conscious consumers

Requirements:

* Short and memorable
* Emotionally engaging
* Unique and brandable
* Avoid clichés

#### Version 3 Output

Here are 10 creative, modern taglines crafted for your eco-friendly water bottle brand. As an advertising copywriter, I designed these to avoid the tired "go green" clichés, focusing instead on sleek, lifestyle-driven messaging that resonates with young professionals and conscious consumers.

**The Taglines**

**1. Forever yours. Never the ocean's.**

> **Why it works:** It strikes a deep emotional chord. It juxtaposes the personal, premium nature of the bottle with a stark environmental reality, making the consumer feel like a protector of the planet.

**2. Fluid living. Fixed values.**

> **Why it works:** Perfectly tailored for young professionals. It acknowledges their dynamic, on-the-go lifestyle ("fluid") while anchoring them to their core ethical beliefs ("fixed values").

**3. Defy the disposable.**

> **Why it works:** It turns sustainability into a quiet act of rebellion. It’s short, punchy, and highly brandable, framing reusability as a powerful choice rather than a chore.

**4. A habit worth holding.**

> **Why it works:** This tagline focuses on behavior change. It plays on the physical act of holding the bottle while elevating hydration to an intentional, positive daily routine.

**5. Impact, bottled.**

> **Why it works:** Minimalist and incredibly confident. It tells the consumer that their purchase isn't just about water; it's a tangible, portable piece of environmental change.

**6. Progress in every pour.**

> **Why it works:** Forward-looking and optimistic. It replaces the guilt often associated with environmental marketing with a sense of active, continuous improvement.

**7. Hydrate with intent.**

> **Why it works:** It taps into the modern wellness and mindfulness trends popular among college students and young adults. It elevates drinking water from a passive need to a conscious, eco-friendly decision.

**8. Outlast the plastic.**

> **Why it works:** A subtle, clever nod to the durability of the product and its environmental mission. It positions your brand as the ultimate, long-term solution to single-use culture.

**9. Style that sustains.**

> **Why it works:** An excellent bridge between aesthetic appeal and eco-consciousness. It assures the lifestyle-focused consumer that they don't have to sacrifice modern design for environmental responsibility.

**10. Earth-aligned. Life-designed.**

> **Why it works:** A rhythmic, poetic tagline that covers both bases perfectly. It shows that the product is made with the planet in mind, but ergonomically and aesthetically crafted for the user's daily life.

---

## 1.2 Iteration Documentation

### Scenario A Iteration Table

| Version | Prompt                                                                       | What Changed                                                      | Why This Improved the Output                                                              |
| ------- | ---------------------------------------------------------------------------- | ----------------------------------------------------------------- | ----------------------------------------------------------------------------------------- |
| V1      | Explain neural networks to a 10-year-old.                                    | N/A                                                               | N/A                                                                                       |
| V2      | Added simple language, real-world example, and word limit.                   | Audience-specific instructions and length constraints were added. | The explanation became shorter, clearer, and easier for a child to understand.            |
| V3      | Added role assignment, context, structure, example, and engaging conclusion. | Introduced role-based prompting and detailed output requirements. | The explanation became more organized, educational, and engaging for the target audience. |

### Scenario B Iteration Table

| Version | Prompt                                                                   | What Changed                                                           | Why This Improved the Output                                                                          |
| ------- | ------------------------------------------------------------------------ | ---------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------- |
| V1      | Write an email declining a job offer.                                    | N/A                                                                    | N/A                                                                                                   |
| V2      | Added gratitude and relationship-building requirements.                  | Included professionalism and future relationship goals.                | The email became more polished and professional.                                                      |
| V3      | Added career advisor role, candidate context, and specific requirements. | Included role assignment, detailed background, and output constraints. | The email became more realistic, personalized, and aligned with professional communication standards. |

### Scenario C Iteration Table

| Version | Prompt                                                                            | What Changed                                        | Why This Improved the Output                                      |
| ------- | --------------------------------------------------------------------------------- | --------------------------------------------------- | ----------------------------------------------------------------- |
| V1      | Create a marketing tagline for an eco-friendly water bottle brand.                | N/A                                                 | N/A                                                               |
| V2      | Requested 10 taglines and specified modern, sustainable messaging.                | Added quantity and marketing direction.             | Generated more focused and relevant taglines.                     |
| V3      | Added copywriter role, brand values, target audience, and creativity constraints. | Included detailed context and audience information. | Produced more original, audience-focused, and brandable taglines. |

---

## 1.3 Role and Context Analysis

Role assignment and context setting significantly improved the quality of the generated outputs. In Scenario A, assigning the model the role of an elementary school teacher helped produce an explanation that was more engaging and appropriate for a 10-year-old audience. In Scenario B, providing the context that the candidate had accepted another opportunity resulted in a more realistic and professional email. In Scenario C, specifying the role of an advertising copywriter along with target audience and brand values generated more creative and relevant marketing taglines. Overall, adding role and context helped the model better understand the intended audience, purpose, and desired outcome.


## Part 2: Temperature & Parameter Control

### 2.1 Temperature Experimentation

#### Chosen Task

Creating a short story opening (2–3 sentences)

---

### Base Prompt

Write a 2-3 sentence opening for a fantasy story about a mysterious door that appears in a forest.

---

### Low Temperature (0.0 - 0.3)

#### Prompt Used

Be precise and consistent.

Write a 2-3 sentence opening for a fantasy story about a mysterious door that appears in a forest.

#### Output

The ancient oaks of the deep woods gave way not to a clearing, but to a freestanding door of polished mahogany rising straight from the moss. Its brass knob gleamed untarnished in the dappled sunlight, completely defying the damp decay of the surrounding forest. When Elara tentatively reached for the handle, the wood hummed beneath her fingertips with a low, vibrating energy that tasted of ozone and forgotten realms.

---

### Medium Temperature (0.6 - 0.8)

#### Prompt Used

Write a 2-3 sentence opening for a fantasy story about a mysterious door that appears in a forest.

#### Output

It hadn't been there yesterday, a solitary door of wrought iron and frosted glass standing entirely unsupported among the ancient pines. Wisps of violet mist curled from its hinges, defying the stiff autumn breeze that rustled the dead leaves below. As Kael stepped closer, the glass frosted over with intricate, glowing runes that pulsed in perfect rhythm with his racing heart.

---

### High Temperature (1.0 - 1.5)

#### Prompt Used

Be creative and explore diverse ideas.

Write a 2-3 sentence opening for a fantasy story about a mysterious door that appears in a forest.

#### Output

Between the twisted roots of the elderwood stood a freestanding frame of petrified wood, its interior holding not the forest behind it, but the swirling, vibrant expanse of a starlit nebula. There was no physical door to push open, only a threshold of chilling gravity that smelled faintly of burning sugar and winter frost. When Lyra tossed a fallen acorn into the cosmic mass, it didn't hit the dirt, but drifted slowly upward into the glittering abyss.

---

### Comparison Table

| Temperature      | Characteristics Observed                                                               | Creativity Level |
| ---------------- | -------------------------------------------------------------------------------------- | ---------------- |
| Low (0.0–0.3)    | Clear, focused, logical description of a mysterious door with limited fantasy elements | Low              |
| Medium (0.6–0.8) | Balanced mix of mystery, fantasy, and descriptive imagery                              | Medium           |
| High (1.0–1.5)   | Highly imaginative concepts, unusual details, and unpredictable storytelling elements  | High             |

---

## 2.2 Analysis & Recommendations

Low temperature is most useful when accuracy, consistency, and predictability are important. Two examples include generating technical documentation and drafting professional business communications where factual correctness matters more than creativity.

High temperature is most useful for creative tasks that benefit from originality and diverse ideas. Two examples include writing fiction stories and brainstorming marketing campaigns where unique and unexpected outputs are valuable.

For this task, the high temperature setting produced the most interesting result because it generated highly imaginative concepts such as a doorway containing a starlit nebula and an acorn floating upward into space. While the low and medium temperature outputs were strong and coherent, the high temperature output was the most memorable and demonstrated the greatest level of creativity. Therefore, high temperature was the most effective choice for a fantasy story opening.

















