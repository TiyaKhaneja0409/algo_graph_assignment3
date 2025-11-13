## 🏗 Problem 4: Network Cable Installation – Prim’s Algorithm (MST)

### ⚙ Time Complexity
- The time plot follows a near-linear-logarithmic pattern, consistent with *O(E log V)*.  
- Efficiency depends on graph density: performs faster for sparse graphs.  
- The priority queue ensures minimal edge selection overhead.

### 💾 Space Complexity
- Memory usage increases with graph connectivity, approximately *O(V + E)*.  
- Requires storing visited nodes and edge lists during MST construction.  
- Efficient and manageable for large-scale infrastructure graphs.

### 🧠 Conclusion
Prim’s Algorithm effectively finds the minimum spanning tree for connecting all nodes with minimal cost.  
Ideal for network design, telecom, and IT infrastructure planning.  
It provides excellent scalability and accuracy in cost-optimization problems.
