# FUTURE_PE_01

# AI Website Copy Generator — Local Business Prompt Framework

**By:** POOJA S

**Internship:** Future Interns — AI/ML Track

**Tool Used:** Claude (Anthropic)

---

## What This Project Is

This project is a structured prompt framework that uses AI to generate complete, publish-ready website copy for local businesses.

Instead of writing website content from scratch, a business owner (or anyone helping them) fills in 8 simple details about their business. The prompt then generates all the copy they need for a real website — in one shot.

---

## The Business I Chose

**Business Name:** NOA The Magical Café
**Location:** Meghalaya, India
**Type:** Café with a study space, near the mountains

I chose this business because it has a unique setting (mountain views + study space) that most generic café copy would completely ignore. It was a good test of whether the framework could capture something specific and real.

---

## What the Framework Generates

The prompt produces four sections of website copy:

| Section | What's Inside |
|---|---|
| Homepage Copy | Headline, subheadline, value proposition, who it's for, key benefits, short intro |
| Services Page | Service name, what's included, why choose this business — for each service |
| CTA Sections | Primary CTA, trust-building CTA, urgency/location-based CTA |
| Tone Guide | Voice description, wrong tone example, right tone example |

---

## The 8 Inputs the Prompt Needs

| Input | Example (NOA Café) |
|---|---|
| Business Name | NOA The Magical Café |
| Business Type | Café |
| Location | Meghalaya, India |
| Key Services | Coffees, Desserts, Pastries, Study Space |
| USP (What makes it different) | Mountain view + study space combo, living room feeling |
| Target Customer | Students, tourists, local regulars |
| Tone | Friendly and confident |
| Trust Signal | 1,800 cups served, awards for greenery, friendliness, cleanliness |

---

## The Prompt Logic

The prompt works in a specific way:

1. **Inputs first** — The user fills in the 8 fields at the top. This forces specificity and prevents generic output.

2. **Role assignment** — The prompt tells Claude it is an expert website copywriter for local businesses. This sets the quality standard.

3. **Section separators** — Each section (Homepage, Services, CTA, Tone) is clearly labeled inside the prompt so the output is organized and easy to copy-paste directly into a website builder.

4. **Hard rules at the bottom** — The prompt includes rules like "never use filler phrases like we are passionate about" and "never start a headline with the business name." These rules push the output away from generic AI copy.

5. **Tone mechanism** — The tone input (friendly / professional / confident-simple) changes the voice across all sections automatically without needing separate prompts.

---

## Files in This Repository

```
/
├── README.md                  — This file
├── prompt/
│   └── website_copy_prompt.txt  — The full reusable prompt framework
├── output/
│   └── noa_cafe_full_copy.md    — Complete generated copy for NOA The Magical Café
```

---

## How to Use This for Any Business

1. Open `prompt/website_copy_prompt.txt`
2. Fill in the 8 business details at the top
3. Paste the full prompt into Claude (claude.ai)
4. Copy the output into your website builder (Bolt, Framer, Webflow, etc.)

The prompt is reusable. You can run it for any local business — salon, clinic, agency, coaching center — just by changing the inputs.

---

## What the Output Looks Like

The full generated copy for NOA The Magical Café is in `/output/noa_cafe_full_copy.md`.

It includes:
- A headline: *"Your Best Work Happens Here — With a View to Prove It."*
- A value proposition specific to the mountain location and study space
- Three service breakdowns (coffees, desserts, study space)
- Three CTA blocks with trust signals and location references
- A tone guide so the business knows how to keep their voice consistent

---

## What I Learned

- Generic inputs produce generic copy. The USP and target customer fields matter the most.
- "Anyone" is not a target customer. Defining the audience specifically improves every section.
- AI copy needs real business details to sound real. The framework is only as good as what you put in.
- A prompt is a system, not just a question. Structure, rules, and order all affect output quality.

---

## Tool Used

**Claude by Anthropic** — claude.ai


No paid API. No coding. Just a structured prompt run in the Claude chat interface.

---

## Live Website
🔗 [noa-mountain-haven.lovable.app](https://noa-mountain-haven.lovable.app/)

*This project was completed as part of the Future Interns AI/ML Virtual Internship Program.*


