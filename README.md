# Track1_Day22 — Monetization & GTM · Nguyễn Văn Biển (2A202602416)

**Sản phẩm: CaTối** — AI trực inbox Fanpage cho shop thời trang dùng Haravan. AI trả lời xong các hội thoại hỏi giá / size / còn hàng / phí ship và lên đơn nháp vào Haravan, chủ yếu trong ca tối (21h–23h30) khi chủ shop vừa đóng gói đơn vừa trực inbox.

## File nộp

| File | Nội dung |
| :--- | :--- |
| [NguyenVanBien_Day22_model.xlsx](NguyenVanBien_Day22_model.xlsx) | File Excel 5 tab hoàn chỉnh (chỉ điền ô vàng, lý do từng ô ở cột E), cùng 2 tab bổ trợ: `7_Stress_Test`, `8_AI_Critique_Log` |
| [NguyenVanBien_Day22_onepager.pdf](NguyenVanBien_Day22_onepager.pdf) | Monetization One-Pager. Mọi con số được đọc thẳng từ Excel đã recalculate |

## 5 con số

| Chỉ số | Giá trị | Ô Excel |
| :--- | :--- | :--- |
| Cost/Job (Biến thể A, chia cho job **hoàn thành**) | $0,0470 ≈ 1.232₫ | `2_Pricing!B5` |
| Giá sàn (3×) | $0,1411 ≈ 3.696₫ | `2_Pricing!B7` |
| Giá bán | **3.900₫ / hội thoại xử lý xong** ($0,1489) | `2_Pricing!B19` |
| Gross Margin | **68,4%** | `2_Pricing!B21` |
| Breakeven containment (GM 60%) | **55,3%**, so với mức ước tính 70% (chưa có eval) | `2_Pricing!B33` |

**Value Metric:** Hybrid, gồm phí tối thiểu 1.560.000₫/tháng (đã gồm 400 hội thoại) cộng 3.900₫/hội thoại xử lý xong. **Kênh:** Partner-Led qua Haravan (chưa liên hệ; deadline có/không là 30/10/2026). Ngân sách CAC $1.284, trong khi CAC theo benchmark ICONIQ là $25.200 (lệch 19,6×).

**Mô hình gãy khi:** containment < 44% hoặc chi phí LLM/job tăng ≥ 1,8×. Ví dụ: phải nâng từ Haiku 4.5 lên Sonnet 5.5 thì GM chỉ còn 46,6%.

Giá API kiểm tra ngày **08/10/2026**. Tỷ giá 26.190 ₫/USD (giá bán Vietcombank 06/10/2026).

## Final Checklist (§5.8)

- [x] 1–2. Tab 1 đủ 5 thành phần chi phí; mẫu số là job HOÀN THÀNH (1.050, không phải 1.500)
- [x] 3–4. Tab 2: giá = 3,17× Cost/Job, GM 68,4%; breakeven 55,3% đã so với containment ước tính 70%
- [x] 5. Tab 3: Value Metric, Decision Note, 2 benchmark có link
- [x] 6. Tab 4: ngân sách CAC, số deal/AE/ngày, chỉ 1 kênh (Haravan, chưa liên hệ, có deadline)
- [x] 7. Tab 5: 90-day plan có số và người chịu trách nhiệm; Evidence Pack có deadline
- [x] 8. Ngày kiểm tra giá API: 08/10/2026 (`6_Benchmarks!B3`)
- [x] 9. One-Pager đủ 3 khối, số khớp Excel
- [x] 10. Prompt §4.7: tự chạy lại 4.7.1 và 4.7.5, ghi accept/reject/partial (tab `8_AI_Critique_Log`, phần B)
- [x] Bài test người lạ: 3/3 câu trả lời được, chỉ hỏi lại 1 câu (breakeven), đạt mục tiêu ≤ 3 (`5_90Day_Plan!B29:B32`)
