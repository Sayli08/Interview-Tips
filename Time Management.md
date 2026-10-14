## 45-Minute Coding Interview Cheat Sheet

| Time      | Phase      | What to do                                   |
| --------- | ---------- | -------------------------------------------- |
| 0–5 min   | Understand | Restate problem, ask clarifying questions    |
| 5–10 min  | Example    | Walk through example, identify edge cases    |
| 10–15 min | Approach   | Explain brute force → optimal approach → why |
| 15–30 min | Code       | Write Java code, explain key logic           |
| 30–38 min | Dry run    | Trace code with example, fix bugs            |
| 38–42 min | Test       | Check edge cases                             |
| 42–45 min | Complexity | Time, space, possible optimizations          |

### What to say — LeetCode 364

Problem: "We multiply each integer by a weight based on its depth. Deeper integers get smaller weights."

Approach: "Since we have lists inside lists, I'll use DFS. First, I'll find the maximum depth. Then I'll use another DFS to calculate the weighted sum."

Code: "If it's an integer, I'll process it. If it's another list, I'll recursively explore it with depth plus one."

Complexity: "O(N) time because we traverse every element twice, and O(D) space for recursion."

Remember: Understand → Example → Approach → Code → Test → Complexity.
