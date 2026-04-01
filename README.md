# Applied_Algorithms
Repo: `tdvipp/Applied_Algorithms`  

Repository này tổng hợp các bài cài đặt/ôn tập thuật toán, được nhóm theo **chủ đề**.  
Mỗi mục bên dưới liệt kê **các file tương ứng** để bạn dễ tìm.

---

## 1) Graph algorithms / Lý thuyết đồ thị
### 1.1. MST (Minimum Spanning Tree)
- Prim: `Mo_phong_ly_thuyet_do_thi/prim_al.cpp`
- Kruskal + **DSU/Union-Find**: `Mo_phong_ly_thuyet_do_thi/krushkal_union_find.cpp`
- (Bản khác/ghi chú): `others/MST_KRUSKAL.cpp`

### 1.2. Topological Sort
- `Mo_phong_ly_thuyet_do_thi/topo_sort.cpp`

### 1.3. DFS numbering / low-link (phục vụ bridge/articulation)
- `Mo_phong_ly_thuyet_do_thi/build_num_and_low_array.cpp`

### 1.4. Bridges & Articulation Points
- `Thuc_hanh_buoi_5/BRIDGES_ARTI_POINTS.cpp`

### 1.5. Strongly Connected Components (SCC)
- `Thuc_hanh_buoi_5/STRONGLY_CONNECTED_COMPONENT.cpp`

### 1.6. Bài toán đồ thị khác
- Bus inter-city routing: `Mo_phong_ly_thuyet_do_thi/BUS_INTER_CITY.cpp`
- Check bipartite graph (BFS + tô màu): `others/check_bipartite_graph.cpp`

---

## 2) BFS / DFS / Traversal
### 2.1. DFS (liệt kê theo thứ tự tăng dần bằng `set`)
- `others/DFS_LIST_SEQ_NODES_LEX.cpp`

### 2.2. DFS dùng trong các bài đồ thị (bridge, SCC, low-link)
- `Thuc_hanh_buoi_5/BRIDGES_ARTI_POINTS.cpp`
- `Thuc_hanh_buoi_5/STRONGLY_CONNECTED_COMPONENT.cpp`
- `Mo_phong_ly_thuyet_do_thi/build_num_and_low_array.cpp`

### 2.3. BFS
- Check bipartite (tô màu 2 phía): `others/check_bipartite_graph.cpp`

---

## 3) Grid / Pathfinding / Traversal trên lưới
- Maze solving (traversal trên grid): `Thuc_hanh_buoi_1/maze.cpp`

---

## 4) Range queries / Sparse-table style preprocessing
- Range Minimum Query (RMQ): `Thuc_hanh_buoi_1/range_minimum_query.cpp`

---

## 5) Stack / Histogram / Maximal rectangle
- Largest black sub-rectangle (thường giải bằng histogram + stack):  
  `Thuc_hanh_buoi_1/largest_black_subrectangle.cpp`

---

## 6) Backtracking / Combinatorial search / Tối ưu ràng buộc
- CBUS (dạng backtracking / TSP-like): `Thuc_hanh_buoi_2/CBUS.cpp`
- BCA (phân công/điều kiện xung đột, backtracking + kiểm tra): `Thuc_hanh_buoi_2/BCA.cpp`
- Hamilton cycle (brute-force/backtracking): `others/HAM_CYCLE.cpp`
- TSP (backtracking/nhánh cận): `others/TSP.cpp`
- Route planning (biến thể gần TSP): `others/do_thi_route_planning.cpp`
- K-path (đếm/tìm đường đi độ dài k, dùng TRY/quay lui): `others/do_thi_k_path.cpp`
- DIGITS (bài thi, quay lui gán chữ số): `De_thi_giua_ky/De_1/bai_3_DIGITS.cpp`

---

## 7) Counting / Đếm nghiệm / Phương trình nguyên
- Count integer solutions of linear equation:  
  `Thuc_hanh_buoi_2/COUNT_INTEGER_LINEAR_EQUATION.cpp`

---

## 8) Sorting / Divide-and-conquer / Counting (BIT-style)
- Inversion counting: `Thuc_hanh_buoi_3/INVERSION.cpp`

---

## 9) Greedy / Subsequences / Searching
- Max distance subsequence: `Thuc_hanh_buoi_3/MAX_DISTANCE_SUB_SEQ.cpp`
- LIS (Longest Increasing Subsequence): `Thuc_hanh_buoi_3/lis1.cpp`

---

## 10) Prefix sums / Cumulative sums
- Max even (subarray) theo ý tưởng cumulative sum:  
  `Thuc_hanh_buoi_4/MAX_EVEN_cusum.cpp`

---

## 11) Scheduling / Optimization
- Makespan scheduling: `Thuc_hanh_buoi_5/MAKE_SPAN_SCHEDULE.cpp`

---

## 12) Bộ đề / Luyện tập
- Giữa kỳ: `De_thi_giua_ky/`
- Cuối kỳ: `De_thi_cuoi_ky/`

---

## Build & run (C++)
Bạn có thể build từng file độc lập:

```bash
g++ -std=c++17 -O2 -o main path/to/file.cpp
./main
```

Ví dụ:
```bash
g++ -std=c++17 -O2 -o main Thuc_hanh_buoi_5/BRIDGES_ARTI_POINTS.cpp
./main
```
