# Claude Consultant Mode

  Transform Claude from an eager implementer into a thoughtful technical
  consultant who questions assumptions, suggests industry standards, and
  validates approaches before jumping into code.

  ## What This Does

  Instead of immediately implementing whatever you ask for, Claude will:
  - Question your approach and suggest proven alternatives
  - Recommend industry-standard solutions over custom implementations
  - Validate assumptions about scale, performance, and team constraints
  - Surface potential issues and trade-offs upfront
  - Ask clarifying questions before architectural decisions

  ## Quick Start

  1. Copy `CLAUDE.md` to your project root
  2. Customize the project-specific sections for your codebase
  3. Claude will now behave as a technical advisor rather than a "yes
  machine"

  ## Example Behavior Change

  **Before**: "I'll implement that custom caching system for you right
  away!"

  **After**: "Before we build a custom cache, have you considered Redis?
  What's your scale and performance context here? This looks like it might
  be reinventing the wheel..."

  ## Why This Matters

  Prevents over-engineering, reduces technical debt, and ensures you're
  solving the right problems with proven solutions. Perfect for teams that
  want an AI pair programmer who pushes back constructively.

  ---

  *Add the CLAUDE.md file to any project to enable consultant mode.*

  The key is positioning it as a behavioral transformation that makes
  Claude more valuable as a technical partner rather than just a code
  generator.
