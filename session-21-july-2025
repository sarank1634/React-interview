## 🔰 Beginner-Level React Questions

**1. What is React?**
A JavaScript library by Facebook for building fast, dynamic UIs using a component-based architecture.

**2. What are components in React?**
Reusable pieces of UI. Two types:

* Functional Components
* Class Components

**3. What is JSX?**
JSX stands for JavaScript XML. It allows HTML-like syntax in JavaScript, which React transforms into `React.createElement()` calls.

**4. Difference between Functional and Class Components?**

| Functional     | Class                  |
| -------------- | ---------------------- |
| Uses functions | Uses ES6 classes       |
| Supports Hooks | Uses lifecycle methods |
| Cleaner syntax | More boilerplate       |

**5. What is state in React?**
A built-in object to store dynamic data within a component. State changes trigger re-rendering.

**6. What are props in React?**
Props are short for properties. They are read-only inputs passed from parent to child.

**7. Difference between props and state?**

* Props: Passed from parent, immutable.
* State: Local, mutable.

**8. What is a key in React and why is it important?**
A unique identifier for list items. Helps React identify which items changed, improved performance.

**9. How does React handle events?**
Using camelCase syntax:

```jsx
<button onClick={handleClick}>Click</button>
```

**10. What is conditional rendering?**
Rendering different UI based on conditions.
Example:

```jsx
{isLoggedIn ? <Logout /> : <Login />}
```

---

## ⚡ Intermediate-Level React Questions

**11. What is the Virtual DOM?**
A lightweight copy of the real DOM. React updates the Virtual DOM, compares it with the previous version (diffing), and applies minimal updates to the real DOM (reconciliation).

**12. What are Hooks in React?**
Special functions that let functional components use state and other features.
Common Hooks:

* `useState()`
* `useEffect()`
* `useRef()`
* `useContext()`
* `useMemo()`

**13. What is useState()?**
A Hook for managing state in functional components:

```jsx
const [count, setCount] = useState(0);
```

**14. What is useEffect()? How is it different from lifecycle methods?**
Used for side effects like fetching data, timers, or subscriptions.
Runs after render — replaces `componentDidMount`, `componentDidUpdate`, and `componentWillUnmount`.

**15. Controlled vs Uncontrolled Components?**

* **Controlled**: React controls input via state.
* **Uncontrolled**: Uses refs; DOM manages input.

**16. What is lifting state up?**
Moving shared state to the closest common ancestor component to manage it centrally.

**17. How to pass data from child to parent?**
Via callback functions:

```jsx
Parent: <Child onSend={handleData} />
Child: props.onSend(data)
```

**18. What is Context API?**
A global state system to avoid prop drilling.
Example: Theme, Language, Auth.

**19. What is prop drilling? How to avoid it?**
Passing props through many layers.
Avoid using:

* Context API
* Redux / Zustand

**20. What are Fragments?**
Used to group elements without adding extra DOM nodes:

```jsx
<></> or <React.Fragment></React.Fragment>
```

---

## 🔥 Advanced-Level React Questions

**21. What is React Reconciliation?**
The process of comparing Virtual DOM trees to find changes and update the real DOM efficiently.

**22. How does React optimize performance?**

* Virtual DOM
* Keys in lists
* `React.memo`, `useMemo`, `useCallback`
* Code-splitting
* Lazy loading
* Avoid unnecessary re-renders

**23. What is memoization?**
Caching expensive computations or components to prevent recalculations:

* `React.memo()` – avoids re-render if props don't change.
* `useMemo()` – memoize values.
* `useCallback()` – memoize functions.

**24. Difference between `useEffect`, `useLayoutEffect`, and `useInsertionEffect`?**

| Hook                 | Runs After DOM Paint? | Use Case                 |
| -------------------- | --------------------- | ------------------------ |
| `useEffect`          | ✅                     | API calls, subscriptions |
| `useLayoutEffect`    | ❌ (before paint)      | DOM measurements         |
| `useInsertionEffect` | ❌ (CSS-in-JS tools)   | Inject styles early      |

**25. React's Rendering Process?**

* Renders virtual DOM
* Diffs with previous virtual DOM
* Reconciles minimal changes to real DOM

**26. Handling side effects?**
Using `useEffect` for:

* Fetching data
* Subscriptions
* Timers
* Cleanup on unmount

**27. What are Higher-Order Components (HOC)?**
Functions that take a component and return a new component with added features.

```jsx
const WithLogger = (Component) => (props) => { ... }
```

**28. What are Render Props?**
Sharing logic via props that are functions:

```jsx
<DataProvider render={(data) => <Chart data={data} />} />
```

**29. What are Error Boundaries?**
Class components that catch JavaScript errors:

```js
componentDidCatch(error, info)
```

**30. What are Custom Hooks?**
Functions starting with `use` that encapsulate reusable logic.
Example:

```js
function useLocalStorage(key, value) { ... }
```

---

## 🧠 React Ecosystem & Tooling Questions

**31. What is Redux?**
A global state container. It uses:

* Store (holds state)
* Actions (describe changes)
* Reducers (update state)

**32. Redux vs Context API?**

| Feature     | Redux         | Context API   |
| ----------- | ------------- | ------------- |
| Use case    | Complex state | Simple global |
| Middleware  | Yes           | No            |
| Boilerplate | More          | Less          |

**33. What is Next.js?**
A React framework for:

* Server-side rendering (SSR)
* Static generation (SSG)
* API routes
* File-based routing

**34. Server-side rendering in React?**
Use `Next.js` or `ReactDOMServer.renderToString()` to render components to HTML on the server.

**35. What is React Router?**
Library to handle routing in React SPA using:

* `<BrowserRouter>`, `<Routes>`, `<Route>`, `<Link>`

**36. What is React DevTools?**
A Chrome/Firefox extension to inspect the React component tree, props, and state.

**37. What is code splitting?**
Breaking the app into smaller bundles to load only what's needed. Use:

* `React.lazy()`
* `Suspense`

**38. What are Portals?**
Render a component outside the root DOM node:

```js
ReactDOM.createPortal(child, container)
```

**39. Suspense and Lazy Loading?**

* `lazy()`: Dynamically import components.
* `Suspense`: Fallback UI until lazy-loaded components are ready.

**40. Performance Optimization in React Apps?**

* Use `React.memo`, `useMemo`, `useCallback`
* Code splitting
* Virtualization (e.g., react-window)
* Lazy loading
* Debounce/throttle inputs
* Avoid unnecessary state updates


