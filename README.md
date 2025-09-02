<h1 align="center">🐍 Mastering DSA with Python 🚀</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Learning-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Language-Python-blue?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/Notebook-Jupyter-orange?style=for-the-badge&logo=jupyter" />
  <img src="https://img.shields.io/github/stars/yourusername/DSA-with-Python?style=for-the-badge" />
</p>

---

## 📖 Introduction
Welcome to my **Data Structures & Algorithms with Python** repository!  
Here, you’ll find **Jupyter Notebooks** organized by topics with clean explanations and working Python code.

📌 File naming format:
```
topicNumber_topicName.ipynb
```

✅ Example:  
- `06_function.ipynb`  
- `07_oops.ipynb`  
- `08_numpy_array.ipynb`  

---

## 🛠️ Learning Roadmap

| Status | Topic # | Topic Name          | File Name               |
|--------|---------|---------------------|-------------------------|
| ✅     | 06      | Functions           | `06_function.ipynb`     |
| ✅     | 07      | OOPs                | `07_oops.ipynb`         |
| ✅     | 08      | NumPy Arrays        | `08_numpy_array.ipynb`  |
| 🚧     | 09      | Searching & Sorting | `09_sorting.ipynb`      |
| 🔜     | 10      | Linked List         | `10_linkedlist.ipynb`   |
| 🔜     | 11      | Stack & Queue       | `11_stack_queue.ipynb`  |
| 🔜     | 12      | Trees & Graphs      | `12_trees_graphs.ipynb` |
| 🔜     | 13      | Dynamic Programming | `13_dp.ipynb`           |

---

## 💻 Featured Python Snippets  

### 🔹 Factorial (Recursion)
```python
def factorial(n):
    return 1 if n == 0 else n * factorial(n - 1)

print("5! =", factorial(5))
```

### 🔹 Queue using Deque
```python
from collections import deque

queue = deque()
queue.append("A")
queue.append("B")
queue.append("C")

print("Initial Queue:", list(queue))
queue.popleft()
print("After Dequeue:", list(queue))
```

### 🔹 Binary Search Tree
```python
class Node:
    def __init__(self, key):
        self.key = key
        self.left = self.right = None

def insert(root, key):
    if not root: return Node(key)
    if key < root.key: root.left = insert(root.left, key)
    else: root.right = insert(root.right, key)
    return root

def inorder(root):
    return inorder(root.left) + [root.key] + inorder(root.right) if root else []

root = None
for val in [50, 30, 70, 20, 40, 60, 80]:
    root = insert(root, val)

print("Inorder Traversal:", inorder(root))
```

---

## 📊 Progress Tracker
- [x] Python Basics  
- [ ] Functions  
- [ ] OOPs  
- [ ] NumPy  
- [ ] Searching & Sorting  
- [ ] Linked List  
- [ ] Stack & Queue  
- [ ] Trees & Graphs  
- [ ] Dynamic Programming  

---

## ⚡ Why This Repo?
✔️ Topic-wise Notebooks 📒  
✔️ Pythonic DSA Implementations 🐍  
✔️ Clean Code + Examples 💡  
✔️ Beginner → Advanced Roadmap 🚀  

---

## 📈 GitHub Stats
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=yourusername&theme=tokyonight&show_icons=true" width="48%" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=yourusername&theme=tokyonight" width="48%" />
</p>

---

## 🌐 Connect with Me
<p align="center">
  <a href="https://github.com/subodhkryadav"><img src="https://img.shields.io/badge/GitHub-black?style=for-the-badge&logo=github" /></a>
  <a href="https://www.linkedin.com/in/subodh-kumar-yadav-522828293"><img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin" /></a>
  <a href="mailto:subodhkumary933@gmail.com"><img src="https://img.shields.io/badge/Email-red?style=for-the-badge&logo=gmail" /></a>
</p>

---

<h3 align="center">✨ Keep Learning • Keep Building • Keep Growing ✨</h3>
