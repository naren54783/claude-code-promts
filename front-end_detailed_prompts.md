
# Frontend Prompt Library 

## 1. Project Setup Prompt

    Act as a senior frontend engineer.

    Task:
    Initialize a React project using Vite with TypeScript and Tailwind CSS.

    Requirements:
    - Use React with Vite
    - Use TypeScript
    - Configure Tailwind CSS properly
    - Use a clean folder structure with:
    - components
    - pages
    - hooks
    - utils
    - styles
    - Add ESLint and Prettier
    - Use functional components only
    - Setup absolute imports
    - Keep the setup simple, scalable, and production-friendly

    Step 1: Propose 2–3 approaches
    For each approach, include:
    - How the project structure would be organized
    - Pros and cons
    - When that approach is best

    Step 2: Recommendation
    - Recommend the best approach for this project
    - Keep the reasoning practical and concise

    Important:
    - Do NOT generate code yet
    - Do NOT create files yet
    - Wait for my confirmation before implementation

    Expected output for this step:
    1. Approaches
    2. Recommendation
    3. Proposed project structure
    4. Key setup decisions

 #### Follow-up
     Use approach 2. Implement it with production-ready code.

    Keep it simple, clean, and maintainable.

### 2. Design System Prompt

    Act as a senior frontend engineer.

Task:
Design a reusable design system using Tailwind CSS for a React application.

Requirements:
- Define color palette, spacing scale, and typography
- Create reusable components:
  Button, Input, Card, Container
- Use consistent border radius (4px)
- Define variants (primary, secondary, ghost)
- Ensure accessibility (focus states, contrast)
- Keep the system simple, scalable, and production-friendly

Step 1: Propose 2–3 approaches
For each approach, include:
- How the design system is structured
- Styling strategy (pure Tailwind vs abstraction vs config-driven)
- Pros and cons
- When to use each approach

Step 2: Recommendation
- Recommend the best approach for this project
- Keep reasoning practical

Important:
- Do NOT write code yet
- Focus on structure, patterns, and reusability
- Wait for my confirmation before implementation

Expected output:
1. Approaches
2. Recommendation
3. Proposed component structure
4. Key design decisions


### 3. Layout + Routing Prompt

    Setup routing using React Router.

    Requirements:
    - Pages: Home, Platform, About, Contact
    - Layout with Navbar + Footer
    - Persistent layout wrapper
    - Clean route structure

    Output:
    - App routing setup
    - Layout component


### 4. Landing Page Prompt
    Build a responsive landing page.

    Sections:
    - Hero
    - Features grid
    - How it works
    - Testimonials
    - CTA

    Requirements:
    - Mobile-first design
    - Grid/flex layout
    - Clean spacing
    - Reusable components

    Output:
    - Fully responsive page


### 5. Make the entire app fully responsive.

    Requirements:
    - Mobile-first approach
    - Breakpoints: sm, md, lg, xl
    - Stack layout on small screens
    - Adjust typography and spacing
    - Optimize touch interactions

    Output:
    - Updated responsive components


### 6. Forms + Validation Prompt

    Build a form with validation.

    Requirements:
    - Use react-hook-form
    - Fields: name, email, password
    - Validation rules
    - Error messages
    - Submit handling

    Output:
    - Reusable form component

### 7. Form prompt
    Build a production-ready form in React.

    Requirements:
    - Use react-hook-form
    - Include validation
    - Show clear error states
    - Accessible labels and inputs
    - Responsive layout
    - Clean Tailwind styling
    - Loading and disabled submit states

    Output:
    - Final form component
    - Validation approach

### 8. API Integration Prompt

    Integrate API calls using Axios.

    Requirements:
    - Create API service layer
    - Handle loading, error, success states
    - Use async/await
    - Clean separation of concerns

    Output:
    - API utility
    - Example usage in component



### 9. Performance Optimization Prompt
    Optimize frontend performance.

    Requirements:
    - Lazy loading (React.lazy)
    - Code splitting
    - Memoization (useMemo, useCallback)
    - Avoid unnecessary re-renders

    Output:
    - Optimized components


### 10. UI Polish Prompt
    Improve UI/UX quality.

    Requirements:
    - Add hover states
    - Add transitions (150ms ease-out)
    - Improve spacing consistency
    - Better typography hierarchy
    - Subtle shadows and borders

    Output:
    - Refined UI components


### 11. Accessibility Prompt
    Improve accessibility.

    Requirements:
    - Semantic HTML
    - ARIA attributes
    - Keyboard navigation
    - Focus states
    - Screen reader support

    Output:
    - Accessible components


### 12. Testing Prompt
    Add frontend testing.

    Requirements:
    - Use Jest + React Testing Library
    - Test components
    - Test user interactions

    Output:
    - Sample test cases


### 13. Production Readiness Prompt
    Prepare app for production.

    Requirements:
    - Environment variables
    - Build optimization
    - Remove console logs
    - Error boundaries
    - SEO basics

    Output:
    - Production-ready setup


## Optimization prompts
### 14. Performance 
    Optimize this React frontend for performance and maintainability.

    Focus areas:
    - Reduce unnecessary re-renders
    - Identify components that should use React.memo
    - Use useMemo and useCallback only where they provide real benefit
    - Avoid inline object/function recreation where it hurts performance
    - Lazy load heavy routes/components
    - Improve bundle size where possible
    - Remove dead code and duplicated logic
    - Keep readability high

    Output:
    1. List the main performance issues you found
    2. Explain why each issue matters
    3. Provide the improved code
    4. Briefly summarize the tradeoffs

### 15. Render performance issues

    Review this component for render performance issues.

    Check for:
    - Unnecessary state
    - Derived state that should be computed instead
    - Expensive calculations inside render
    - Recreated handlers and props
    - Over-rendering children
    - Poor key usage in lists

    Refactor the code with performance improvements, but do not over-engineer it.
    Explain each change briefly.


### 16. Optimize for production readiness.   

    Optimize this frontend for production readiness.

    Requirements:
    - Improve code splitting
    - Use lazy loading for routes
    - Minimize repeated API calls
    - Prevent duplicate fetches
    - Add loading and error states where missing
    - Keep UX smooth
    - Preserve current behavior

    Return:
    - Problems found
    - Refactored code
    - Production-readiness recommendations


## 17. Refactoring prompts    

    Refactor this React code to make it cleaner, more modular, and easier to maintain.

    Goals:
    - Break large components into smaller reusable components
    - Extract repeated UI into shared components
    - Improve naming of variables, functions, and props
    - Separate business logic from presentation
    - Remove duplicated code
    - Keep behavior exactly the same
    - Use TypeScript-friendly patterns if applicable

    Output:
    1. Refactoring plan
    2. Refactored code
    3. Explanation of major improvements

###
    Refactor this component using senior-level frontend practices.

    Requirements:
    - Keep the UI behavior unchanged
    - Improve readability and structure
    - Extract helper functions where needed
    - Move side effects into proper hooks
    - Avoid deeply nested JSX
    - Improve prop typing/interfaces
    - Make it easier to test

    Please explain why each refactor improves maintainability.

## UI issue fixing prompts    

### 
    Fix the UI issues in this React/Tailwind component.

    Check for:
    - Broken alignment
    - Inconsistent spacing
    - Overflow issues
    - Text wrapping problems
    - Button/input sizing inconsistencies
    - Poor responsive behavior
    - Visual hierarchy issues

    Requirements:
    - Keep the existing design style
    - Make the layout clean and balanced
    - Ensure mobile responsiveness
    - Explain what caused each issue
    - Provide corrected code

###
    Review this page like a frontend engineer doing UI bug fixing.

    Find and fix:
    - Layout shifts
    - Elements overlapping
    - Incorrect flex/grid usage
    - Margin/padding inconsistencies
    - Inconsistent card heights
    - Misaligned text/buttons
    - Responsive breakpoints that do not work well

    Return:
    1. UI issues found
    2. Root cause of each issue
    3. Updated code    
### 
    This component has become messy. Clean it up like a senior frontend engineer.

    Goals:
    - Simplify the logic
    - Reduce JSX complexity
    - Improve naming
    - Extract reusable parts
    - Fix UI inconsistencies
    - Improve responsiveness
    - Remove performance anti-patterns
    - Keep the same functionality

    Do not rewrite the whole thing unnecessarily.
    Make focused, high-value improvements.
    Show the final code and explain the important changes.  

## Prompt for bug-fix mode
    Act like a frontend engineer debugging UI and code quality issues.

    Analyze this code for:
    - Visual bugs
    - Responsiveness issues
    - State management mistakes
    - Render inefficiencies
    - Maintainability problems

    Then:
    - Fix the issues
    - Explain root causes
    - Provide the corrected version
    - Keep the solution practical and production-ready

    Refactor, optimize, and fix UI issues in this React component. Preserve functionality, improve maintainability, fix responsiveness and layout problems, and remove obvious performance anti-patterns. Explain the key changes and provide the final code.


### Best way to use them
    Use this flow with Claude Code:

    1. Paste the component and say:
        Refactor, optimize, and fix UI issues in this component.
    2. Then follow with:
        Now make the code more reusable without changing behavior.
    3. Then:
        Now polish spacing, alignment, and responsive behavior.
    4. Then:
        Now do a final pass for production readiness.

    Here’s a compact master prompt you can save:

    Review this React/Tailwind code as a senior frontend engineer. Refactor for maintainability, optimize performance where it matters, and fix UI/responsive issues. Preserve behavior, avoid over-engineering, explain the issues found, and provide production-ready code.

##
    Review this React + Tailwind code as a senior frontend engineer. Fix UI/responsive issues, refactor for maintainability, improve accessibility, and optimize performance where it matters. Preserve behavior, avoid over-engineering, explain the key issues, and provide production-ready code.        

##
    
    Audit this codebase for file size and loading performance issues. Identify unused CSS, redundant JavaScript imports, uncompressed assets, and synchronous loading patterns that should be async. Prioritize changes that would have the most impact on initial page load time, and implement the top five with explanations of what you changed and why.    