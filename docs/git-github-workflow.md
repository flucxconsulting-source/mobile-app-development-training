# Git and GitHub Workflow

GitHub is the source of truth for this training repository.

## Basic Flow

1. Pull the latest changes before starting work.
2. Make a small, focused change.
3. Run or verify the project when possible.
4. Commit with a clear message.
5. Push to GitHub.

## Commit Message Style

Use short, meaningful messages:

- `Add Kotlin setup exercise`
- `Document Android Studio emulator setup`
- `Create BMI calculator project scaffold`
- `Fix Compose state update bug`

## Branching

Use `main` for stable training material. For larger app projects or experiments, use feature branches:

```text
feature/bmi-calculator
feature/compose-state-practice
docs/android-studio-setup
```

## Learning Rule

When an error happens, document three things:

- The exact error message.
- The cause in plain language.
- The fix and how to recognize the issue next time.
