# Project Guidelines for GitHub Copilot

## Technology Stack

- React Native
- Tamagui UI Framework
- TypeScript

## Architecture Principles

- Follow Vertical Slice Architecture
- Adhere to Single Responsibility Principle (SRP)
- Feature-first organization

## Directory Structure

```
src/
├── features/           # Feature slices
│   ├── auth/          # Authentication feature
│   │   ├── api/       # API calls
│   │   ├── components/# UI components
│   │   ├── hooks/     # Custom hooks
│   │   └── types/     # Type definitions
│   └── [feature]/     # Other features follow same pattern
├── shared/            # Shared utilities and components
│   ├── components/    # Common UI components
│   ├── hooks/         # Common hooks
│   ├── utils/         # Utility functions
│   └── types/         # Common type definitions
└── app/              # App-wide configurations
    ├── navigation/   # Navigation setup
    └── providers/    # Context providers
```

## Coding Standards

1. Components:

- Use functional components with hooks
- Keep components focused and small
- Implement proper prop typing

2. State Management:

- Use React Context for global state
- Keep state close to where it's used
- Implement proper state isolation per feature

3. Styling:

- Use Tamagui's styling system
- Create reusable tokens and themes
- Maintain consistent styling patterns

4. Testing:

- Write unit tests for business logic
- Test components in isolation
- Implement integration tests for features

## Feature Implementation Guidelines

1. Create a new directory under `features/` for each feature
2. Keep feature-specific code within its slice
3. Share common code through the `shared/` directory
4. Implement proper error boundaries
5. Add proper TypeScript types

## Performance Considerations

- Implement proper memo usage
- Optimize re-renders
- Use proper asset optimization
- Implement lazy loading where applicable

## Documentation Requirements

- Add JSDoc comments for functions
- Document complex business logic
- Include usage examples in components
- Keep README updated for each feature

## Security Guidelines

- Implement proper input validation
- Use secure storage for sensitive data
- Follow React Native security best practices
- Implement proper authentication flows

## Application Requirements

- create react native project by using expo

- Implementation should be based on the requirements specification document located in the `/docs` folder
- Follow the UI/UX design specifications from wireframes in the `/docs` folder
- Requirements and wireframes in the docs folder serve as the source of truth for:
  - Feature specifications
  - UI/UX implementation details
  - Business logic requirements
  - Data flow and state management patterns
  - Screen layouts and navigation flows

Note: Always refer to the `/docs` folder for the most up-to-date requirements and design specifications before implementing any feature.
