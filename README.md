# ManyMinds – Perspectives on neurodiversity Agent

### Executive Summary
ManyMinds is a declarative Copilot agent that provides trustworthy, evidence‑informed guidance on neurodiversity for employees, managers, and leaders. It combines curated public knowledge with optional internal resources and applies neuroinclusive interaction principles by default. The agent serves as a single, scalable entry point for awareness, everyday support, and inclusive leadership enablement.

### Value
ManyMinds lowers the effort and cost of neurodiversity education by making reliable, role‑specific guidance instantly accessible without additional training resources. Clear source governance, inclusive design, and configurable modes build trust while ensuring safe use across the organization. This enables sustainable engagement, supports compliance and inclusion goals, and strengthens inclusive workplace culture at scale.
<br><br>

<img width="570" height="360" alt="image" src="https://github.com/user-attachments/assets/72a52dda-b7a2-444b-8d9d-a49f0250387e" />


## Inclusive by Design - ManyMinds intentionally
- Keeps responses structured and calm
- Reduces cognitive overload
- Avoids assumptions and generalizations
- Offers choice and control
- Focuses on strengths and needs, not “fixing”

## What ManyMinds Can Do
- Explain neurodiversity in a clear, non‑stigmatizing way
- Offer practical, everyday strategies (work & life)
- Support leaders with inclusive communication and management guidance
- Provide optional Coaching Mode (goal‑oriented, not therapy)
- Clearly distinguish public knowledge from company‑internal resources

## Default Behavior (Out of the Box)
- Sources: HYBRID (public + internal, if available)
- Citations: FULL (readable inline source links)
- Inclusive Mode: ON (low cognitive load, predictable structure)
- Coaching: AUTO (only when helpful)
You can change this at any time.

## Best practice to use
- just ask questions: I’d like to understand what neurodiversity means and why it matters at work.
- Be specific about your role: I’m a people manager. How can I better support neurodivergent employees?
- use Coaching Mode: COACH: ON Help me create a realistic 2‑week plan to reduce masking at work.

## Source Transparency
- Public sources are labeled P-*
- Internal company sources are labeled I-*
- You can explicitly request:
- MODE: PUBLIC → only external sources
- MODE: INTERNAL → only internal resources
- MODE: HYBRID → both (default)

This makes it easy to discover what support exists in your organization.

## SOURCE REGISTRY

- Sources are held in seperate txt files to ensure code quality
- the txt follow clear rules and are referenced within the agent source
- make sure to adjust agent source accordingly if you add own internal resources

Here is an exmaple of the source schema:
[P-WHO-AUTISM]
Title: WHO – Autism (fact sheet)  
Type: Public health fact sheet  
Scope: ASD overview, prevalence estimate, inclusion/support considerations  
Audience: Public, policymakers  
Link: https://www.who.int/news-room/fact-sheets/detail/autism-spectrum-disorders  
