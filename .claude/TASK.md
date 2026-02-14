# Add Feature Task

You are implementing a new feature in the codebase. Follow the goal and
scope provided in the task arguments carefully.

## Guidelines
- Read and understand the existing codebase architecture first
- Follow the project's established patterns and conventions
- Write clean, well-documented code
- Add appropriate tests for new functionality
- Ensure the feature integrates well with existing code
- Handle edge cases and error conditions
- Update documentation if the feature affects the user-facing API
- Ensure the build passes before completing


## Project Conventions (vercel)
- This is a Vercel-deployed project. Follow Next.js and Vercel best practices.
- Use the App Router (app/) if it exists; otherwise use Pages Router (pages/).
- Follow the Next.js file-based routing conventions.
- Use Server Components by default; add 'use client' only when needed.
- Ensure API routes follow Next.js API route patterns.
- Use environment variables via process.env (NEXT_PUBLIC_ for client-side).
- Respect vercel.json configuration for rewrites, redirects, headers.
- Ensure builds pass with `next build` before completing.
- Follow TypeScript strict mode if tsconfig.json has strict: true.


## Goal
Add a new documentation page called 'Getting Started' under the pages directory. The page should include sections for: Prerequisites, Installation, Quick Start, and Next Steps. Use clear markdown formatting and follow the existing documentation style in the project.

## Scope
Focus on: pages/

## Definition of Done
- The feature is fully implemented as described in the goal
- New code follows existing project patterns
- Tests are written and passing for the new functionality
- The build completes without errors
- No existing tests are broken
- Code is documented appropriately


## Important: Interruption Protocol
If you encounter any of the following situations, clearly state the situation
and stop working. DO NOT attempt to continue or work around the issue:
- You need additional information or clarification from the user
- You need approval for a significant architectural decision
- You need a secret, API key, or credential that is not available
- You encounter an error you cannot resolve

State the type of blocker (NEEDS_USER_INPUT, NEEDS_APPROVAL,
MISSING_SECRET, or ERROR) followed by a clear description.
