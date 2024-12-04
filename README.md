# React useEffect Infinite Loop Bug

This repository demonstrates a common bug in React applications involving the `useEffect` hook and shallow comparisons of objects.  Incorrectly comparing objects within the `useEffect` dependency array can lead to unexpected re-renders and infinite loops.  The solution shows how to correctly compare objects using techniques like JSON.stringify or lodash's isEqual.