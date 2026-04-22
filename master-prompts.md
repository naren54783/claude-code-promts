 
 ### Best Prompt

    Act as a senior software engineer.

    Task:
    [describe task]

    Step 1: Propose 2–3 approaches with pros/cons
    Step 2: Recommend best approach

    IMPORTANT:
    - Do NOT write code yet
    - Wait for my confirmation
 
 ###   
    
    Act as a senior software engineer.

    Task:
    [describe what you want]

    Step 1: Propose multiple approaches
    - Give 2–3 possible approaches
    - For each approach include:
    - How it works
    - Pros and cons
    - When to use it

    Step 2: Recommendation
    - Suggest the best approach for this use case
    - Keep reasoning practical (not theoretical)

    IMPORTANT:
    - Do NOT write code yet
    - Wait for my confirmation before implementation


###
    Use Approach [X]. Now implement it with production-ready code.

    Requirements:
    - Clean architecture
    - Maintainable code
    - Proper validation and error handling
    - Keep it simple, avoid over-engineering

    Output:
    - Code
    - Short explanation of key decisions

### strong session opener
    Read and follow CLAUDE.md for project conventions.

    Before making changes:
    - summarize the relevant rules from CLAUDE.md in 5 bullets max
    - identify any ambiguity or conflict
    - propose a short plan

    While implementing:
    - follow existing patterns in the repo
    - do not add dependencies unless explicitly approved
    - keep changes minimal and production-ready

    Before finishing:
    - verify the code matches CLAUDE.md rules
    - run or describe lint/tests impacted
    - list files changed and why

 ### Instead of relying on passive memory, start sessions with a short instruction block like:
    Follow project rules in CLAUDE.md.
    Non-negotiables for this task:
    - no new dependencies
    - TypeScript strict mode
    - functional components only
    - update tests if behavior changes

    Before coding:
    1. summarize relevant rules you found
    2. state plan in 3 bullets
    3. then implement   