<div align="center">

# ☕ Java Placement Training & Programming Mastery (PTP)
### **Comprehensive Core Java, Collections, Multithreading, Data Structures & Algorithms, and Placement Interview Solutions**

[![Java](https://img.shields.io/badge/Java-17%20%7C%2021_LTS-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](https://www.oracle.com/java/)
[![Data Structures](https://img.shields.io/badge/DSA-Arrays_%7C_Trees_%7C_Graphs-4B0082?style=for-the-badge)](https://github.com/akshayamv-0909/java-ptp-)
[![JUnit 5](https://img.shields.io/badge/JUnit_5-Testing-25A162?style=for-the-badge&logo=junit5&logoColor=white)](https://junit.org/junit5/)
[![Maven](https://img.shields.io/badge/Apache_Maven-Build_Tool-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)](https://maven.apache.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](LICENSE)

<p align="center">
  <b>Official Repository:</b> <a href="https://github.com/akshayamv-0909/java-ptp-">https://github.com/akshayamv-0909/java-ptp-</a><br>
  <i>"From Core OOPs Foundations to FAANG & Product-Based Campus Placement Mastery."</i>
</p>

</div>

---

## 📌 Overview

**java-ptp-** (Java Placement Training Program) is a structured, production-grade repository designed for computer science students and software engineers preparing for technical interviews, campus placements, and competitive programming.

This repository serves as a complete reference codebase, featuring well-documented code implementations, design patterns, JUnit test suites, time/space complexity analyses, and solved placement problems from top product companies.

```
+-------------------------------------------------------------------------------------------------------+
|                                    JAVA MASTERY ROADMAP (PTP)                                         |
+-------------------+-------------------+-------------------+-------------------+-----------------------+
|   1. Core Java    |  2. Collections   |  3. Java 8+ Stream| 4. Multithreading |    5. DSA & LeetCode  |
| OOPs & Memory     | Lists, Sets, Maps | Lambdas, Optionals| Concurrency & Lock| 100+ Top Campus Qs    |
+-------------------+-------------------+-------------------+-------------------+-----------------------+
```

---

## 📚 Curriculum & Learning Modules

### 🧩 Module 01: Core Java & Object-Oriented Programming (OOPs)
- **4 Pillars of OOPs**: Encapsulation, Inheritance, Polymorphism (Runtime & Compile-Time), and Abstraction.
- **SOLID Principles**: Single Responsibility, Open-Closed, Liskov Substitution, Interface Segregation, Dependency Inversion.
- **Java Memory Architecture**: Stack vs. Heap allocation, Metaspace, Garbage Collection algorithms (G1GC, ZGC).
- **Strings Deep-Dive**: `String` immutability, String Constant Pool (SCP), `StringBuilder` vs `StringBuffer`.

### 📦 Module 02: Java Collections Framework & Generics
- **List Interface**: `ArrayList` dynamic resizing, `LinkedList` node pointers, `Vector`, `CopyOnWriteArrayList`.
- **Set Interface**: `HashSet` hashing mechanism, `LinkedHashSet` insertion ordering, `TreeSet` (Red-Black Tree).
- **Map Interface**: `HashMap` internal bucketing & collision resolution, `ConcurrentHashMap`, `TreeMap`, `LinkedHashMap`.
- **Queue & Deque**: `PriorityQueue` (Min-Heap / Max-Heap), `ArrayDeque`, `BlockingQueue`.
- **Custom Comparators**: `Comparable<T>` vs `Comparator<T>`.

### ⚡ Module 03: Java 8+ Modern Functional Programming
- **Lambdas & Functional Interfaces**: `Predicate`, `Function`, `Consumer`, `Supplier`.
- **Streams API**: Filter, Map, FlatMap, Reduce, Collect, GroupingBy, PartitioningBy, Parallel Streams.
- **Null Safety**: `Optional<T>` patterns to eliminate `NullPointerException`.
- **New Date/Time API**: `LocalDate`, `ZonedDateTime`, `Duration`, `Period`.

### 🧵 Module 04: Multithreading & High-Concurrency
- **Thread Lifecycles**: Creating threads via `Thread` vs `Runnable` vs `Callable<V>`.
- **Synchronization & Locks**: `synchronized` blocks, `ReentrantLock`, `ReadWriteLock`, Condition variables.
- **Thread Pools**: `ExecutorService`, `ThreadPoolExecutor`, `ForkJoinPool`, `CompletableFuture`.
- **Atomic Variables**: `AtomicInteger`, `AtomicReference`, CAS (Compare-And-Swap) operations.
- **Deadlock Prevention**: Dining philosophers simulation, resource hierarchy ordering.

### 🌲 Module 05: Data Structures & Algorithms in Java
- **Arrays & Strings**: Two Pointers, Sliding Window, Kadane's Algorithm, Prefix Sums.
- **Linked Lists**: Fast & Slow Pointers, Cycle Detection, Reversal, Merge K Sorted Lists.
- **Stacks & Queues**: Next Greater Element, Monotonic Stack, LRU Cache implementation.
- **Trees & Binary Search Trees**: BFS/DFS Traversals, Lowest Common Ancestor (LCA), Diameter of Tree.
- **Graphs**: Adjacency Lists, BFS, DFS, Dijkstra's Algorithm, Topological Sort (Kahn's), Disjoint Set Union (DSU).
- **Dynamic Programming**: 0/1 Knapsack, Longest Common Subsequence (LCS), Coin Change, Matrix DP.

---

## 📂 Repository Structure

```bash
java-ptp-/
├── pom.xml                                   # Maven dependencies & build configurations
│
└── src/
    ├── main/java/com/placement/
    │   ├── core/                             # OOPs, Polymorphism, Interfaces, Memory
    │   │   ├── oops/
    │   │   ├── memory/
    │   │   └── strings/
    │   ├── collections/                      # Collections Framework & Custom Data Structures
    │   │   ├── list/
    │   │   ├── map/
    │   │   └── set/
    │   ├── streams/                          # Java 8+ Functional Streams & Lambdas
    │   ├── concurrency/                      # Multithreading, ThreadPools & CompletableFuture
    │   ├── dsa/                              # Data Structures & Algorithms
    │   │   ├── arrays/
    │   │   ├── linkedlist/
    │   │   ├── trees/
    │   │   ├── graphs/
    │   │   └── dp/
    │   └── interview100/                     # Top 100 Solved Company Placement Questions
    │
    └── test/java/com/placement/              # JUnit 5 Unit Test Suites
        ├── core/
        ├── collections/
        └── dsa/
```

---

## 💻 Getting Started

### Prerequisites
- [Java Development Kit (JDK 17 LTS or JDK 21 LTS)](https://www.oracle.com/java/technologies/downloads/)
- [Apache Maven](https://maven.apache.org/) (v3.8+) or your favorite IDE (IntelliJ IDEA / VS Code / Eclipse)

### 1. Clone the Repository
```bash
git clone https://github.com/akshayamv-0909/java-ptp-.git
cd java-ptp-
```

### 2. Compile & Run with Maven
```bash
# Compile the entire project
mvn clean compile

# Run all JUnit 5 test suites
mvn test
```

### 3. Run a Specific Module / Solution
```bash
# Example: Run the LRU Cache demonstration
mvn exec:java -Dexec.mainClass="com.placement.dsa.stacks.LRUCache"
```

---

## 🎯 Top Campus Placement Questions Included

| Topic | Problem Statement | Complexity | Difficulty |
| :--- | :--- | :--- | :--- |
| **Array** | Trapping Rain Water | $\mathcal{O}(N)$ Time, $\mathcal{O}(1)$ Space | 🔴 Hard |
| **String** | Longest Substring Without Repeating Characters | $\mathcal{O}(N)$ Time, $\mathcal{O}(\min(N, M))$ Space | 🟡 Medium |
| **LinkedList** | Reverse Nodes in k-Group | $\mathcal{O}(N)$ Time, $\mathcal{O}(1)$ Space | 🔴 Hard |
| **Tree** | Serialize and Deserialize Binary Tree | $\mathcal{O}(N)$ Time, $\mathcal{O}(N)$ Space | 🔴 Hard |
| **DP** | 0/1 Knapsack & Coin Change Problem | $\mathcal{O}(N \times W)$ Time, $\mathcal{O}(W)$ Space | 🟡 Medium |
| **Design** | LRU Cache with $\mathcal{O}(1)$ `get` & `put` | $\mathcal{O}(1)$ Time, $\mathcal{O}(\text{Capacity})$ Space | 🟡 Medium |

---

## 🧪 Unit Testing with JUnit 5

All algorithms and custom data structures are verified using automated JUnit 5 parameterized tests:

```java
@ParameterizedTest
@CsvSource({
    "racecar, true",
    "hello, false",
    "A man a plan a canal Panama, true"
})
void testIsPalindrome(String input, boolean expected) {
    assertEquals(expected, StringAlgorithms.isPalindrome(input));
}
```

---

## 🤝 Contributing

Contributions of new solutions, optimized algorithms, and interview questions are welcome!
1. Fork the Project (`https://github.com/akshayamv-0909/java-ptp-/fork`)
2. Create a Topic Branch (`git checkout -b solution/LongestPalindromicSubstring`)
3. Commit with Clean Messages (`git commit -m 'Add Java solution with JUnit test'`)
4. Push to the Branch (`git push origin solution/LongestPalindromicSubstring`)
5. Open a Pull Request

---

## 📄 License

Distributed under the **MIT License**. See `LICENSE` for details.

---

<div align="center">
  <sub>Maintained by <a href="https://github.com/akshayamv-0909">@akshayamv-0909</a> · Java Placement Program Track</sub>
</div>
