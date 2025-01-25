# React useEffect Infinite Loop Bug

This repository demonstrates a common React bug involving the `useEffect` hook.  The bug is caused by an infinite render loop due to a missing dependency in the effect's dependency array. The solution is to correctly include the `count` variable in the dependency array to prevent the effect from being executed after every render, only when it changes.