# Claude GitHub Actions Test Repository

This repository is set up to test Claude GitHub Actions integration.

## How it works

1. Create an issue or pull request
2. Mention `@claude` in a comment, issue description, or PR review
3. Claude will automatically respond with assistance

## Setup Instructions

1. Install the Claude GitHub App: https://github.com/apps/claude
2. Add your authentication secret to repository secrets:
   - For Claude Max users: `CLAUDE_CODE_OAUTH_TOKEN`
   - For API users: `ANTHROPIC_API_KEY`
3. The workflow in `.github/workflows/claude.yml` will handle the rest

## Testing

Try creating an issue and mentioning `@claude` with a question about the code!