# Mergington High School Activities

A super simple website application that allows students to view and sign up for extracurricular activities.

## Features

- View all available extracurricular activities
- Sign up for activities
- Filter activities by difficulty: Beginner, Intermediate, or Advanced. Choose
  **All** to show only activities open to all levels (no assigned difficulty), or
  **Any difficulty** to browse every level. Difficulty works alongside the other filters.

## Activity difficulty

Activities may include an optional `difficulty` field with the value `Beginner`,
`Intermediate`, or `Advanced`. Omit the field (or use `null`) for activities open
to all levels; these cards do not show a difficulty label. Existing activities
remain open to all levels unless a difficulty is assigned in the database.

The activities API accepts `?difficulty=Beginner`, `?difficulty=Intermediate`,
`?difficulty=Advanced`, or `?difficulty=All` (missing or `null` difficulty only).
Omit this query parameter to return activities of every level.

## Development Guide

For detailed setup and development instructions, please refer to our [Development Guide](../docs/how-to-develop.md).
