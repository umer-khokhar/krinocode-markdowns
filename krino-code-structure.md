# KrinoCode: First Launch Structure

The 10 launch items are **pages**, and each page has its own sections and sub-topics. Pages are grouped into 3 launch sections so the site has a clear navigation from day one.

---

## Launch Navigation

```
KrinoCode
│
├── Start Here
│     └── 1. Start Here
│
├── Section A: The AI Era
│     ├── 2. What Changed and What Did Not
│     └── 3. What AI Does Well and Badly
│
├── Section B: Foundation
│     ├── 4. Learning With AI Without Losing the Skill
│     └── 5. Learn What Matters
│
├── Section C: Working With AI Output
│     ├── 6. Reviewing AI Output
│     └── 7. Common AI Failure Modes
│
└── Section D: Spec-Driven Development
      ├── 8. Why Specs Matter Now
      ├── 9. Anatomy of a Good Spec
      └── 10. Worked Example: Spec to Shipped
```

## Suggested folder layout

```
docs/
├── start-here/
│   └── index.md
├── ai-era/
│   ├── what-changed.md
│   └── what-ai-does-well-and-badly.md
├── foundation/
│   ├── learning-with-ai.md
│   └── learn-what-matters.md
├── ai-output/
│   ├── reviewing-ai-output.md
│   └── common-failure-modes.md
└── spec-driven/
    ├── why-specs-matter.md
    ├── anatomy-of-a-spec.md
    └── worked-example.md
```

## Standard page template (use on every page)

1. **Why it matters**: one short paragraph
2. **Core ideas**: the main concepts
3. **Mental model**: one simple picture or analogy
4. **Example**: something concrete
5. **AI lens**: how AI helps here, and where it misleads you
6. **Practice exercise**
7. **Check yourself**: 3 to 5 questions
8. **Next page**: link to the following page

**Signal ratings** used on pages and sections: **[E] Essential**, **[U] Useful**, **[O] Optional**.

---

# Page 1: Start Here

**Section A: What KrinoCode Is**
- A. The one-line promise (know what matters in the AI era)
- B. The problem: too much noise, too many tools
- C. The idea behind the name (*krino*: to tell what matters from what doesn't)

**Section B: Who This Is For**
- Complete beginners
- Self-taught developers filling gaps
- Working developers adapting to AI
- Who this is *not* for

**Section C: What You Will Learn**
- Overview of the full roadmap (launched pages and coming soon)
- The three themes: learn what matters, work well with AI, build from clear specs

**Section D: How to Use the Docs**
- Reading order
- The signal rating system (Essential, Useful, Optional)
- The standard page template
- Pace: suggested time per week

**Section E: Choose Your Path**
- Path 1: I'm new to development
- Path 2: I code, but I use AI a lot and want to do it well
- Path 3: I'm experienced and want the spec-driven workflow

**Section F: Community and Contributing**
- How to give feedback
- How to report errors or suggest a page
- Code of conduct

---

# Page 2: What Changed and What Did Not

**Section A: The Big Shift**
- Code is cheap to produce, correctness is not
- The bottleneck moved from typing to deciding and verifying
- A short timeline of how coding tools evolved (autocomplete, chat, agents)

**Section B: What Changed**
- Speed of producing code
- Cost of boilerplate and prototypes
- Expectations from employers and teams
- The way people learn and search for answers
- The pace of new tools

**Section C: What Did Not Change**
- Computers still do exactly what they are told
- Requirements must still be understood
- Bugs, security and maintainability still matter
- Communication and teamwork
- The need to understand what you ship

**Section D: Skills That Gain Value**
- Specification and clear thinking
- Code review and verification
- Debugging
- System thinking and architecture
- Communication and judgment

**Section E: Skills That Lose Value**
- Memorizing syntax
- Writing routine boilerplate by hand
- Knowing every API by heart

**Section F: Durable vs. Shifting**
- A simple table: durable skills vs. shifting tools
- How to tell which category something belongs to

**Section G: Common Myths**
- "Developers will not be needed"
- "You don't need to learn fundamentals anymore"
- "AI code is always better or always worse"

**AI lens**: how AI can mislead you about its own abilities

**Exercise**: list 10 tasks from your last project and mark each as *changed*, *unchanged* or *partly changed*

---

# Page 3: What AI Does Well and Badly

**Section A: How AI Coding Tools Work (in plain terms)**
- A language model predicts likely text, it does not "understand" like a person
- Context window and why it matters
- Training cutoff and outdated knowledge
- Chat, editor assistants and agents

**Section B: Where AI Is Strong**
- Boilerplate and repetitive code
- Translating between languages and formats
- Explaining unfamiliar code
- Writing first drafts of tests
- Refactoring with clear rules
- Searching and summarizing documentation
- Generating examples

**Section C: Where AI Is Weak**
- Novel design and architecture
- Subtle logic bugs
- Security-sensitive code
- Large codebases with lots of hidden context
- Keeping long sessions consistent
- Knowing what it does not know
- Recent libraries and versions

**Section D: Why It Fails (Root Causes)**
- Missing context
- Ambiguous instructions
- Outdated training data
- Confident-sounding guesses (hallucination)
- Pattern matching over reasoning

**Section E: A Practical Decision Guide**
- Good task for AI: yes / maybe / no
- A simple flowchart: "Should I use AI for this?"
- How much to verify depending on risk

**Section F: Matching Task to Tool**
- Quick questions vs. multi-file edits vs. autonomous work

**AI lens**: AI's own self-assessment is not reliable, verify independently

**Exercise**: give the same task to AI in three different ways, compare the results and note where it went wrong

---

# Page 4: Learning With AI Without Losing the Skill

**Section A: The Core Problem**
- Getting answers is easy, building understanding is not
- The illusion of competence
- Why struggling is part of learning

**Section B: How Learning Actually Works**
- Active recall
- Spaced repetition
- Deliberate practice
- Feedback loops

**Section C: Using AI as a Tutor, Not a Crutch**
- Ask for hints, not full solutions
- Ask AI to explain, then explain back in your own words
- Ask AI to quiz you
- Ask for multiple approaches and compare
- Ask "why", not just "how"

**Section D: Struggle First, Then Ask**
- A simple rule: try for X minutes before asking
- How to describe your attempt when you ask
- When to stop struggling and get help

**Section E: Warning Signs of Over-Reliance**
- You can't explain the code you shipped
- You can't start without AI
- You copy errors back without reading them
- You don't recognize when the answer is wrong

**Section F: A Weekly Learning Routine**
- Build, review, reflect
- "No-AI" practice sessions
- Keeping a learning log

**Section G: Learning Paths by Experience Level**
- Beginner
- Intermediate
- Experienced developer learning a new area

**AI lens**: prompts that turn AI into a tutor (templates)

**Exercise**: solve one small problem with no AI, then with AI, then compare what you learned

---

# Page 5: Learn What Matters (Essential, Useful, Optional)

**Section A: The Problem of Too Much**
- Too many tools, frameworks and opinions
- Why people feel behind
- The cost of chasing everything

**Section B: The Signal Rating System**
- **Essential**: needed for almost everything, learn first
- **Useful**: valuable in the right situation
- **Optional**: awareness only
- How ratings are decided on KrinoCode

**Section C: The 80/20 of Software Skills**
- The small set of skills that carry most of the value
- Fundamentals vs. tools
- Concepts last, tools change

**Section D: How to Judge a Topic Yourself**
- Questions to ask: How often will I use this? What breaks without it? Will it still matter in 3 years?
- Spotting hype
- Evaluating a new tool in 30 minutes

**Section E: Depth vs. Breadth**
- When to go deep
- When to stay broad
- T-shaped skills

**Section F: Building Your Own Priority List**
- Mapping your goals
- Sorting skills into the three levels
- Revisiting it every few months

**Section G: Staying Current Without Burning Out**
- A sustainable information diet
- What to ignore

**AI lens**: AI will tell you everything is important, you decide what matters

**Exercise**: sort 20 technologies or skills into Essential, Useful and Optional for your own goal

---

# Page 6: Reviewing AI Output

**Section A: Why Review Is the Core Skill**
- AI output looks right even when it's wrong
- You are responsible for what you ship
- Review is faster than writing, but only if you are good at it

**Section B: The Review Mindset**
- Treat AI as a fast, confident junior developer
- Read the diff, not just the result
- Assume nothing, verify everything that matters

**Section C: The Review Process**
1. Does it solve the right problem? (check against the spec)
2. Do I understand every line?
3. Does it run, and do the tests pass?
4. Edge cases and failure behavior
5. Security and data handling
6. Fits the codebase (style, structure, existing helpers)
7. Unneeded changes or complexity

**Section D: Verification Techniques**
- Reading line by line
- Running the code and tests
- Writing a test for the claim
- Checking APIs and libraries against official docs
- Checking package names actually exist
- Testing with odd inputs

**Section E: The Review Checklist**
- A printable checklist (correctness, clarity, security, performance, maintainability)
- A shorter version for small changes

**Section F: Reviewing at Different Sizes**
- A single function
- A multi-file change
- A whole feature produced by an agent

**Section G: When to Reject or Redo**
- Signs the approach is wrong
- When to restart the conversation instead of patching
- How to give feedback to the AI

**Section H: Real Examples**
- Example 1: a function that looks fine but has an off-by-one bug
- Example 2: an endpoint missing authorization
- Example 3: code using an API that does not exist
- Each shown as *the generated code, what was wrong, how to catch it*

**AI lens**: asking AI to review its own work (useful, but not enough)

**Exercise**: review three flawed code samples and find the bugs, then compare with the answer key

---

# Page 7: Common AI Failure Modes

A catalog page. Each failure mode uses the same 5-part format:
**What it looks like → Why it happens → Real example → How to catch it → How to prevent it**

**Section A: Correctness Failures**
- Invented APIs, functions and packages
- Outdated library usage and deprecated methods
- Off-by-one and edge-case errors
- Wrong assumptions about data shape
- Plausible but incorrect logic

**Section B: Security Failures**
- Missing input validation
- Missing authentication or authorization checks
- Hard-coded secrets
- SQL injection and XSS patterns
- Insecure defaults
- Suggesting vulnerable or non-existent packages

**Section C: Design and Quality Failures**
- Over-engineering and unnecessary abstraction
- Duplicating existing code instead of reusing it
- Ignoring project conventions
- Giant functions and tangled code
- Missing error handling

**Section D: Behavior Failures**
- Silent behavior changes during a refactor
- Deleting or "fixing" tests to make them pass
- Doing more than asked (scope creep)
- Doing less than claimed
- Claiming something works without running it

**Section E: Conversation and Context Failures**
- Drift across long sessions
- Forgetting earlier constraints
- Losing track of files and state
- Repeating a failed fix in a loop
- Overconfidence when wrong

**Section F: Quick Reference Table**
- Failure mode, warning sign and fastest check

**Section G: Prevention Habits**
- Clear specs
- Small, focused tasks
- Tests first
- Pinning versions in context
- Fresh sessions for new tasks
- Review every diff

**AI lens**: prompts that reduce each failure mode

**Exercise**: given a failure mode name, write a prompt that would have prevented it

---

# Page 8: Why Specs Matter Now

**Section A: The Problem With Vague Prompts**
- "Build me a login page" and what goes wrong
- Same prompt, ten different results
- Rework caused by unclear intent

**Section B: What a Spec Is**
- Definition in plain language
- Spec vs. prompt vs. ticket vs. documentation
- A spec is a contract between you and the AI (and your future self)

**Section C: Why Specs Matter More Now**
- AI executes literally and confidently
- Code is cheap, so clarity is the bottleneck
- Specs make review possible (you check against something)
- Specs make results repeatable
- Specs help teams share intent

**Section D: What Spec-Driven Development Is**
- The workflow: Spec → Plan → Tasks → Implement → Verify
- How it differs from "vibe coding"
- How it differs from older heavy documentation processes

**Section E: When to Use a Spec, and How Much**
- Tiny task: a few lines
- Feature: a one-page spec
- System: a fuller spec
- A simple rule for deciding

**Section F: Benefits and Costs**
- Faster overall, fewer rewrites, better review
- Upfront thinking time
- Risks of over-specifying

**Section G: Common Objections**
- "It's slower than just prompting"
- "Requirements change too fast"
- "AI can figure out what I mean"

**AI lens**: using AI to help *write and sharpen* the spec (not just execute it)

**Exercise**: take one vague prompt you used recently and list every decision it left open

---

# Page 9: Anatomy of a Good Spec

**Section A: The Parts of a Spec**
1. **Goal and context**: what and why
2. **Users and scenarios**: who uses it, in what situations
3. **Requirements**: what it must do
4. **Constraints**: stack, performance, compatibility, style
5. **Non-goals**: what it must not do or what is out of scope
6. **Acceptance criteria**: how you will know it works
7. **Edge cases and failure behavior**
8. **Examples and sample data**
9. **Open questions**

**Section B: Writing Each Part Well**
- For each part: purpose, what good looks like, what weak looks like
- Weak vs. strong rewrites side by side

**Section C: Writing Acceptance Criteria**
- Testable statements
- Given / When / Then format
- Examples of vague vs. testable criteria

**Section D: Level of Detail**
- What to specify and what to leave to the AI
- Specify behavior, not implementation (unless it matters)
- Avoiding contradictions

**Section E: Spec Types**
- Feature spec
- Bug-fix spec
- Refactor spec
- API spec (brief intro, with OpenAPI as a later topic)
- UI spec

**Section F: Reviewing a Spec**
- A spec review checklist
- Asking AI to find gaps and ambiguities
- Getting a second human to read it

**Section G: Templates**
- One-page feature spec template
- Short bug-fix template
- Refactor template

**AI lens**: asking AI "what's missing or unclear in this spec?"

**Exercise**: turn a vague idea into a one-page spec using the template, then have AI critique it

---

# Page 10: Worked Example, Spec to Shipped

A full walkthrough on one small, realistic feature, so readers see the complete workflow. Suggested feature: **"Add a bookmark feature to a notes app"** (small, with UI, API and data, no heavy setup).

**Section A: The Starting Point**
- The existing project (small starter repo provided)
- The vague request, as it first arrives

**Section B: Step 1: Clarify and Write the Spec**
- Asking the right questions
- Using AI to find gaps
- The finished spec (goal, requirements, constraints, non-goals, acceptance criteria, edge cases)

**Section C: Step 2: Plan**
- Turning the spec into a technical plan
- Reviewing and correcting the plan before any code

**Section D: Step 3: Break Into Tasks**
- Small, ordered, verifiable tasks
- Which tasks are good for AI and which to do yourself

**Section E: Step 4: Tests From the Spec**
- Writing tests from the acceptance criteria first

**Section F: Step 5: Implement With AI**
- Giving context and the spec
- One task at a time
- Showing a real prompt and the actual output

**Section G: Step 6: Review**
- Applying the review checklist from Page 6
- Problems found (shown honestly, including failure modes from Page 7)
- Fixing and re-verifying

**Section H: Step 7: Verify Against the Spec**
- Running tests
- Manual check of each acceptance criterion
- Updating the spec if reality changed

**Section I: Ship and Reflect**
- Commit, pull request and merge
- What went well and what you would change
- Time and effort summary

**Section J: Comparison**
- Same feature built with a vague prompt only
- What differed in rework, bugs and clarity

**Section K: Try It Yourself**
- Starter repo
- A second feature to build alone using the same steps
- Solution to compare against

---

# Launch Checklist

- [ ] All 10 pages drafted using the standard page template
- [ ] Each page has an AI lens, exercise and "check yourself" questions
- [ ] Starter repo for the worked example published
- [ ] Review checklist and spec template available as downloads
- [ ] Navigation, search and "next page" links working
- [ ] Domain, GitHub and social handles ready
- [ ] About page and contribution guide
- [ ] "Coming soon" roadmap page showing the full structure

# Suggested Writing Order

1. Page 6: Reviewing AI Output (flagship, your clearest value)
2. Page 7: Common AI Failure Modes
3. Page 8: Why Specs Matter Now
4. Page 9: Anatomy of a Good Spec
5. Page 10: Worked Example
6. Page 3: What AI Does Well and Badly
7. Page 2: What Changed and What Did Not
8. Page 4: Learning With AI Without Losing the Skill
9. Page 5: Learn What Matters
10. Page 1: Start Here (write last, once you know what the site contains)