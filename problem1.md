# Xoay vòng danh sách liên kết đôi

Cho một danh sách liên kết (DSLK) đôi, hãy xoay danh sách liên kết ngược chiều kim đồng hồ qua `k` nút. Trnog đó, `k` là một số nguyên dương cho trước và nhỏ hơn số nút `n` trong danh sách liên kết.

**Input:**

- Dòng đầu tiên là `n` số nút
- Dòng tiếp theo là `n` node trong DSLK
- Dòng cuối là `k`, số node cần xoay ngược chiều kim đồng hồ

**Output:**

- In ra DSLK sau khi đã xoay `k` node ngược chiều kim đồng hồ

**Ví dụ:**

Ví dụ 1:

```
# Input
5
1 2 3 4 5
2

# Output
3 4 5 1 2
```

Ví dụ 2:

```
# Input
7
2 6 4 2 0 1 2
3

# Output
2 0 1 2 2 6 4
```