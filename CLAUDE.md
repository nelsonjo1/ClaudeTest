# Claude Context for ClaudeTest

This file provides context and instructions for Claude when working on this project.

## Important Instructions

Always read PLANNING.md at the start of every new conversation, check TASKS.md before starting your work, mark completed tasks to TASKS.md immediately, and add newly discovered tasks to TASKS.md when found.

## Project Overview

This is a Task Manager demo application built with React and Vite. It demonstrates modern React patterns and features a clean, gradient-styled UI.

## Key Commands

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview

# Run linter
npm run lint
```

## Project Structure

- `src/App.jsx` - Main application component with task management logic
- `src/App.css` - Custom styles with gradient theme and animations
- `src/main.jsx` - Application entry point
- `src/index.css` - Global styles
- `vite.config.js` - Vite configuration

## Key Features

1. **Task Management**: Add, complete, and delete tasks
2. **Filtering**: Filter tasks by All, Active, or Completed status
3. **Responsive Design**: Works on mobile and desktop
4. **Modern UI**: Gradient styling with smooth animations
5. **State Management**: Uses React hooks (useState) for state

## Development Notes

- The app uses functional components with hooks
- No external state management library (uses local component state)
- Styling uses vanilla CSS with modern features (gradients, transforms, transitions)
- The project is set up with ESLint for code quality

## GitHub Repository

Repository URL: https://github.com/nelsonjo1/ClaudeTest

## Future Enhancements

Potential improvements that could be made:
- Add localStorage persistence
- Add drag-and-drop to reorder tasks
- Add due dates and priorities
- Add categories or tags
- Add dark/light theme toggle
- Add unit tests
- Convert to TypeScript

## Session Summary

### Initial Session (2025-07-16)

In this session, we successfully:

1. **Created a React + Vite Application**
   - Initialized a new Vite project with React template
   - Set up the development environment
   - Installed all necessary dependencies

2. **Built a Task Manager Demo**
   - Replaced the default Vite template with a functional task manager
   - Implemented core features: add, complete, delete, and filter tasks
   - Added an active task counter
   - Fixed deprecated `onKeyPress` warning by using `onKeyDown`

3. **Designed a Modern UI**
   - Created a gradient-themed interface with purple/blue colors
   - Added smooth animations and transitions
   - Implemented responsive design for mobile devices
   - Styled all interactive elements with hover effects

4. **Set Up Version Control**
   - Initialized Git repository
   - Created initial commit with all project files
   - Authenticated GitHub CLI (after user completed web auth)
   - Created and pushed to GitHub repository: nelsonjo1/ClaudeTest
   - Resolved merge conflict with remote README

5. **Created Project Documentation**
   - **CLAUDE.md**: Added context file with project overview and instructions
   - **PLANNING.md**: Created comprehensive planning document with vision, architecture, tech stack, and required tools
   - **TASKS.md**: Built detailed task list organized into 10 milestones plus future enhancements
   - Updated CLAUDE.md with task tracking instructions

6. **Established Development Workflow**
   - Set up clear instructions for future Claude sessions
   - Created a structured approach to task management
   - Documented all key commands and project structure

The project is now fully functional, well-documented, and ready for future development following the roadmap in TASKS.md.