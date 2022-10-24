### Week 1

#### Solution of Linear System

- None （无解）
- One  (unique solution) （唯一解）
- Infinitely many （五穷解）

#### Elementary Row Operations (行变换)

- $R_i \leftrightarrow R_j$ (interchange)
- $\alpha R_i$
- $R_i+\beta R_j$

#### **Consistent** and **Inconsistent**

- Consistent: infinity or one 
- Inconsistent: none

#### Echelon Matrix

- Row Echelon Form Matrix (REF)
  - properties
    - the row with **all zero** should be on the **bottom** （全零行放在底）
    - Each ***leading entry***(the first entry which is not zero in the row) of a row is in a column to the right of the leading entry of the row above it. (Echelon) （leading entry 列号单调）
    - **All** entry (below the ***leading entry***) must be zero.（Leading Entry 下面全是 $0$）

- Reduced Row Echelon Form Matrix(R R E F)
  - with all properties of REF
  - besides:
    - leading entry must be $1$ （leading entry 只能是1）
    - Each leading 1 is the **only** nonzero entry in its column （Leading Entry 所在列，除 $LE$ 全是$0$）



**REF** is enough to determine the cases of solution (three cases). (Row Echelon Form 对于解决解数量问题已经足够了)

the Reduced Echelon Form of the matrix is unique to the specific matrix. （Reduced Row Echelon Form 对于一个特定矩阵来说是唯一的）（**Each matrix is row equivalent to one and only one reduced echelon form.**）

- **Pivot Position** corresponds to the leading entry in Reduced Row Echelon Form Matrix. (**Pivot Position** 和 Reduced Row Echelon Form 里面的 Leading Entry 一 一对应)

- **Pivot Column** is the column with Pivot Position. （有 Leading Entry 的那一列）

- **Basic Variables** corresponds to **Pivot Column**. （有Leading Entry 的那一列对应的自变量）
- **Free Variables** corresponds to the other column. 
  - It determines whether the solution of linear system is infinity, （自由元有无 决定 方程组解有限性）
  - Free Variables can be any number. and the value of  **Basic Variables** depend on Free Variables.











