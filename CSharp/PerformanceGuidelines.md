# Performance Guidelines
1. Consider using Any() to determine whether an IEnumerable<T> is empty
2. Only use async for low-intensive long-running activities
3. Prefer Task.Run for CPU-intensive activities
4. Beware of mixing up await/async with Task.Wait
5. Beware of async/await deadlocks in single-threaded environments