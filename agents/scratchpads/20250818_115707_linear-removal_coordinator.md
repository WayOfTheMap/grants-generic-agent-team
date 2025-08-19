# Linear Reference Removal Coordination
**Date**: 2025-08-18
**Coordinator**: Main Coordinator Agent
**Project**: Remove Linear-specific references from agent markdown files

## Objective
Replace all Linear-specific references with generic project management best practices across all agent markdown files.

## Scope
- 6 files identified with Linear references
- Replace with tool-agnostic project management concepts
- Maintain functionality while removing vendor lock-in

## Files to Process
1. coordinator-agent.md
2. product-owner.md
3. lead-engineer.md
4. devops-agent.md
5. qa-expert.md
6. debugging-specialist.md

## Status
- [x] coordinator-agent.md - COMPLETED
- [x] product-owner.md - COMPLETED
- [x] lead-engineer.md - COMPLETED
- [x] devops-agent.md - COMPLETED
- [x] qa-expert.md - COMPLETED
- [x] debugging-specialist.md - COMPLETED

## Changes Log

### Summary of Changes Made
All Linear-specific references have been successfully removed and replaced with generic project management best practices across all 6 agent markdown files.

### Detailed Changes by File

#### 1. coordinator-agent.md (5 changes)
- Replaced "Linear MCP Server" with "Project Management Integration"
- Changed "Linear Integration Workflow" to "Project Management Workflow"
- Updated "Linear Project Structure" to "Project Management Structure"
- Modified "Coordinator's Linear Automation" to "Coordinator's Project Management Automation"
- Updated "Agent Handoff via Linear" to "Agent Handoff via Project Management System"
- Removed all Linear-specific API calls and replaced with generic commands

#### 2. product-owner.md (8 changes)
- Replaced "Linear MCP Server" with "Project Management Tools"
- Removed Linear-specific configuration from JSON
- Changed "Linear Integration for Product Owner" to "Project Management Integration for Product Owner"
- Updated "Product Owner's Linear Issue Template" to "Product Owner's Issue Template"
- Modified "Product Owner Linear Automation" to "Product Owner Task Automation"
- Changed "Requirements Workflow in Linear" to "Requirements Workflow in Project Management"
- Removed all Linear-specific command references (--mcp-server linear)
- Updated issue references from "LIN-123" format to generic "#123" format

#### 3. lead-engineer.md (2 changes)
- Changed "Linear Integration for Engineering" to "Project Management Integration for Engineering"
- Updated "Engineering Linear Issue Structure" to "Engineering Task Structure"
- Modified "Engineering Linear Automation" to "Engineering Task Automation"
- Removed Linear-specific commands and issue references

#### 4. devops-agent.md (2 changes)
- Changed "Linear Integration for DevOps" to "Project Management Integration for DevOps"
- Updated "DevOps Linear Issue Structure" to "DevOps Task Structure"
- Modified "DevOps Linear Automation" to "DevOps Task Automation"
- Removed Linear-specific deployment tracking commands

#### 5. qa-expert.md (2 changes)
- Changed "Linear Integration for QA" to "Project Management Integration for QA"
- Updated "QA Linear Issue Structure" to "QA Task Structure"
- Modified "QA Linear Automation" to "QA Task Automation"
- Removed Linear-specific test tracking commands

#### 6. debugging-specialist.md (2 changes)
- Changed "Linear Integration for Debugging" to "Project Management Integration for Debugging"
- Updated "Debugging Linear Issue Structure" to "Debugging Issue Structure"
- Modified "Debugging Linear Automation" to "Debugging Task Automation"
- Removed Linear-specific bug tracking commands

### Key Transformations Applied
1. **Tool References**: "Linear" → "project management system/tool"
2. **Issue References**: "Linear issues/tickets" → "tasks/work items"
3. **Commands**: Removed "--mcp-server linear" flags from all commands
4. **Issue IDs**: Changed "LIN-123" format to generic "#123" format
5. **Workflows**: Maintained agile/scrum principles while removing vendor-specific implementations
6. **Best Practices**: Focused on universal project management concepts rather than tool-specific features