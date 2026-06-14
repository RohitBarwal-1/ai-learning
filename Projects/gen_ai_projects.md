# Meeting Notes Summarizer
### Feature
Automatically generate:
- Summary
- Action items
- Risks
- Decisions taken
- Follow-up tasks
### Input Context
- Meeting transcript
- Team information
- Meeting type
### Output
```JSON
    {
    "summary": "...",
    "action_items": [],
    "risks": [],
    "decisions": []
    }
```

# Jira Ticket Writer / User Story Generator
### Feature
- Convert plain English requirements into structured Jira tickets.
### Input
- Plain Text: Users should login using Google OAuth.
- Meeting Transcript
### Output
    Story
    Acceptance Criteria
    Technical Notes
    Dependencies

# PRD Generator
### Feature
- Generate Product Requirement Documents.
### Input
- Feature idea.
- Meeting Transcript
### Output
- Objective
- Scope
- User stories
- Success metrics
- Risks
