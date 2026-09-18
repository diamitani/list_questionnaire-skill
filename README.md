# List Creation — Question Flow

**Category:** 99-uncategorized
**Source:** list_questionnaire.md
**Generated:** 2026-08-28

## Overview

This repository contains a generalized AI agent skill ready for use with Claude Code, Hermes Agent, or any PAL-compliant agent framework.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/diamitani/list_questionnaire-skill.git
   ```

2. Import the skill into your agent framework:
   ```bash
   # for AI Agents (Claude Code, Cursor, Copilot, Cline, Windsurf, Hermes)
   @skill SKILL.md
   
   # For Hermes Agent
   skill_view(name='list_questionnaire')
   ```

## Configuration

This skill uses placeholder values for company-specific data:
- `{COMPANY_NAME}` — Replace with your company name
- `{COMPANY_SLUG}` — Replace with your company URL slug
- `{USER_HOME}` — Replace with the user's home directory
- `{USER_NAME}` — Replace with user's name

## License

MIT License — See LICENSE file for details.

## Support

Questions? Open an issue on GitHub.
