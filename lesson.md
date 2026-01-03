# **Detailed Lesson Plan: 1.6 Introduction to NumPy**

**Total Duration:** 180 Minutes (3 Hours)

## **Section 1: The Environment & The Engine (60 min)**

*Goal: Master Jupyter in VSCode and understand the "Why" of NumPy.*

| Time | Activity | Instructor Notes |
| ----- | ----- | ----- |
| 05m | **Objectives & Intro** | Highlight: NumPy is the foundation for Pandas and Scikit-Learn. |
| 15m | **Workshop 1: Jupyter/VSCode** | Demo: Creating cells, Markdown vs Code, Keyboard shortcuts (`Shift+Enter`). |
| 15m | **Workshop 2: Speed Test** | Demo: Compare Python List vs NumPy Array (1M elements). Use `%timeit`. |
| 20m | **Theory: Memory & Types** | Explain **Contiguous Memory** vs Python lists. Discuss homogeneous types. |
| 05m | **Q\&A** | Address "Why not just use Excel?" (Scale, Memory efficiency, Automation). |

## **Section 2: Array Anatomy & Arithmetic (60 min)**

*Goal: Create arrays, manage data types, and perform vectorized math.*

| Time | Activity | Instructor Notes |
| ----- | ----- | ----- |
| 10m | **Theory: The ndarray** | Explain dimensions (1D, 2D, 3D), `.shape`, `.dtype`, and `.ndim`. |
| 20m | **Workshop 3: Creation & Casting** | **Demo:** `np.array()`, `np.zeros()`, `np.ones()`. **Exercise:** Using `.astype()` to cast floats to ints. |
| 20m | **Workshop 4: Math & Broadcasting** | **Demo:** Element-wise math and Broadcasting scalars/arrays. **Exercise:** Vectorized arithmetic. |
| 05m | **Socratic Review** | "What happens to the decimal when casting `float` to `int32`?" (Truncation). |
| 05m | **Break** | Stretch and reset. |

## **Section 3: Data Selection, Logic & Algebra (60 min)**

*Goal: Advanced manipulation, filtering, and introduction to matrix math.*

| Time | Activity | Instructor Notes |
| ----- | ----- | ----- |
| 15m | **Workshop 5: Slicing Views** | **Demo:** `[row, col]` syntax. Explain that slices are **views** (modifying a slice changes the original). |
| 15m | **Workshop 6: Boolean & Set Logic** | **Demo:** Filtering by mask (e.g., `data[names == 'Bob']`). **Exercise:** `np.unique()` and `np.where()`. |
| 15m | **Workshop 7: Stats & Algebra** | **Demo:** `.mean(axis=0)` vs `axis=1`. Introduction to Matrix Multiplication with `@` and `.dot()`. |
| 15m | **Assessment & Wrap-up** | Run the 5-question quiz. Connect NumPy arrays to future Pandas DataFrames. |

