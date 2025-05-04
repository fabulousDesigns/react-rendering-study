# React Rendering Study 📘

## 🚀 Purpose
This repository is a 3-week intensive study plan aimed at deeply understanding **React's rendering behavior**, optimization techniques, and how they relate to **V8 JavaScript engine** internals.

If you're tired of flaky performance and confusing re-renders, this repo is your roadmap to becoming a React rendering expert.

## 📚 Structure
```
react-rendering-study/
├── README.md                   <-- Summary and usage instructions
├── checklist.md                <-- Full day-by-day study guide
├── progress-log.md            <-- Daily/weekly study progress
├── experiments/                <-- Hands-on demos you build
└── resources/                  <-- Links, diagrams, notes
```

## 🗓️ Study Timeline
- **Week 1**: React Component Rendering Fundamentals
- **Week 2**: Advanced Rendering Optimization
- **Week 3**: V8-Specific Optimizations for React

## ✅ How to Use
1. Follow the `checklist.md` step-by-step.
2. Build small experiments under `experiments/`.
3. Log your learning daily in `progress-log.md`.
4. Save key diagrams/articles in `resources/`.

## 💡 Bonus Tips
- Use **React Developer Tools** to inspect renders.
- Try **Why Did You Render** to catch re-render traps.
- Compare React rendering with how **V8** optimizes JS behind the scenes.

---

Ready to dive in? Start with the [checklist.md](./checklist.md)!

---

# 📅 Study Checklist: React Rendering Deep Dive

## Week 1: React Component Rendering Fundamentals (5 Days)

### Day 1–2: Core React Rendering Process
- 🔄 Study the render and commit cycle:
  - [Render and Commit – React Docs](https://react.dev/learn/render-and-commit)
  - [Rendering Elements – Legacy Docs](https://legacy.reactjs.org/docs/rendering-elements.html)
- ⚙️ Learn about React’s component lifecycle:
  - [Interactive Lifecycle Methods Diagram](https://projects.wojtekmaj.pl/react-lifecycle-methods-diagram/)
  - [State and Lifecycle – Legacy Docs](https://legacy.reactjs.org/docs/state-and-lifecycle.html)

### Day 3: State and Props Behavior
- 📦 Understand React's state mechanism:
  - [State: A Component’s Memory](https://react.dev/learn/state-a-components-memory)
  - [Updating Objects in State](https://react.dev/learn/updating-objects-in-state)
  - [Updating Arrays in State](https://react.dev/learn/updating-arrays-in-state)
- 📸 Understand the snapshot model:
  - [State as a Snapshot](https://react.dev/learn/state-as-a-snapshot)
- 📬 Props and their effect on rendering:
  - [Passing Props to a Component](https://react.dev/learn/passing-props-to-a-component)
  - [Choosing the State Structure](https://react.dev/learn/choosing-the-state-structure)

### Day 4: Component Hierarchies and Re-render Propagation
- 👨‍👩‍👧 Understand parent-child rendering:
  - [Preserving and Resetting State](https://react.dev/learn/preserving-and-resetting-state)
  - [Sharing State Between Components](https://react.dev/learn/sharing-state-between-components)
- 🧠 Learn React’s reconciliation algorithm:
  - [Virtual DOM and Internals – Legacy Docs](https://legacy.reactjs.org/docs/faq-internals.html)

### Day 5: Hands-On Experimentation
- 🔬 Build small apps to visualize re-renders
- 🧰 Tools:
  - [React Developer Tools Extension](https://react.dev/learn/debugging-components)
  - [Why Did You Render – GitHub](https://github.com/welldone-software/why-did-you-render)

## Week 2: Advanced React Rendering Concepts (5 Days)

### Day 1–2: Render Optimization Techniques
- 🧠 Memoization:
  - [React.memo API](https://react.dev/reference/react/memo)
  - [useMemo Hook](https://react.dev/reference/react/useMemo)
  - [useCallback Hook](https://react.dev/reference/react/useCallback)
- ⚠️ Hook dependencies and overuse:
  - [You Might Not Need an Effect](https://react.dev/learn/you-might-not-need-an-effect)
  - [Separating Events from Effects](https://react.dev/learn/separating-events-from-effects)

### Day 3: Context API and Rendering
- 🌐 Learn how Context affects rendering:
  - [Passing Data Deeply with Context](https://react.dev/learn/passing-data-deeply-with-context)
  - [useContext Hook](https://react.dev/reference/react/useContext)
  - [Context.Provider](https://react.dev/reference/react/Context#contextprovider)

### Day 4: React Internals
- 🧵 Study React Fiber:
  - [React Fiber Architecture (GitHub)](https://github.com/acdlite/react-fiber-architecture)
  - [A Complete Guide to React Rendering Behavior](https://blog.logrocket.com/complete-guide-rendering-behavior-react/)
- 🔍 Diffing algorithm:
  - [Optimizing Performance – Legacy Docs](https://legacy.reactjs.org/docs/optimizing-performance.html)
  - [React Re-renders Guide](https://tkdodo.eu/blog/react-rendering)

### Day 5: Performance Testing and Analysis
- 🧪 Master measurement tools:
  - [Profiler API](https://react.dev/reference/react/Profiler)
  - [Measuring Performance](https://react.dev/learn/debugging-performance)

## Week 3: React with V8 Specific Optimizations (5 Days)

### Day 1–2: V8’s JavaScript Optimization
- ⚙️ How V8 optimizes JS:
  - [V8 Official Docs](https://v8.dev/docs)
  - [Understanding JS Performance – V8 Blog](https://v8.dev/blog/understanding-javascript-performance)
- 🔍 React component execution in V8:
  - [JS Execution Pipeline – V8 Blog](https://v8.dev/blog/inside-javascript-execution)

### Day 3–4: Common Performance Anti-Patterns
- 🛑 Avoid common traps:
  - [Preventing Unnecessary Re-renders – React Docs](https://react.dev/learn/optimizing-performance#preventing-unnecessary-re-renders)
  - [Kent C. Dodds Optimization Article](https://kentcdodds.com/blog/optimize-react-re-renders)
- 🧰 Advanced debugging:
  - [JavaScript CPU Profiler – Chrome DevTools](https://developer.chrome.com/docs/devtools/javascript/cpu-profiling/)
  - [Memory Problems – Chrome Docs](https://developer.chrome.com/docs/devtools/memory-problems/)

### Day 5: Full Review and Integration
- 📖 Create a personal reference mapping React patterns to V8 behaviors
- 🗺️ Map re-render causes to V8 optimization opportunities

---

# 🧭 Resource Priority List
- **React Official Docs**
  - [Render and Commit](https://react.dev/learn/render-and-commit)
  - [State as a Snapshot](https://react.dev/learn/state-as-a-snapshot)
  - [Updating Objects/Arrays in State](https://react.dev/learn/updating-objects-in-state)
  - [Preserving and Resetting State](https://react.dev/learn/preserving-and-resetting-state)
- **React GitHub & Internals**
  - [Reconciliation Overview](https://legacy.reactjs.org/docs/reconciliation.html)
  - [React Scheduler Package](https://github.com/facebook/react/tree/main/packages/scheduler)
- **React Core Team Content**
  - [Lifecycle Blog Post by Dan Abramov](https://overreacted.io/a-complete-guide-to-useeffect/)
  - [React as a UI Runtime – Dan Abramov](https://github.com/reactjs/rfcs/pull/229)

---

🎯 Stay consistent, and you’ll come out of this with deep knowledge and real debugging confidence!
