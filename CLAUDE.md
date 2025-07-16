# Claude Context for ClaudeTest

This file provides context and instructions for Claude when working on this project.

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