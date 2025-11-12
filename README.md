# LlamaForge Test Repository

This is a test repository for the LlamaForge PR Test Generator system.

## Purpose

This repository is used to test the automated test generation capabilities of LlamaForge. When you open a PR, the LlamaForge bot will automatically generate unit tests and snapshot tests for your changes.

## Setup

This repository is configured with:
- `.bot-policy.yml` - Bot configuration for test generation
- GitHub Actions workflows for CI/CD
- Sample code to test with

## Testing

1. Create a PR with some code changes
2. The LlamaForge bot will automatically:
   - Analyze your PR diff
   - Generate appropriate tests
   - Create a follow-up PR with the generated tests

## Sample Code

See the `src/` directory for sample code that can be tested.

## How to Test LlamaForge

1. Make changes to `src/utils.ts` or add new files
2. Create a pull request
3. The LlamaForge bot will detect the PR and generate tests
4. Review the generated test PR
