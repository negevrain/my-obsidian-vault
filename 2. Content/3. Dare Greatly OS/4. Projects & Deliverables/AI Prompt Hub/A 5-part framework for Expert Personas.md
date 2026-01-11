---
Favorite: false
Status: Draft
---
Hey everyone, I see a lot of people using basic `Act as a [Role]` prompts. This is a good start, but it’s lazy and gives you generic, surface-level answers.

To get truly expert-level output, you need to give the LLM a complete identity. I’ve had huge success with this 5-part framework:

1. **[Role & Goal]:** Define _who_ it is and _what_ it’s trying to achieve.
    
    - _Example:_ “You are a Silicon Valley venture capitalist. Your goal is to review this pitch and decide if it’s worth a $1M seed investment.”

1. **[Knowledge Base]:** Define its specific expertise and experience.
    
    - _Example:_ “You have 20 years of experience, have reviewed 5,000 pitches, and have deep expertise in B2B SaaS, and AI-driven platforms. You are skeptical of consumer-facing hardware.”

1. **[Tone & Style]:** Define _how_ it communicates.
    
    - _Example:_ “Your tone is skeptical but fair, concise, and professional. You use financial terminology correctly. You avoid hype and focus on fundamentals: market size, team, and traction.”

1. **[Constraints]:** Define what it _should not_ do. This is critical.
    
    - _Example:_ “You will NOT give vague, positive feedback. You will be critical and point out at least 3 major weaknesses. Do not summarize the pitch; only provide your analysis. Your response must be under 300 words.”
    

1. **[Example Output]:** Show it _exactly_ what a good response looks like.
    
    - _Example:_ “A good analysis looks like this: ‘Team: Strong, but lacks a technical co-founder. Market: TAM is inflated; realistic TAM is closer to $500M…’”
    

When you combine all five, you don’t just get a “costume”—you get a true expert persona that dramatically constrains the model’s output to exactly what you need.