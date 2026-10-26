# Demo trang chi tiết sản phẩm — Thiết bị mầm non Việt Mỹ

Trang chi tiết sản phẩm dựng theo Figma **"[Viet My] Website"**, frame `16680-30490` (bản desktop + mobile + bảng chọn mẫu trên mobile).

- Xem trực tiếp: https://lanvi-commits.github.io/demo-chi-tiet-san-pham-thiet-bi-mam-non-viet-my/
- 1 file `index.html` tự chứa: ảnh, font Plus Jakarta Sans và icon đều nhúng sẵn, không tải gì từ site khác. Có `noindex`.

## Bấm thử được gì

- Đổi ảnh sản phẩm (ảnh nhỏ, mũi tên, vuốt trên mobile).
- Chọn kích thước / màu → giá, giá gốc, nhãn % và dòng "Bạn tiết kiệm" đổi theo. Chỉ size **Vừa** có giá gốc, nên chọn Nhỏ/Lớn thì nhãn % ẩn.
- Số lượng và lựa chọn đồng bộ giữa khối mua chính, thanh mua dính đáy và bảng chọn mẫu (mobile).
- Thêm giỏ / thêm báo giá → số trên header tăng giảm. Mobile: bấm "Mua Ngay" hoặc giỏ ở thanh đáy sẽ mở bảng chọn mẫu trước.
- Chú thích ⓘ, câu hỏi thường gặp, "Xem Thêm" mô tả, lọc đánh giá, nút "Hữu ích".
- Desktop: thanh mua dính đáy hiện khi đã cuộn qua nút mua. Mobile: tab mục dính đầu trang, tự sáng theo vị trí cuộn.

Các liên kết sang trang khác chỉ hiện thông báo "Demo", không chuyển trang. Nút Chat Zalo / số điện thoại của 5 tư vấn viên trong băng mobile là số thật.

## Nội dung

Chữ giữ nguyên Figma. Lưu ý Figma đang lẫn 2 sản phẩm: tên + ảnh là *Vòng xoay vận động VM-6311*, còn breadcrumb, mã VM-CT0015, thông số, mô tả, FAQ, đánh giá, thanh mua dính là *Bàn mầm non gỗ cao cấp ABC*. Giá, đánh giá, số đã bán là số mẫu của Figma, chưa phải số thật.

Ảnh là ảnh sản phẩm thật của Việt Mỹ trên site đang dựng (vòng xoay VM-6311, ghế nhựa VM-0201, bàn gỗ, ảnh tư vấn viên).

## Sửa

`index.html` là bản build từ `Design UX-UI/brands/viet-my/nguyen-lieu/2026-10-26_trang-san-pham-figma-build/` — sửa `src.html` → chạy `python3 build.py` → commit + push. Đừng sửa tay `index.html`.
