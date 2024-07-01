# To-Do Dashboard

## Introduction
The **To-Do Dashboard** is a simple dashboard application to track to-do tasks. This project uses React.js to build the application.

## Basic Requirements
Create a React application and Feel free to use any UI framework or libraries. Below are the key requirements:

1. **Task List**: 
    - Render dynamically using the provided API endpoint.
    - Bell icon color represents task priority (red – High, yellow – Medium, blue – Low).
    - "Mark as done" button visible for "in progress" tasks.
    - Apply client-side pagination (8 items per page).

2. **Activity Feed**:
    - Design using dummy data.

3. **Tasks by Priorities Chart**:
    - Display full task count by priority using the provided API endpoint.

### API Endpoint
- **URL**: [https://6363c8f68a3337d9a2e7d805.mockapi.io/api/to-do](https://6363c8f68a3337d9a2e7d805.mockapi.io/api/to-do)
- **Method**: GET
- **Response**: 
    ```json
    [
      {
          "id": "1c62e7a0-bb4a-4bf6-aec4-cf6773a44a1d",
          "name": "Jim Estrada",
          "priority": "LOW",
          "todo": "Cevlurhur gatjufej milomse ipoka nef va fawotge.",
          "completed": false,
          "createdAt": "2022-10-31T08:40:26.550Z"
      },
    ]
    ```

## Technical Requirements

### Must Haves
- React with ES6+
- React functional components with React hooks
- Manage state with Redux or Context API
- Follow React best practices
- Follow the best application folder structure
- Mobile responsiveness
- Resolve all console errors and warnings

### Extra/Bonus Points
- TypeScript
- Usage of Next.js framework
- Server-side rendering
- Usage of a linter
- Styled-Components
- Unit tests

## Appendix - How to use Figma
- **UI Design**: [Figma Design Link](https://www.figma.com/design/a0vdOyubUVSK5WJMu3Uj9e/To-Do-Dashboard-%7C-Assignment-v1.0-%7C-Beta-Launch?node-id=0-1&t=l00X49xEs3mPR2po-1)
