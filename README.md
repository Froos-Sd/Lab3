# 🧠 AI Lab 3 – Search Algorithms & Knowledge Base Reasoning
👤 Student Information
Name: Firas Saadeddin
ID: S23208870
📌 Overview
This lab focuses on two main Artificial Intelligence concepts:

Search Algorithms – specifically Breadth-First Search (BFS)
Knowledge Base Reasoning – using logical inference
🚀 Part 1: Search Algorithms
✅ Exercise 1 – BFS Search
Goal: Find a path from Makkah to Madinah using BFS.

Results:

Steps taken: 5 steps
Path found:
Makkah → Jeddah → Madinah
Conclusion:
This is the shortest path, since BFS guarantees shortest paths in unweighted graphs.

➕ Exercise 2 – Adding a New City
Task: Extend the graph and find a new path.

Result:

Path from Makkah to Abha:
Makkah → Taif → Abha
🧩 Part 2: Knowledge Base (KB)
🕵️ Exercise 3 – Logical Inference
Question: Does the KB prove Nora is guilty?

Answer:
No, because there is no rule linking having the key to being guilty.

Required rule:
kb.tell(Implication(nora_key, nora_guilty))

