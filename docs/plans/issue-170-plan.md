# Issue #170: Add 10 template agents

## Summary

Create 10 pre-configured agent templates for import from My Agents screen.

## Root Cause

Users start from scratch with no templates.

## Solution

1. Create 10 templates in apps/desktop/src/assets/agent-templates/
2. Add template browser UI
3. Implement backend commands
4. Document location

## Files to Modify

- tauri.ts: template commands
- CreateAgentWizard.tsx: template option
- AgentList.tsx: Browse button
- agents.rs: implement commands

## New Files

- templates.json
- 10 template dirs (SOUL.md, IDENTITY.md)
- TemplateBrowserModal.tsx

## Steps

1. Create content
2. Backend commands
3. Frontend UI
4. Test

## Tests

- Unit, Integration, E2E
- Edge cases

## Success

- 10 templates
- Working browser
- Import flow
- Offline