# React Router v6 useNavigate Hook Error

This repository demonstrates a common issue encountered when using the `useNavigate` hook in React Router v6: redirects failing due to the hook being uninitialized.  The problem typically occurs when attempting a redirect within a component's `useEffect` hook with an empty dependency array `[]`. 

The `bug.js` file shows the problematic code, while `bugSolution.js` provides a solution that ensures the `useNavigate` hook is properly initialized before attempting navigation.