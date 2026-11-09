# Team

> Điền file này trên repo chung do nhóm trưởng fork. Nhóm điền phần **Thông tin nhóm** và **Thành viên**. Mỗi người tự điền phần của mình trong **Cá nhân**. Không copy file này sang repo khác.

## Thông tin nhóm

- Tên nhóm: LabB2
- Candidate problem nhóm chọn (1 câu): Tóm tắt hồ sơ bệnh án khi ra viện tại khoa Nội - Bệnh viện Đa khoa Quốc tế Vinmec (giảm tải gánh nặng đọc lại và chép tay cho bác sĩ điều trị)
- Quyết định cuối (Go / Not Yet / No-Go): **Not Yet** cho phần LLM (làm ngay phần Template tự điền không dùng AI để vừa giảm tải vừa đo baseline)

## Thành viên

| STT | Họ và tên | MSSV | Vai trò trong nhóm | Tài khoản GitHub |
|---:|---|---|---|---|
| 1 | Phan Trần Mạnh Cường | 2A202603810 | Nhóm trưởng (lead), điều phối; vẽ quy trình; research nguồn; đề xuất mức can thiệp và quyết định | Cuongngucuteee |
| 2 | Cung Đức Anh | 2A202603814 | Phản biện chính, phụ trách kiểm chứng giả định & Problem Statement |cungducanh2712 |
| 3 | Hoàng Thế Phong | 2A202603832 | Research giải pháp đã có; chuyển quy trình sang Mermaid; phản biện Problem Statement và 4 rủi ro |Hphong2305|

Không ghi email hay số điện thoại vào bảng này, vì repo có thể để public.

Gợi ý vai trò (một người có thể giữ nhiều vai): điều phối thời gian, ghi chép, người phản biện chính, phụ trách kiểm chứng (phỏng vấn/survey), phụ trách research, vẽ quy trình, viết Problem Statement.

## Phân công theo checkpoint

| Checkpoint | Người chính | Người hỗ trợ | Sản phẩm |
|---|---|---|---|
| CP3 — Hội tụ nhóm | Mạnh Cường | Đức Anh, Thế Phong | Cluster, cây OST, bảng chấm điểm |
| CP4 — Kiểm chứng | Đức Anh | Mạnh Cường | Assumption map, snapshot hoặc survey |
| CP4 — Research | Mạnh Cường | Thế Phong | Bảng research có link |
| CP5 — Quy trình trước/sau | Mạnh Cường | Thế Phong | Quy trình + bảng before/after |
| CP5 — Problem Statement v0 | Đức Anh | Mạnh Cường, Thế Phong | Problem Statement v0 |
| CP6 — Mức can thiệp + Problem Statement v1 | Mạnh Cường | Đức Anh, Thế Phong | Ma trận, AI Canvas, eval, Problem Statement v1 |
| CP6 — Quyết định | Mạnh Cường | Đức Anh, Thế Phong | 4 rủi ro + Go/Not Yet/No-Go |

## Cá nhân

Mỗi thành viên thêm một mục theo mẫu dưới đây, tiêu đề là `HoVaTen-MSSV`.

### PhanTranManhCuong-2A202603810

**Phần việc phụ trách:**

- Nhóm trưởng: fork repo, điều phối nhóm qua CP3–CP6.
- Đưa candidate được chọn (Tóm tắt hồ sơ bệnh án khi ra viện); vẽ quy trình trước/sau; research nguồn; đề xuất mức can thiệp AI và quyết định.

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Pitch card tóm tắt ra viện (~8 phút); phản biện card VinFast của Đức Anh.
- Điều phối gom 9 candidate thành 2 cluster, chốt outcome của cây OST.
- Vẽ sơ đồ quy trình hiện tại và tương lai (`report/assets/cp2-workflow-card-1.png`).
- Tìm nguồn `[N1]`–`[N7]` (Stanford, Williams et al., BV Nhi Đồng, mẫu biểu Bộ Y tế).
- Đưa bản Problem Statement 6 trường làm khung cho v0; đề xuất Rule trước → Workflow, không dùng Agent; quyết định Not Yet cho LLM, làm ngay Template.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `group_report.md` mục 2.1 (card #1–#3), 2.2–2.3, 4, 5, 6, 8; `report/assets/cp2-workflow-card-1.png`; `report/individual/2A202603810_PhanTranManhCuong.md` mục 4.

**Điều mình học được từ phần nhóm:**

- Học hỏi thêm kinh nghiệm trao đổi giữa các thành viên.

### CungDucAnh-2A202603814

**Phần việc phụ trách:**

- Pitch Problem Card #1 (Hệ thống hỗ trợ tra cứu lịch sử sửa chữa và lập lệnh tiếp nhận xe tại xưởng VinFast)
- Phản biện trực tiếp Card #1 của Cường về đối tượng hưởng lợi và bản chất tối ưu chi phí vs thời gian
- Phụ trách kiểm chứng giả định (Assumption Map & rà soát dữ liệu đối sánh CP4)
- Tham gia xây dựng Problem Statement v0/v1 và rà soát boundary an toàn y tế (CP5, CP6)

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Đóng góp bài toán xuất phát điểm (Card VinFast) cho nhóm thảo luận
- Đặt câu hỏi phản biện then chốt giúp Cường thu hẹp phạm vi bài toán Vinmec về đúng vai trò của bác sĩ điều trị và gạch bỏ lời hứa phi thực tế về việc "giúp bệnh nhân về sớm"
- Cùng nhóm hoàn thiện bản Problem Statement v0 và v1, đặc biệt là ranh giới (Boundary) và Success Metric đo bằng log bệnh án
- Đóng góp vào phần đánh giá 4 rủi ro và đồng thuận quyết định Not Yet kèm ngưỡng dừng đo lường được

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `report/individual/2A202603814_CungDucAnh.md` (Báo cáo cá nhân đầy đủ CP1, CP2, CP7)
- `report/individual/2A202603810_PhanTranManhCuong.md` (Ghi nhận phần phản biện qua lại giữa Cường và Đức Anh ở mục 4)
- `report/team/group_report.md` (Mục 2.1 dòng Pitch của Cung Đức Anh và Phan Trần Mạnh Cường; Mục 3 Assumption map; Mục 5 Problem Statement v0; Mục 7 Problem Statement v1)

**Điều mình học được từ phần nhóm:**

- Học được cách gắn nhãn nguồn kiểm chứng `[N]` và nhãn giả định `[GĐ]` để phân biệt rõ ràng giữa số liệu thực chứng và phỏng đoán chủ quan.
- Hiểu sâu sắc sự khác biệt giữa Solution trá hình và Opportunity thực sự trong cây OST (Opportunity Solution Tree).
- Nhận thức rõ ràng nguyên tắc *Problem first, AI second*: ưu tiên giải pháp đơn giản nhất (Rule template tự điền) trước để đo lường baseline, kiên quyết chọn Not Yet cho AI khi chưa đủ điều kiện an toàn.

### HoangThePhong-2A202603832

**Phần việc phụ trách:**

- Research giải pháp đã có (CP4); chuyển quy trình sang Mermaid và rà điểm bàn giao (CP5); phản biện Problem Statement, mức can thiệp và 4 rủi ro (CP5–CP6).

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Pitch 3 card (feedback giảng viên, ôn thi, Xanh SM đồ thất lạc).
- Tìm các giải pháp đã có (Epic, Nabla, Nuance DAX, pilot ở bệnh viện) và mẫu 52/BV2; tự mở link, bỏ link chết và loại công cụ ghi âm khám ngoại trú khỏi bảng research.
- Đề xuất tách bước "chép dữ liệu" và "viết diễn biến + lời dặn" trong quy trình; thêm nhánh quay về khi AI lỗi.
- Dùng AI phản biện Problem Statement: thu hẹp actor về bác sĩ 1 khoa Nội, đo bằng log, thêm 0 sai lệch thuốc/liều; bác bỏ mức Agent; đề xuất nâng rủi ro Feasibility/Viability.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `group_report.md` mục 2.1 (card #7–#9), 3.3 (ghi chú loại ambient scribe), 4, 5 (phản biện v0), 8.1; `report/individual/2A202603832_HoangThePhong.md` mục 4–5.

**Điều mình học được từ phần nhóm:**

- Problem tốt phải chỉ ra dữ liệu nằm ở đâu và bước nào template là đủ, trước khi nghĩ tới AI.
