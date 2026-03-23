# OpenCode Configuration README Design Specification

## Overview
This document specifies the design for a comprehensive README.md file for the OpenCode configuration repository located at `~/.config/opencode`. This configuration provides enhanced capabilities for OpenCode through custom skills, agents, commands, and plugins.

## Target Audience
- OpenCode users who want to leverage this enhanced configuration
- Developers maintaining or extending the configuration
- Users seeking to understand available capabilities

## Design Structure

### 1. Overview Section
**Purpose:** Provide high-level understanding of what this configuration offers.

**Content:**
- Brief description of the OpenCode configuration
- Key features and enhancements
- Prerequisites (OpenCode installation, environment setup)
- Quick summary of value proposition

### 2. Installation & Setup
**Purpose:** Guide users through getting started.

**Content:**
- How to use/apply this configuration
- Required environment variables (STITCH_API_KEY, OPENCODE_DOMAIN)
- Configuration file location and structure
- Verification steps

### 3. Skills Catalog
**Purpose:** Document all available skills with clear usage guidance.

**Content:**
- Table format with columns: Skill Name, Description, When to Use, Examples
- Skills to include:
  - design-md: Analyze Stitch projects and synthesize design systems
  - shadcn: Manage shadcn components and projects
  - agent-browser: Browser automation for AI agents
  - stitch-design: Unified entry point for Stitch design work
  - skill-creator: Create/update reusable OpenCode skills
  - react-components: Convert Stitch designs to React components
  - agent-creator: Create/update OpenCode agents
  - stitch-loop: Iterative website building with Stitch
  - enhance-prompt: Transform UI ideas into Stitch-optimized prompts
  - command-creator: Create/update reusable commands
  - react-ts-frontend: Modern React stack development

### 4. Agents Reference
**Purpose:** Document custom agent hierarchy and capabilities.

**Content:**
- Table format with columns: Agent Name, Purpose, Model, When Invoked
- Agents to include:
  - High complexity: creation-orchestrator, feature-lead, debug-lead
  - Medium complexity: reviewer, feature-manager, discovery, quick-lead
  - Low complexity: builder
- Explanation of agent hierarchy and dispatch patterns

### 5. Commands Guide
**Purpose:** Document available commands and their usage.

**Content:**
- Table format with columns: Command, Purpose, Syntax, Examples
- Commands to include:
  - create-agent: Create new agent definitions
  - create-skill: Create new skill definitions
  - create-command: Create new command definitions
  - debug: Debug code and systems
  - design-opencode: Design OpenCode configurations
  - feature: Manage feature development
  - medium-lead: Medium complexity task management
  - quick: Quick task execution

### 6. Configuration Details
**Purpose:** Explain the technical configuration structure.

**Content:**
- `opencode.json` structure breakdown
- Permission system explanation
- MCP server configurations (Stitch, Notion)
- Plugin system (superpowers integration)
- Model assignments and reasoning

### 7. Usage Examples
**Purpose:** Provide practical examples of common workflows.

**Content:**
- Example 1: Creating a new skill using skill-creator
- Example 2: Debugging code using debug command
- Example 3: Building React components with react-ts-frontend
- Example 4: Using Stitch for design work
- Best practices and patterns

### 8. Troubleshooting & FAQ
**Purpose:** Help users resolve common issues.

**Content:**
- Common issues and solutions
- Debugging tips
- How to extend or customize the configuration
- Contribution guidelines
- Support resources

## Design Principles

1. **Comprehensive but Organized:** All information should be available but well-structured
2. **User-Focused:** Prioritize information users need to effectively use the configuration
3. **Practical Examples:** Include concrete examples for all major features
4. **Clear Navigation:** Use clear headings and table of contents
5. **Maintainable:** Structure should be easy to update as configuration evolves

## Success Criteria
- Users can understand what capabilities are available
- Users can successfully set up and use the configuration
- Users can find appropriate skills/agents/commands for their tasks
- Users can troubleshoot common issues
- The README serves as a comprehensive reference document

## Implementation Notes
- Use GitHub-flavored markdown
- Include badges if applicable
- Use tables for structured information
- Include code blocks for configuration examples
- Link to external documentation where appropriate