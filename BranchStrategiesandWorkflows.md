# Design and Implement Branch Strategies and Workflows

1. ## Explore branch workflow types


[Git Branching Workflows - Scrimba Explain](https://scrimba.com/explain/guide0l5geebrt)

### Github Flow
Core principles:-
    -`Single main branch`: The main branch is always deployable and contains production-ready code.
    -`Feature branches`: All development work happens in short-lived feature branches created from main.
    -`Pull request workflow`: Changes are reviewed and discussed through pull requests before merging.
    -`Continuous deployment`: Successful merges to main trigger automated deployment to production.
    -`Rapid iteration`: Features are deployed quickly, enabling fast feedback and course correction.

### Forking workflow for opensource stuff
Distributed collaboration model:-
    -`Individual repositories`: Each contributor maintains their own complete copy of the project.
    -`Controlled integration`: Project maintainers review and merge contributions from external forks.
    -`Security isolation`: External contributors cannot directly impact the main repository.
    -`Scalable contribution`: Supports unlimited numbers of contributors without access management complexity.

2. ## Feature Branch Workflow

[Feature Branch Workflow - Scrimba Explain](https://scrimba.com/explain/guide0g50re115)

When to open pull requests:-
    -`Early collaboration`: Share wireframes, architectural decisions, or proof-of-concepts.
    -`Seeking guidance`: Request help when blocked or needing expert input.
    -`Ready for review`: Complete implementation ready for final validation.
    -`Work in progress`: Draft pull requests for ongoing feedback and transparency.
Pull request best practices:

Clear descriptions: Explain what, why, and how of your changes.
Visual aids: Include screenshots, diagrams, or demo links when relevant.
Reviewer guidance: Use @mentions to request specific expertise.
Template usage: Follow team templates for consistency.

3. ## Explore Git branch model for continuous delivery

[Git Branching for CD - Explain](https://scrimba.com/explain/guide0l59qfl51)

Main Branch Stability:-
    -`Single source of truth`: The main branch is the exclusive path for production releases.
    -`Production readiness`: Main branch must always be in a deployable state.
    -`Branch protection`: Implement comprehensive branch policies to prevent direct commits.
    -`Gated changes`: All modifications flow through pull requests exclusively.
    -`Release tracking`: Tag all production releases with semantic Git tags.