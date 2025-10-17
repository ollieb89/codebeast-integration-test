# CodeBeast Integration Test Repository

This repository is used for testing GitHub-Linear integration commands.

## Purpose

Test environment for Epic 1 (GitHub-Linear Integration) validation.

## Test Data

- **Issues**: 10 diverse test issues (bugs, features, docs, performance, security)
- **Pull Requests**: 1 test PR with Linear references
- **Labels**: 15+ labels (priority, type, status, component)

## Commands Being Tested

1. `/integration:github-linear-sync` - Bidirectional sync
2. `/integration:github-to-linear` - GitHub → Linear import
3. `/integration:linear-to-github` - Linear → GitHub export
4. `/integration:sync-status` - Sync monitoring
5. `/integration:pr-task-link` - PR-task linking
6. `/integration:issue-to-task` - Issue conversion
7. `/integration:task-to-issue` - Task export
8. `/integration:task-from-pr` - Task creation from PR
9. `/integration:bulk-import` - Bulk operations
10. `/integration:cross-reference` - Reference management
11. `/integration:automation-setup` - Automation infrastructure
12. `/integration:conflict-resolve` - Conflict resolution

## Setup Date

$(date +%Y-%m-%d)
