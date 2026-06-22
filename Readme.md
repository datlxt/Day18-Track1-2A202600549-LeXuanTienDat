# Day 18 — Human-Centered AI Design

**FlashLearn AI** — lát cắt tính năng: *AI đọc nội dung bài học → tạo bộ flashcard nháp → người dùng kiểm tra, sửa, từ chối → học.*

- **Track:** 1 · Biến thể AI Personal Assistant for Students
- **Prototype:** [index.html](index.html) — mở trực tiếp bằng trình duyệt (HTML/CSS/JS thuần, không cần API).
- **Link xem (deploy):** _<dán link GitHub Pages / Netlify đã cấp quyền xem vào đây>_

## Cách mở
Mở `index.html` bằng Chrome/Edge, hoặc deploy GitHub Pages (Settings → Pages → branch `main`).

## Cấu trúc prototype (sidebar 00–07)
| # | Khu vực | Nội dung |
|---|---------|----------|
| 00 | Flow map & phạm vi | Vòng đời + danh sách kịch bản + trong/ngoài phạm vi |
| 01 | Onboarding | AI làm gì / không làm gì / dữ liệu & quyền |
| 02 | Luồng chính (During) | Nhập bài học · F1 AI hỏi tập trung phần nào |
| 03 | Review & Agency | Kiểm tra thẻ + Act/Ask/Don't Act + F2 bằng chứng + F5 độ tin cậy thấp |
| 04 | Failure & Recovery | F4 AI tự tin nhưng SAI → vòng khôi phục hoàn chỉnh |
| 05 | Feedback 2×2 | Đủ 4 ô user/system × explicit/implicit + rationale |
| 06 | Design rationale | Lập luận theo rủi ro & khả năng khôi phục |
| 07 | Demo path | Kịch bản bấm 5 phút |

## Đối chiếu điều kiện tối thiểu
- [x] Onboarding lần đầu (01)
- [x] ≥4 kịch bản ngoài onboarding: F1, F2, F5 (During/Uncertainty) + F4 (Recovery)
- [x] Lát cắt Onboarding → During → After → Feedback/Recovery
- [x] Đủ Act / Ask / Don't Act (03)
- [x] ≥1 vòng feedback + recovery hoàn chỉnh (04)
- [x] Đủ 4 loại feedback 2×2 (05)
- [x] ≥1 lớp bằng chứng/explainability (nút "Nguồn" + tách 🟦 dữ kiện / 🟨 suy luận)
- [x] Design rationale đặt cạnh flow (06 + thẻ rationale trong từng màn)

## Demo path nhanh
00 Flow map → 01 Onboarding → 02 chip "Bài dài · cả chương" → AI hỏi tập trung → 03 xem Nguồn + thử Act/Ask/Don't Act → 04 Recovery (Đối chiếu nguồn → Báo sai → sửa) → 02 chip "Agency Design" xem F5 → 05 ma trận → 06 rationale.
