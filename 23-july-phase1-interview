Here are **100 React Interview Questions with Key Answers**, categorized for maximum clarity:

---

## 🔰 Beginner-Level React Questions (1–25)

1. **What is React?**
   A JavaScript library by Meta for building user interfaces with a component-based architecture.

2. **What are components in React?**
   Independent, reusable pieces of UI. Can be class or functional components.

3. **What is JSX?**
   JavaScript XML – syntax extension that looks like HTML and is used to describe UI.

4. **Difference between class and functional components?**

   * Class: Uses `class`, lifecycle methods.
   * Functional: Uses hooks, simpler syntax.

5. **What is a state in React?**
   An object that holds data that influences output and behavior.

6. **What are props?**
   Inputs to components; passed from parent to child.

7. **Difference between props and state?**
   Props are immutable; state is mutable and managed inside the component.

8. **What is the virtual DOM?**
   Lightweight in-memory copy of the real DOM that React updates efficiently.

9. **Why use React?**
   Fast rendering, component reusability, strong community, virtual DOM, hooks.

10. **How to create a React app?**
    Using `npx create-react-app my-app`.

11. **What is `create-react-app`?**
    A toolchain to scaffold React projects with zero config.

12. **Controlled vs Uncontrolled Components?**

    * Controlled: Form data handled by state.
    * Uncontrolled: Form data handled by DOM refs.

13. **How to handle forms in React?**
    Use state to control input values and handle submit events.

14. **What is conditional rendering?**
    Render different UI elements based on conditions (`if`, ternary, etc.).

15. **What are React fragments?**
    Used to group multiple elements without adding extra nodes (`<> </>`).

16. **What is a key prop?**
    A unique identifier to help React identify which items have changed.

17. **What is a synthetic event?**
    A cross-browser wrapper around native events.

18. **How to pass data from parent to child?**
    Using props: `<Child name="mystry" />`.

19. **How to pass data from child to parent?**
    Via callback function: `props.onData(data)`.

20. **What are default props?**
    Default values for props if none are passed: `Component.defaultProps`.

21. **What is `useState()`?**
    Hook to add local state to functional components.

22. **What is `useEffect()`?**
    Hook to handle side effects like fetching, timers, etc.

23. **What is prop drilling?**
    Passing props through many layers unnecessarily.

24. **How to avoid prop drilling?**
    Use Context API or state management libraries.

25. **What is the purpose of `render()`?**
    Returns UI to be rendered (used in class components).

---

## ⚡ Intermediate-Level React Questions (26–60)

26. **Explain component lifecycle (class).**
    Mounting → Updating → Unmounting (`constructor`, `render`, `componentDidMount`, etc.).

27. **What is `componentDidMount()`?**
    Called after component mounts; best for API calls.

28. **What is `componentDidUpdate()`?**
    Called after component updates (e.g., after prop/state change).

29. **What is `componentWillUnmount()`?**
    Cleanup logic before component is removed from DOM.

30. **Difference between `useEffect()` and lifecycle methods?**
    `useEffect()` can replace `componentDidMount`, `componentDidUpdate`, and `componentWillUnmount`.

31. **What is React Router?**
    Library for routing in React apps.

32. **How to handle routing in React?**
    Using `<BrowserRouter>`, `<Route>`, `<Link>` from `react-router-dom`.

33. **What is lazy loading?**
    Dynamically loading components only when needed using `React.lazy()`.

34. **What is `React.Suspense`?**
    Wrapper that shows fallback while lazy components load.

35. **What are higher-order components (HOC)?**
    Functions that take a component and return a new one with enhanced features.

36. **What are render props?**
    A prop that accepts a function to render dynamic content.

37. **What is Context API?**
    A way to share data globally without prop drilling.

38. **How to use `useContext()`?**
    `const value = useContext(MyContext);`.

39. **What is `useRef()`?**
    Returns a mutable ref object; commonly used to access DOM.

40. **What is `useMemo()`?**
    Memoizes expensive calculations to avoid re-execution.

41. **What is `useCallback()`?**
    Memoizes functions to prevent re-creation on re-render.

42. **What is memoization in React?**
    Caching results of expensive computations.

43. **What is `React.memo()`?**
    HOC to memoize functional components.

44. **Difference between `useMemo()` and `React.memo()`?**

    * `useMemo`: Caches computation.
    * `React.memo`: Caches component rendering.

45. **What are custom hooks?**
    Reusable functions that use other hooks.

46. **How to create a custom hook?**
    Prefix function with `use`, call hooks inside it.

47. **Local vs Global state?**

    * Local: Component-specific.
    * Global: Shared across components.

48. **Redux vs Context API?**

    * Redux: Complex logic, middleware.
    * Context: Simpler, for light use.

49. **What is Redux?**
    Predictable state container using actions, reducers, and store.

50. **What are actions in Redux?**
    JS objects describing what to do (`type`, `payload`).

51. **What are reducers?**
    Pure functions to change state based on actions.

52. **What is the Redux store?**
    Centralized state container.

53. **What is `connect()` in Redux?**
    HOC to connect components to the Redux store.

54. **What is Redux Toolkit?**
    Official, modern way to write Redux logic faster.

55. **What is thunk middleware?**
    Allows async actions in Redux.

56. **What is async/await with `useEffect()`?**
    Wrap async calls inside `useEffect` using inner functions.

57. **What is error boundary?**
    Special component to catch errors in render phase.

58. **What is `componentDidCatch()`?**
    Lifecycle method to catch and handle errors.

59. **How to fetch API data in React?**
    Use `fetch()` or `axios` inside `useEffect()`.

60. **What is `useLayoutEffect()`?**
    Similar to `useEffect()` but runs synchronously after DOM changes.

---

## 🚀 Advanced-Level React Questions (61–85)

61. **Difference between `useEffect()` and `useLayoutEffect()`?**
    `useLayoutEffect()` runs before paint; used for DOM measuring.

62. **Explain reconciliation.**
    Process where React compares virtual DOM and updates only changed parts.

63. **How does React handle re-renders?**
    Triggers re-render when state/props change and updates diffed parts.

64. **What causes unnecessary re-renders?**
    Changing state/props that didn’t actually change.

65. **How to avoid unnecessary re-renders?**
    Use `React.memo`, `useMemo`, `useCallback`.

66. **What is a key in list rendering?**
    Unique identifier for each list item to help reconciliation.

67. **How to improve React performance?**
    Code splitting, memoization, virtualization, avoiding re-renders.

68. **What are pure components?**
    Components that render same output for same props/state.

69. **Difference between pure function and pure component?**

    * Pure function: No side effects.
    * Pure component: No re-render unless props/state change.

70. **Explain batching.**
    React groups multiple state updates into one render.

71. **What is concurrent mode?**
    React mode for interruptible rendering for smoother UX.

72. **What is Suspense for data fetching?**
    Experimental API for handling loading states declaratively.

73. **How does React handle accessibility?**
    Follows WAI-ARIA, supports screen readers, semantic HTML.

74. **What are portals in React?**
    Render children outside DOM hierarchy: `ReactDOM.createPortal`.

75. **How does SSR work in React?**
    Server renders HTML and sends to client for faster first load.

76. **What is Next.js?**
    React framework with SSR, file-based routing, and API routes.

77. **What is static site generation (SSG)?**
    Pages pre-rendered at build time for fast delivery.

78. **SSR vs CSR?**

    * SSR: Server-rendered HTML.
    * CSR: Renders in browser after JS loads.

79. **What is hydration?**
    React attaches event listeners to static HTML after load.

80. **How does reconciliation differ from rendering?**
    Reconciliation compares elements; rendering updates DOM.

81. **What are forward refs?**
    Pass refs through components using `React.forwardRef`.

82. **What is uncontrolled input?**
    Input managed by DOM, not state.

83. **What is `dangerouslySetInnerHTML`?**
    Inject raw HTML — used with caution to avoid XSS.

84. **Declarative vs imperative code in React?**
    Declarative: Describe what to do.
    Imperative: Define how to do it.

85. **How React handles browser events?**
    Uses event delegation via synthetic events.

---

## 🌐 Ecosystem & Tooling (86–100)

86. **What is Vite?**
    Fast dev server and bundler for modern apps.

87. **What is Babel?**
    JavaScript compiler that converts modern JS to browser-compatible code.

88. **What is Webpack?**
    Module bundler that transforms and bundles resources.

89. **What is ESLint?**
    Tool for identifying and fixing code quality issues.

90. **How to write reusable components?**
    Use props, avoid hardcoded logic, keep components small.

91. **What is tree shaking?**
    Removing unused code during bundling to reduce size.

92. **What is code splitting?**
    Splitting app code into chunks to load only necessary parts.

93. **What is TypeScript in React?**
    Adds type safety to JavaScript. Used in `.tsx` files.

94. **How to type props with TypeScript?**
    Define an interface:

    ```ts
    interface Props { name: string }
    ```

95. **What is unit testing in React?**
    Testing individual components or logic in isolation.

96. **What is Jest?**
    Testing framework for JavaScript, often used with React.

97. **What is React Testing Library?**
    Library for testing UI behavior, not internals.

98. **How to test components?**
    Render, simulate user interactions, and assert outputs.

99. **What is Storybook?**
    Tool to build and document UI components in isolation.

100. **How to deploy a React app?**
     Build using `npm run build`, host on Netlify, Vercel, or GitHub Pages.

---

✅ Want this exported to PDF or Google Docs?
✅ Need mock test mode or flashcards?

Just say **“Give me PDF”** or **“Mock test mode ON”** and I’ll get it ready.
