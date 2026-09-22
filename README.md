# DAY-10-LAB-10-GUNSHEEL-KAUR-AVIATION
Day 10 Generative AI lab on aviation image generation, five-part image prompting, iterative refinement, prompt bleed, accuracy audits and responsible AI use.

Programme: BBA Aviation Management
Course: Generative AI for Business
Lab: Day 10 — Lab 10
Topic: Image Generation, Five-Part Prompt and Iterative Refinement

Objective

The objective of this lab is to understand how structured image prompts can improve AI-generated aviation visuals. The lab focuses on the five-part image prompt:

Subject
Medium or Style
Environment
Lighting
Aspect Ratio

The lab also examines iterative refinement, prompt bleed, aviation accuracy, professionalism, ethical use and human review.

1. Weak Image Prompt

The initial weak prompt was:

"Create an airport image."

This prompt provides very little direction to the image-generation tool. It does not clearly specify the subject, visual style, environment, lighting, aspect ratio or intended use.

Missing Components
Subject
Style
Detailed environment
Lighting
Aspect ratio
Intended use
Brand restrictions
Text restrictions
Accuracy instructions
2. Five-Part Image Prompt
Five Components
Component	Student Response
Subject	Diverse young adult travellers using self-service check-in kiosks
Medium or Style	Professional photorealistic corporate photography
Environment	Modern international airport terminal with realistic travel bags and passenger movement
Lighting	Bright natural daylight with clean professional illumination
Aspect Ratio	16:9 landscape for a business presentation
Structured Prompt

Create a professional, photorealistic image of a diverse group of young adult travellers using self-service check-in kiosks inside a modern international airport terminal. Show a clean, spacious environment with realistic travel bags and clear passenger movement. Use bright natural daylight and a neutral blue-and-white colour palette. Use a 16:9 landscape aspect ratio suitable for a business presentation. Do not include airline logos, airport names, readable personal information, boarding-pass details or promotional text.




3. Weak Prompt vs Structured Prompt
Evaluation Criterion	Weak Prompt	Structured Prompt
Clear subject	Partially clear	Clearly specified
Aviation setting	General airport	Modern international terminal
Professional style	Not specified	Photorealistic corporate style
Lighting	Not specified	Bright natural lighting
Aspect ratio	Not specified	16:9 landscape
Realistic details	Less controlled	More controlled
Unwanted text/logos	May appear	Explicitly restricted
Presentation use	Limited	Suitable for presentation

The structured prompt produced a more useful image because it clearly defined the visual requirements. However, human review is still required because AI-generated images may contain inaccurate details or distorted text.

4. Iterative Refinement

The image was refined by changing one variable at a time.

Versions
Original: Photorealistic airport self-service check-in scene in 16:9.
Version 1 — Style: Changed photorealistic photography to a flat-vector illustration.
Version 2 — Lighting: Changed natural daylight to warm evening lighting.
Version 3 — Aspect Ratio: Changed 16:9 landscape to 1:1 square.
Version 4 — Environment: Changed the self-service check-in area to a boarding-gate waiting area.




Key Observation

Changing one variable at a time makes it easier to identify the effect of each prompt modification. However, prompt bleed can occur when changing one instruction unintentionally affects other visual elements.

Version 4 introduced invented gate numbers, flight times and flight-status information even though these details were not requested.

5. Prompt Bleed

Prompt bleed occurs when an instruction unintentionally affects another part of the generated image or causes an unwanted element to appear.

Examples
Intended Instruction	Unwanted Result	Corrective Instruction
Neutral blue-and-white palette	Warmer colours appeared	Maintain neutral blue-and-white colours
No readable promotional text	Gate numbers and flight information appeared	Keep all displays blank
Realistic aviation environment	Artificial screen details	Use realistic equipment with non-readable screens
Boarding-gate waiting area	Invented operational information	Use a generic gate area without operational information




6. Correcting Unwanted Elements
Correction Prompt

Remove all readable gate numbers, flight times, flight-status information, promotional messages and other artificial text. Keep the boarding-gate waiting area, passengers, luggage, aircraft and airport architecture unchanged. Keep the aircraft only outside the terminal windows. Maintain realistic passenger spacing and unobstructed walkways. Do not add airline logos, airport names, personal information or operational information. Keep digital displays blank or non-readable.




7. Aviation Accuracy Audit

The generated visual was checked for:

Aircraft structure
Aircraft placement
Passenger behaviour
Airport equipment
Walkways and exits
Signs
Airline branding
Personal information
Misleading operational information

Most visual elements were acceptable, but Version 4 contained invented gate and flight information. These details needed to be removed before publication.

8. Professionalism Audit
Criterion	Score
Visual Quality	5/5
Business Relevance	5/5
Composition	5/5
Colour Consistency	4/5
Readability	3/5
Audience Suitability	5/5
Brand Neutrality	5/5
Overall Professionalism	4/5

The image had strong presentation value, but human review and correction of artificial text were required.

9. Three Aviation Visuals
Visual A — Airline Marketing

Purpose: Create an attractive campaign visual encouraging students to explore domestic destinations.

Target Audience: Young adults and university students interested in travel.

Prompt Focus:

Young adult travellers
Domestic journey
Modern airport terminal
Photorealistic commercial photography
Bright daylight
16:9 landscape
No airline logos, prices, airport names or promotional text




Visual B — Airport Awareness

Purpose: Encourage passengers to keep airport terminal walkways clear.

Target Audience: Airport passengers and travellers.

Prompt Focus:

Passengers moving responsibly
Clear walkways
Modern airport terminal
Realistic seating and infrastructure
Bright neutral lighting
No inaccurate safety signage




Visual C — Aviation Presentation

Presentation Title: Improving Passenger Experience Through Airport Technology

Purpose: Explain the role of airport self-service technology.

Target Audience: Students, teachers and aviation-management audiences.

Prompt Focus:

Passengers using self-service technology
Modern international airport
Photorealistic corporate photography
16:9 landscape
Realistic kiosks and luggage
No fake charts, statistics, logos or passenger data




10. Image-Generation Limitations

The generated images demonstrated several limitations:

Some airport signs contained readable or semi-readable text.
Human faces and hands were mostly realistic but still required inspection.
Airport structures and aircraft appeared visually convincing, but operational accuracy could not be assumed.
No obvious real airline logo was intentionally included.
Version 4 introduced unwanted gate numbers, flight times and status information.
AI-generated visuals can potentially mislead viewers if fake operational information is presented as real.

Human correction is therefore required before publication.

11. Ethical and Responsible Use

The generated images were reviewed for:

Deceptive presentation
Unauthorised branding
Fake operational information
Real events or individuals
Stereotypes
False safety information
Authenticity concerns
Usage rights
AI-use disclosure

The images should not be presented as authentic photographs of a real airport, flight or event.

12. Reflection
What are the five parts of an effective image prompt?

The five parts are:

Subject
Medium or Style
Environment
Lighting
Aspect Ratio
What is image generation?

Image generation creates a new image based on a text prompt, while image retrieval finds an existing image from a source.

Why change only one variable at a time?

It makes it easier to identify which prompt change caused a particular visual change.

What is prompt bleed?

Prompt bleed occurs when an instruction unintentionally affects another part of the generated image or introduces an unwanted element.

Example of an aviation inaccuracy

The AI introduced invented information such as "Gate B12", a departure time and an "On Time" status.

Why should text normally be added separately?

AI image tools can generate distorted or incorrect text. Adding text separately provides better control over spelling, formatting and accuracy.

Why avoid real airline logos?

Real airline logos may create brand, trademark and authenticity concerns.

Why is peer review important?

Peer review can identify visual problems that the creator may overlook, including fake text, unrealistic airport details and misleading information.

Why is human review required?

AI-generated images can contain realistic-looking but incorrect people, equipment, aircraft, signs, text or operational details. Human review helps identify and correct these problems before publication.




13. GitHub File Structure
genai-business-portfolio/
└── day-10-image-generation/
    ├── aviation-image-generation.md
    └── images/
        ├── weak-prompt.png
        ├── structured-prompt.png
        ├── version-1-style.png
        ├── version-2-lighting.png
        ├── version-3-aspect-ratio.png
        ├── version-4-environment.png
        ├── corrected-image.png
        ├── visual-a-airline-marketing.png
        ├── visual-b-airport-awareness.png
        └── visual-c-aviation-presentation.png




14. AI Usage Declaration

An AI image-generation tool was used to create the visuals in this activity. The prompts were independently designed and refined, and the images were checked for accuracy, professionalism, bias and responsible use.

15. Final Learning Outcome

This lab demonstrated that structured five-part image prompts provide better control over AI-generated aviation visuals. Iterative refinement helps test individual prompt variables, while prompt-bleed analysis identifies unintended changes.

The activity also demonstrated that AI-generated aviation images must be checked for fake text, incorrect operational information, branding, aviation inaccuracies and ethical concerns before publication.

Conclusion

The Day 10 lab developed practical skills in aviation image generation, structured prompting and iterative visual refinement. It showed that detailed prompts can improve the quality and relevance of generated images, but AI outputs still require human inspection and responsible review before official or public use.
