# Hoán đổi vị trí 2 node bất kỳ

Cho một danh sách liên kết (DSLK) đơn, hoán đổi nút thứ `k` từ đầu với nút thứ `k` từ cuối. Không được phép hoán đổi dữ liệu, chỉ nên thay đổi con trỏ, thao tác này hữu ích trong trường hợp dữ liệu mỗi node có kích thước lớn, phức tạp, việc thay đổi liên kết sẽ dễ hơn việc thay đổi giá trị của node.

Lưu ý: `k` đếm từ 1 (không phải chỉ sống mảng - bắt đầu từ 0)

**Input:**

- Dòng đầu tiên là `n` số nút
- Dòng tiếp theo là `n` node trong DSLK
- Dòng cuối là `k` (`k < (n / 2)`)

**Output:**

- In ra DSLK

**Ví dụ:**

Ví dụ 1:

```
# Input
5
1 2 3 4 5
2

# Output
1 4 3 2 5

# Giải thích
Vị trí k=2 từ đầu là số 2, vị trí k=2 từ cuối là 4
```

Ví dụ 2:

```
# Input
7
2 6 4 2 0 1 2
3

# Output
2 6 0 2 4 1 2

# Giải thích
Vị trí k=3 từ đầu là số 4, vị trí k=3 từ cuối là 0
```