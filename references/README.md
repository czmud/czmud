As I come across new topics I add them to this readme to keep track of my learning
### Learning
- Implement Github Actions in CI/CD pipeline
- Difference between Open APIs and REST APIs
- Remote Procedure Calls / Using DTO instead of model based REST API
- Adding Linting/Prettier to projects
- Typescript difference between 'unknown' and 'any' typing
- How do MVVM frameworks work?

## Learned
- What is Dependency Injection?
- Difference between C# variable designations:
  - singleton
  - transient
  - scoped
- Graph datastructure traversing:
          A
         / \
        B   C
       / \
      D   E
  - DFS (Depth First Search)
    - follow paths deep first, then return node by node to follow other branches
    - uses stack to manage traversal
    - A -> B -> D -> E -> C
  - BFS (Breadth First Search)
    - check nodes directly connected to current node first, then follow paths deeper with each pass
    - uses queue to manage traversal
    - A -> B -> C -> D -> E