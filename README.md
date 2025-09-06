# janet-ai-repo
Janet's Github Repository for AI-powered projects, demos, and experiments.
# Loan Doc eSign – BA & AI Showcase

This repository demonstrates **Business Analysis skills** applied to a real-world scenario:  
**Upgrade Loan application with Co-siner with eSign **

The focus is on **requirements analysis** and using **AI tools** to accelerate the creation of:
- User stories
- Acceptance criteria (INVEST + Gherkin format)
- Backlog/tickets (exportable to Jira or GitHub Issues)

## Structure
- `01_requirements/` – Problem statement, sample requirements, assumptions.
- `02_ai-prompts/` – AI prompts + raw and refined outputs for transparency.
- `03_user-stories/` – Final curated epics, stories, and acceptance criteria.
- `04_backlog/` – Stories exported in CSV format, ready for import into Jira/GitHub.

## Example Workflow
1. **Requirement**: “System must allow creation of an envelope with loan documents via REST API.”  
2. **AI Prompt** (see `02_ai-prompts/requirement_to_story.prompt.md`) → generates draft story + AC.  
3. **BA Review**: Raw AI output refined for clarity and INVEST compliance.  
4. **Final User Story**: Stored in `03_user-stories/user_stories.md`.  
5. **Ticket**: Exported to `04_backlog/jira_import.csv`.
