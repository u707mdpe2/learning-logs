# React Hooks Notes

## useState
- State updates are async; use functional updates for derived state.
- Never call hooks inside loops, conditions, or nested functions.

## useEffect
- Dependency array controls when effects run.
- Cleanup function for subscriptions or timers to avoid memory leaks.

## useMemo & useCallback
- Use for expensive calculations or stable references.
- Don't over-optimize; measure first.

## Custom Hooks
- Extract shared logic into reusable functions starting with `use`.
- Keep them focused and composable.