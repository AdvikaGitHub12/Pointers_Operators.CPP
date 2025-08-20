# 🧵 Pointer Operations in C++  

---

## 🎯 Aim  
To study and implement pointer operations in C++ and understand the difference between **call by value** and **call by reference** parameter-passing methods.  

---

## 📚 Theory  

In C++, the way we pass parameters to functions determines whether changes inside the function affect the original variables.  

### 📦 Call by Value  
- **Definition:** A copy of the actual parameter is passed to the function.  
- **Effect:** Changes happen only on the copy → originals remain unchanged.  
- **Working:** Function operates in its own scope and does not affect caller variables.  

### 🔗 Call by Reference  
- **Definition:** The address or reference of actual parameters is passed, allowing direct modification of originals.  
- **Effect:** Changes done inside the function reflect in the caller variables.  
- **Working:** Function receives pointers (or references) → dereferences them to access and modify actual memory.  

---

## 📊 Comparison Table  

| ⚙️ Feature                 | 📦 Call by Value           | 🔗 Call by Reference       |
|-----------------------------|----------------------------|-----------------------------|
| **Data Passed**             | Copy of value              | Address / reference         |
| **Changes affect original** | ❌ No                      | ✅ Yes                      |
| **Memory Use**              | Extra copy made            | No extra copy               |
| **Safety**                  | Safer (no side effects)    | Can change caller data      |
| **Typical Use Case**        | Read-only operations       | In-place modifications      |  

## 🧠 Conclusion  

This experiment demonstrates the difference between parameter-passing methods in C++.  

- 📦 **Call by Value** → Works on copies, originals remain safe.  
- 🔗 **Call by Reference** → Works directly on real data, originals are modified.  
- ✅ Key Insight:  
  - Use **Call by Value** for safety (read-only operations).  
  - Use **Call by Reference** for in-place updates and efficiency.  
