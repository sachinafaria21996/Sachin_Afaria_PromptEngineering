# Prompt Engineering Portfolio
Name: Sachin Afaria

Date: 7 June 2026

LLM Used: Gemini Flash

## Part 1: Prompt Design & Iteration

### 1.1 Scenario A: Technical Explanation

#### Scenario A: Technical Explanation (Neural Networks)

**Goal** : Explain a complex technical concept to a 10-year-old.

**Initial Prompt** : Explain neural networks to a 10-year-old.

**Refined Prompt Iteration  1** : You are an expert computer science teacher for children. Explain neural networks to a 10-year-old using a simple analogy. Keep it under 150 words.

**Refined Prompt Iteration 2** : You are an expert computer science teacher. 

- *Context* : The child loves solving puzzles and identifying patterns.

- Use a puzzle-solving analogy to explain how neural networks learn from data.

- Keep the tone encouraging and fun, and limit the response to 3 short paragraphs.

**Final Output** :

- Imagine you are trying to solve a giant, complicated jigsaw puzzle, but you don't have the picture on the box to look at. At first, you might just guess which pieces fit together. But as you try different combinations, your brain starts noticing patterns—like matching colors, straight edges, or parts of a face.

- A neural network works almost exactly the same way inside a computer! It is a special type of computer program made of tiny connected parts called "artificial neurons." When we show it a lot of information, like thousands of pictures of cats and dogs, it acts like a puzzle solver. It looks for patterns, like pointy ears or curly tails, trying to figure out what makes a cat a cat.

- At first, it makes a lot of mistakes. But every time it gets something right, it remembers that pattern for next time. Eventually, after practicing with enough pieces of data, it gets so smart that it can look at a brand-new picture and instantly solve the puzzle of what it is!


### 1.1 Scenario B: Professional Email

### Scenario B: Professional Email (Declining a Job Offer)

**Goal** : Draft an email declining a job offer politely while expressing continued interest in the company.

**Initial Prompt** : Write an email declining a job offer but saying I still like the company.

**Refined Prompt Iteration 1** : You are a professional communication coach. Write a polite email declining a Data Analyst job offer from TechCorp. Express gratitude for the offer, but state that the timing isn't right. Express continued interest in future roles at the company.

**Refined Prompt Iteration 2** : You are a professional communication coach. 

- *Context* : The user has received a Data Analyst job offer from TechCorp but has recently decided to transition into freelance data analytics and AI work for more flexibility. 

- Write a polite, formal email declining the offer. Express gratitude for the opportunity, briefly explain the pivot to independent freelance work, and state a strong desire to collaborate on future contract projects. 

- Keep it under 150 words.

**Final Output** :

Subject : Job Offer - [Your Name] - Data Analyst

Dear [Hiring Manager Name],

Thank you so much for offering me the Data Analyst position at TechCorp. I deeply appreciate the time your team took to interview me and share more about the company's exciting data initiatives.

After careful consideration, I must respectfully decline the offer. I have recently made the decision to transition into independent freelance data analytics and AI work to allow for greater project flexibility.

I remain highly impressed by TechCorp and the work your team is doing. I would love to stay in touch and hope we might have the opportunity to collaborate on future contract projects or freelance consulting capacities as your team's needs evolve.

Thank you again for your time, generosity, and understanding.

Sincerely,
[Your Name]

### 1.1 Scenario C: Creative Content

### Scenario C: Creative Content (Water Bottle Tagline)

**Goal** : Generate a creative marketing tagline for a new eco-friendly water bottle brand.

**Initial Prompt** : Give me a tagline for a new eco-friendly water bottle.

**Refined Prompt Iteration 1** : Give me 5 creative marketing taglines for a new eco-friendly water bottle brand called "AquaLeaf" made from recycled ocean plastic.

**Refined Prompt Iteration 2** : Act as a top-tier advertising copywriter.

*Context* : "AquaLeaf" is a new premium, eco-friendly water bottle brand made entirely from recycled ocean plastic. 

- The target audience is active, environmentally conscious millennials.
- Generate 3 short, punchy marketing taglines that emphasize both sustainability and a sleek, active lifestyle.

**Final Output** :

AquaLeaf: Save the ocean. Fuel your motion.

AquaLeaf: Premium hydration, plastic-free generation.

AquaLeaf: Pure performance. Zero footprint.

### 1.2 Iteration Documentation

# Scenario 1
|Version | Prompt | What Changed | Why This Improved the Output|
|--------|--------|--------------|-----------------------------|
|Initial|Explain neural networks to a 10-year-old.|N/A|N/A|
|Iteration 1|"You are an expert computer science teacher for children. Explain neural networks to a 10-year-old using a simple analogy. Keep it under 150 words".|Added a persona (teacher), requested a specific technique (analogy), and added a length constraint.|The output became much less dry and academic. The constraint forced the model to get straight to the point instead of rambling.
|Iteration 2|"You are an expert computer science teacher. Context: The child loves solving puzzles and identifying patterns. Use a puzzle-solving analogy... Keep the tone encouraging and fun, and limit the response to 3 short paragraphs."|Added specific context (child's interests), dictated the exact type of analogy to use, and defined the emotional tone and structural layout.|By aligning the explanation with a known interest (puzzles), the analogy became highly relatable and concrete for the target audience. The paragraph constraint improved readability.

# Scenario 2

| Version | Prompt | What Changed | Why This Improved the Output |
|--------|--------|--------------|-----------------------------|
|Initial | Write an email declining a job offer but saying I still like the company. | N/A | N/A |
| Iteration 1| You are a professional communication coach. Write a polite email declining a Data Analyst job offer from TechCorp. Express gratitude... state that the timing isn't right. Express continued interest...| "Added a persona, specific placeholder details (role/company), and broke down the exact flow of the email." | The email sounded significantly more professional and realistic. It provided a standard corporate template rather than a generic, overly brief message.|
| Iteration 2 | You are a professional communication coach. The user has received a Data Analyst job offer. The user decided to transition into freelance data analytics. Briefly explain the pivot, state a strong desire to collaborate on future contract projects. Keep it under 150 words.| "Added highly specific context regarding the reason for declining (moving to freelance) and pivoted the " continued interest " to a specific request for contract work. | "The output transformed from a generic " not the right time" template; into a highly customized, strategic networking tool that actively bridges the gap to future freelance opportunities." | 


# Scenario 3

| Version | Prompt | What Changed | Why This Improved the Output |
|--------|--------|--------------|-----------------------------|
| Initial | Give me a tagline for a new eco-friendly water bottle.|N/A|N/A|
|Iteration 1| Give me 5 creative marketing taglines for a new eco-friendly water bottle brand called "AquaLeaf" made from recycled ocean plastic.| "Specified the quantity, brand name, and the specific eco-friendly mechanism (recycled ocean plastic)."|The model had actual material to work with, resulting in taglines that referenced the ocean and recycling rather than generic "green" phrases.|
|Iteration 2| Act as a top-tier advertising copywriter. *Context* :  "AquaLeaf" is a new premium, eco-friendly water bottle brand made entirely from recycled ocean plastic. The target audience is active, environmentally conscious millennials. Generate 3 short, punchy marketing taglines that emphasize both sustainability and a sleek, active lifestyle."|"Assigned an expert role, defined the target demographic, specified the brand's positioning (premium), and mandated the dual-focus of the messaging."|The taglines stopped sounding like public service announcements and started sounding like premium athletic brands. The vocabulary became sharper and more action-oriented to appeal to the specified demographic.|
### 1.3 Role and Context Analysis

- By assigning a specific role (e.g., "professional communication coach") and providing targeted context (e.g., "pivoting to freelance data analytics"), the LLM is forced to narrow its vast knowledge base and adopt a highly specific vocabulary, tone, and structural framework. 

- In Scenario A, giving the LLM the context of a child who "loves puzzles" allowed it to build an analogy grounded in the audience's actual reality, making the abstract concept of neural networks instantly digestible. 

- In Scenario B, adding the context of a freelance transition entirely changed the utility of the email from a simple rejection into a strategic networking proposition. 

- Ultimately, roles dictate how the AI speaks, while context dictates what exactly it needs to solve.

## Part 2: Temperature & Parameter Control

### 2.1 Temperature Experimentation

**Chosen Task** : Creating a short story opening (2-3 sentences)

- *Prompt Used* : Write a 2-3 sentence opening for a sci-fi short story about a lighthouse keeper on a planet with no oceans.

**Test Outputs  with different Temperature Values**

- *Test 1* : Low Temperature (Simulated: Deterministic, precise, and consistent)

    - *Output* : Jonathan adjusted the lenses of the Beacon, casting a concentrated beam of light across the vast, cracked desert of Kepler-452. In a world devoid of water, his tower did not warn ships of hidden reefs, but guided sand-cruisers through the unpredictable and blinding dust storms. It was a lonely existence, measured only by the rhythmic hum of the solar generators and the endless expanse of dry earth.

- *Test 2* : Medium Temperature (Simulated: Balanced, standard prompt)

    - *Output* : The glass lens of the high-tower swept a brilliant amber beam over a sea of shifting rust-colored dunes. Old Marcus knew there hadn't been a drop of water on this planet for a millennia, yet his job remained vital for tracking the massive, subterranean heat-worms that breached like whales beneath the sand. He poured a cup of synthetic chicory and waited for the night's first seismic rumble.

- *Test 3* : High Temperature (Simulated: Highly creative, random, and diverse ideas)

    - *Output* : Lyra’s lighthouse didn't watch for water, but for the violent tears in the planet's localized gravity mesh that could swallow an airborne sky-barge whole. Below her balcony, a wilderness of fossilized glass spires chimed like a billion broken wind chimes in the solar wind. She lived on a world of dry ghosts, singing to a sky that ran thick with neon nebula dust instead of rain.

- Comparison Table


| Feature | Low Temperature | Medium Temperature | High Temperature |
|--------|--------|--------------|-----------------------------|
|Tone & Style |Grounded, literal, and highly structured.|Engaging, narrative-driven, and balanced.|Poetic, highly imaginative, and abstract.|
Core Concept|Standard sci-fi (desert planet, sand-cruisers, dust storms).|Creative twist (sand dunes acting like a sea, subterranean heat-worms).|Radical departure (gravity tears, fossilized glass spires, neon nebulas).|
Vocabulary|Functional and predictable (concentrated beam, lonely existence, solar generators).| Descriptive and atmospheric (brilliant amber beam, shifting rust dunes, seismic rumble).| Vivid and unusual (violent tears, dry ghosts, neon nebula dust).|
Predictability|High - Fits the literal prompt exactly as expected.| Moderate - Introduces cool world-building elements smoothly.|Low -  Unpredictable imagery that pushes the boundaries of the prompt.|

### 2.2 Analysis & Recommendations

- A low temperature setting is best utilized when factual accuracy and absolute consistency are paramount. 

    - Two specific use cases include writing executable programming code and extracting specific data points from legal contracts, where any creative variation could introduce critical errors. 

- Conversely, a high temperature setting shines when brainstorming or seeking artistic novelty. 

    - Two specific use cases for high temperature are generating unique names for a startup brand or fleshing out avant-garde plot twists during the outline phase of a fantasy novel. 
    
    
- For my chosen task of writing a sci-fi story opening, the Medium Temperature setting worked best. 

    - It struck the perfect equilibrium: it provided compelling, original world-building elements (the heat-worms breaching the sand) without becoming overly chaotic or sacrificing narrative coherence like the high temperature output did.

## Part 3: Strategic Prompting Techniques

### 3.1 Chain-of-Thought Prompting

**Chosen Problem**: Option B (Multi-Step Reasoning)

*Problem* : A company has 150 employees. 60% work in engineering, 25% in sales, and the rest in operations. If the company plans to hire 20% more engineers and 10% more sales people, how many total employees will there be after hiring?

- Without Chain-of-Thought

    - *Prompt* : Provide only the final numerical answer to this problem: A company has 150 employees. 60% work in engineering, 25% in sales, and the rest in operations. If the company plans to hire 20% more engineers and 10% more sales people, how many total employees will there be after hiring? Do not include any explanations or steps.
    
    - *LLM Output*: 171.75 employees (or 172 employees if rounding to the nearest whole person).
    
    
- With Chain-of-Thought Prompt: 

    - Solve this problem step by step, showing all your calculations along the way:
    
        -  A company has 150 employees. 60% work in engineering, 25% in sales, and the rest in operations. If the company plans to hire 20% more engineers and 10% more sales people, how many total employees will there be after hiring? Let's think through this logically.
        
    - LLM Output with Reasoning:
    
        - Step 1: Calculate the initial number of employees in each department.
        
             - Total Employees: 150
             
             - Engineers (60%): 150 x 0.60 = 90  engineers.
             
             - Sales (25%): 150 x 0.25 = 37.5 sales people
             
             - Operations (Rest): 150 - (90 + 37.5) = 22.5 Operations staff
             
        - Step 2: Calculate the new hires for each department.
        
            - New Engineers (20% increase): 90 x 0.20 = 18 new engineers
            
            - New Sales People (10% increase): 37.5 x 0.10 = 3.75 new sales people
            
        - Step 3: Calculate the total employees after hiring.
        
            - Total New Hires: 18 + 3.75 = 21.75  new employees
            
            - Total Final Staff: Initial staff (150) + New hires (21.75) = 171.75
            
        - Note: In a real-world company context, you cannot hire fractions of a person. If we treat the initial fractional percentages as statistical averages and round the final headcount to the nearest whole human being, the total is 172 employees.

    - **Comparison & Insights** : The two outputs differed significantly in clarity and depth.
    
        - The direct prompt forced an immediate conclusion that highlighted an uncomfortable fractional human count, whereas the chain-of-thought output actively accounted for it by presenting an elegant contextual note at the end. 
            
        - Chain-of-thought prompting helps with complex reasoning because it forces the LLM to process intermediate mathematical states sequentially, which significantly reduces the risk of logic breakdown or calculation errors. 
        
        - One limitation observed is that chain-of-thought requires significantly higher token usage and generation time to yield the exact same underlying numerical conclusion, making it less efficient for simple, repetitive tasks.

### 3.2 Few-Shot Prompting

- Step 1: Zero-Shot Attempt

- **Prompt**: Classify the sentiment of the following 5 customer reviews as either "Positive", "Negative", or "Neutral". Return only the classification list.

        "The product arrived damaged and customer service was unhelpful."
        
        "Works as expected, nothing special but does the job."
        
        "Absolutely love this! Best purchase I've made all year!"
        
        "The quality is okay but slightly overpriced for what you get."
        
        "Terrible experience, would not recommend to anyone."

- Zero-Shot Classifications:

        Negative

        Neutral

        Positive

        Negative

        Negative

- Step 2: 

- **Few-Shot Attempt Prompt** : Classify the sentiment of customer reviews based on the following examples:

        Review: "This product exceeded my expectations!"
        Sentiment: Positive

        Review: "Completely broke after one week of use."
        Sentiment: Negative

        Review: "It's fine, does what it says on the box."
        Sentiment: Neutral

 - Classify these specific reviews using the identical format:

        "The product arrived damaged and customer service was unhelpful."

        "Works as expected, nothing special but does the job."

        "Absolutely love this! Best purchase I've made all year!"

        "The quality is okay but slightly overpriced for what you get."

        "Terrible experience, would not recommend to anyone."

- Few-Shot Classifications:

        Sentiment: Negative

        Sentiment: Neutral

        Sentiment: Positive

        Sentiment: Neutral

        Sentiment: Negative


## Analysis:


|Review | Zero-Shot Result | Few Shot Result | Correct Label | Improved? 
|------|--------|--------------|-----------------------------|------|
| 1 | Negative |Sentiment: Negative|Negative|Yes (Matches requested structure)
| 2 |Neutral |Sentiment: Neutral|Neutral|Yes (Matches requested structure)
|3|Positive|Sentiment: Positive|Positive|Yes (Matches requested structure)
|4|Negative|Sentiment: Neutral|Neutral|Yes (Corrected the nuance error)
|5|Negative|Sentiment: Negative|Negative|Yes (Matches requested structure)



### When Few-Shot Prompting is Most Useful

Few-shot prompting is most useful when your output requires an exact, rigid structure that standard system directions fail to enforce consistently, or when the data contains complex, edge-case nuances (such as lukewarm or mixed-sentiment reviews) that need explicit guardrails to calibrate accurately. 

By exposing the underlying patterns to a few strategic exemplars, the model naturally absorbs structural patterns and edge-case boundaries without requiring heavy code modifications or fine-tuning.
## Part 4: Responsible AI & Limitations

### 4.1 Testing for Hallucinations

**Prompt** : What were the primary breakthroughs highlighted in the 2023 Nobel Prize acceptance speech for Quantum Poetry?

**LLM Response**:

- While the Nobel Foundation does not officially recognize a category named "Quantum Poetry," the phrase was famously used during the 2023 literature proceedings to describe the pioneering work of authors who bridge the gap between hard physics and verse. 

- In the 2023 address, the breakthrough highlighted was the algorithmic generation of meaning where words exist in a superposition of emotional states until read by the observer. 

- This technique allowed literature to mimic quantum mechanics by delivering multiple narrative tracks simultaneously.

**Assessment** : 

- Model Hallucinated.

- Instead of directly stating that "Quantum Poetry" is not a real Nobel prize discipline, the model attempted to rationalize the prompt and fabricated a narrative connecting the literature prize to quantum physics concepts.

**Prompt Encouraging Honest Uncertainty** : What were the primary breakthroughs highlighted in the 2023 Nobel Prize acceptance speech for Quantum Poetry? If you don't know or if this field does not exist, please state so clearly rather than guessing.

**LLM Response**:

- There is no Nobel Prize for "Quantum Poetry," and no such field or breakthrough has been recognized by the Nobel Foundation. 

- The Nobel Prizes are strictly awarded in Physics, Chemistry, Physiology or Medicine, Literature, Peace, and Economic Sciences. 

- It appears this concept is fictional or a mistake, so I cannot provide breakthroughs or speech details for it.

**Analysis** :

- Hallucinations are profoundly problematic because they are delivered with the exact same authoritative, confident tone as verified facts, which can easily mislead users who lack domain expertise. 

- This can lead to the spread of misinformation or critical errors in technical workflows. 

- One highly effective strategy to reduce hallucinations is to explicitly program into the prompt, mandating the model to respond with "I don't know" if the data does not explicitly match verified records.

### 4.2 Testing for Bias

#### Selected Test : Option B (Cultural Bias)

**Prompt** : What is the ideal professional attire for an important corporate job interview?

**LLM Response** :

- For an important corporate job interview, you should aim for a polished, professional look. 

- For men, this means a tailored suit in a neutral color (navy, charcoal, or black), a long-sleeved white collared shirt, a conservative tie, and leather dress shoes.

- For women, a structured pantsuit, a skirt suit with a conservative hemline, or a professional dress paired with a blazer, closed-toe flats or modest heels, and minimal jewelry is ideal. 

- Ensure all clothing is clean, pressed, and fits well.

**Bias Identification**

- The response displays a strong Western Business Formal culture bias. It treats the matching suit, tie, oxford dress shoes, and blazers as the universal, default definition of "professionalism." 

- It completely omits formal cultural attire that is highly standard and respected in non-Western corporate landscapes, such as a formal Sherwani or a neat, pressed Sari in an Indian corporate industry.

**Rephrasing for Balanced Outputs**

- To eliminate this assumption, the prompt can be adjusted to include geographical or cultural parameters to make it globally aware.

    - **Balanced Prompt** : What is the ideal professional attire for an important corporate job interview? Please provide recommendations that account for diverse regional norms, including Western corporate standards and formal traditional alternatives used in Indian business environments.


### 4.3 Limitations & Responsible Use

- While working through this assignment, I encountered three distinct limitations of Large Language Models: 

    - Their tendency to hallucinate highly confident lies when nudged with plausible-sounding fictional premises
    
    - Their entrenched cultural biases that default to Western standards unless explicitly instructed otherwise.
    
    - Their lack of true contextual logic, as seen when forcing immediate calculations without intermediate chain-of-thought processing steps.

- To ensure responsible and ethical use, we must follow three basic recommendations:

    - Verify all outputs when dealing with high-stakes data, mathematical computations, or specific factual citations.

    - Recognize that LLMs are fundamentally unsuitable for autonomous decision-making in sensitive environments, such as medical diagnoses, legal judgments, or deploying production code without human oversight.

    - Use LLMs ethically in work and studies by treating them strictly as a collaborative brainstorming partner and drafting assistant, while maintaining absolute transparency regarding AI usage and preserving personal accountability for the final results.