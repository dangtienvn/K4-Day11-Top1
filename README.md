# K4-Day11-Top1 — Tổng hợp bài nộp nhóm

> **Day 11 · SVM-360 Fisheye Lab** · Khoá K4
>
> Repo này là **cổng tổng hợp** của nhóm Top1. Hiện vật thực hành (XML, lock, QA, rework, kế hoạch 4 camera) nằm trong repo cá nhân của từng thành viên. Người chấm truy cập từ bảng bên dưới.

---

## Thông tin nhóm

|                     |                                     |
| ------------------- | ----------------------------------- |
| Tên nhóm            | Top1                                |
| Khoá                | K4                                  |
| Số lượng thành viên | 3 người                             |
| Đại diện nộp bài    | Đặng Thành Tiên (MSSV: 2A202602099) |
| Ngày nộp            | 2026-09-28                          |

---

## Bảng repo và commit chốt của các thành viên

| Thành viên                       | MSSV        | Tên mode      | Slice    | QA bài của    | Repo cá nhân                                                                                                  | Commit chốt        |
| -------------------------------- | ----------- | ------------- | -------- | ------------- | ------------------------------------------------------------------------------------------------------------- | ------------------ |
| **Đặng Thanh Tiến** _(Đại diện)_ | 2A202602099 | DangThanhTien | B4-dense | PhamThiOanh   | [K4-Day11-DangThanhTien-2A202602099](https://github.com/dangtienvn/K4-Day11-DangThanhTien-2A202602099)        | `2846135`          |
| **Phạm Thị Oanh**                | 2A202602055 | PhamThiOanh   | B2-edge  | PhanBoiThuy   | [K4-Day11-PhamThiOanh-2A202602055](https://github.com/phamthioanh13112004-prog/K4-L2-DAY11-PhamThiOanh-02055) | `chốt-bài-cá-nhân` |
| **Phan Bội Thúy**                | 2A202602129 | PhanBoiThuy   | B4-edge  | DangThanhTien | [K4-Day11-PhanBoiThuy-2A202602129](https://github.com/BoiThuy/K4-DAY11-PhanBoiThuy-2A202602129)               | `chốt-bài-cá-nhân` |

---

### Liên kết bằng chứng chi tiết của đại diện nhóm (Đặng Thanh Tiến)

| Hiện vật                           | Link                                                                                                                         |
| ---------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| `submission/manifest.json`         | [manifest.json](https://github.com/dangtienvn/K4-Day11-DangThanhTien-2A202602099/blob/main/submission/manifest.json)         |
| Nhãn đã khóa (`r1_craft/lock.txt`) | [lock.txt](https://github.com/dangtienvn/K4-Day11-DangThanhTien-2A202602099/blob/main/submission/r1_craft/lock.txt)          |
| QA review (`r2_qa/qa_review.md`)   | [qa_review.md](https://github.com/dangtienvn/K4-Day11-DangThanhTien-2A202602099/blob/main/submission/r2_qa/qa_review.md)     |
| Rework delta (`rework/delta.md`)   | [delta.md](https://github.com/dangtienvn/K4-Day11-DangThanhTien-2A202602099/blob/main/submission/rework/delta.md)            |
| Exit ticket (`50_exit_ticket.md`)  | [50_exit_ticket.md](https://github.com/dangtienvn/K4-Day11-DangThanhTien-2A202602099/blob/main/submission/50_exit_ticket.md) |

---

## Cách nhóm phân công và thảo luận

1. **Phân công slice & QA xoay vòng (3 người theo `team.json`):**
   - Đặng Thanh Tiến (Slice: `B4-dense`) → Soát QA bài của Phạm Thị Oanh.
   - Phạm Thị Oanh (Slice: `B2-edge`) → Soát QA bài của Phan Bội Thúy.
   - Phan Bội Thúy (Slice: `B4-edge`) → Soát QA bài của Đặng Thanh Tiến.
2. **Thảo luận guideline:** Cả nhóm thống nhất quy tắc đề xuất R04-ext (`20_guideline_patch.md`) cho xe ba bánh điện chở hàng và cách xử lý trường hợp nghi ngờ teaching reference thiếu (`E0_reference_defect`).
3. **Kế hoạch 4 camera:** Thống nhất phân bổ 200 frame cho 4 camera (Front, Rear, Left, Right) trong `45_sampling_plan.csv` và các ca hard case ở vùng seam góc xe trong `46_gold_set_plan.md`.
4. **Vấn đề còn tồn đọng:** Ca seam cross-camera (D004 trong `40_decision_log.csv`) cần policy từ Lab Coach trước khi xác nhận cách gán nhãn chính thức.

---

## Kiểm tra trước khi gửi link

- [x] Repo cá nhân và Repo nhóm ở chế độ **Public**
- [x] `submission/manifest.json` của đại diện nhóm có `failed_gates: []` (`check` exit code 0)
- [x] Bảng phân công 3 người trùng khớp với sơ đồ vòng trong `team.json`
