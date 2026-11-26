# BÀI LÀM PHA 2 – HACKATHON 02

- **Mã đề:** 08
- **Họ tên:** Võ Xuân Thịnh
- **Lớp:** HCM_KS26_CNTT2
- **Link repository Pha2:** https://github.com/HCM-KS26-CNTT2-IT206/HCM-KS26-CNTT2_PromptAI_H02
- **Công cụ AI đã dùng (ChatGPT/Claude/Gemini):** ChatGPT

> Pha 2 (20 phút cuối). Mỗi mục: mở cuộc trò chuyện mới, gửi nguyên văn prompt đã viết trong bai_lam_pha1.md, dán câu trả lời và link chia sẻ vào đây. Xong, kéo thả file này vào repository Pha2.

## 4.2. Trích xuất tin nhắn đặt lịch khám ra JSON

**KET QUA AI**

```text
[
  {
    "ma_dich_vu": "TRAM",
    "ngay_hen": "2026-12-17",
    "nguoi_lon": 2,
    "tre_em": 1,
    "khung_gio": "chieu",
    "ghi_chu": null
  },
  {
    "ma_dich_vu": "CAOVOI",
    "ngay_hen": "2027-01-06",
    "nguoi_lon": 3,
    "tre_em": 0,
    "khung_gio": null,
    "ghi_chu": "Một người bị tiểu đường"
  },
  {
    "ma_dich_vu": "TAYTRANG",
    "ngay_hen": null,
    "nguoi_lon": 4,
    "tre_em": 0,
    "khung_gio": "sang",
    "ghi_chu": "Một người dị ứng thuốc tê"
  }
]
```

**Link trò chuyện:**
https://chatgpt.com/c/6b07e3bc-84b0-83ec-b57f-3051bdc6b95d

## 4.3. Báo giá bằng Chain-of-Thought

**KET QUA AI**

```text
Bước 1: Tiền người lớn
Có 6 người lớn sử dụng dịch vụ CAOVOI.
- Giá cạo vôi răng: 350.000 đồng/người.
- Phép tính: 6 × 350.000 = 2.100.000 đồng.
Bước 2: Tiền trẻ em
- Trẻ 7 tuổi: 350.000 × 80% = 280.000 đồng.
- Trẻ 11 tuổi: 350.000 × 80% = 280.000 đồng.
- Trẻ 4 tuổi: Được khám miễn phí = 0 đồng.
Tổng tiền trẻ em: 280.000 + 280.000 + 0 = 560.000 đồng.
Bước 3: Tiền dịch vụ
Tiền dịch vụ = Tiền người lớn + Tiền trẻ em.

2.100.000 + 560.000 = 2.660.000 đồng.
Bước 4: Giảm giá nhóm
- Nhóm có 6 người lớn, đủ điều kiện giảm giá 10% (từ 5 người lớn trở lên).
- Số tiền giảm: 2.660.000 × 10% = 266.000 đồng.
- Tiền dịch vụ sau giảm: 2.660.000 − 266.000 = 2.394.000 đồng.
Bước 5: Phí chụp X-quang
- Có 3 người, mỗi người chụp 1 phim.
- Phí mỗi phim: 150.000 đồng.
- Phép tính: 3 × 150.000 = 450.000 đồng.
Bước 6: Tổng tiền
Tổng tiền = Tiền dịch vụ sau giảm + Phí chụp X-quang.

2.394.000 + 450.000 = 2.844.000 đồng.

[RESULT :2.844.000 đồng]
```

**Link trò chuyện:**
https://chatgpt.com/c/6b07e43f-7d4c-83ec-a831-7ffb2399f98d

### b) Kiểm tra kết quả AI
kết quả đúng 

## 4.4. Dây chuyền xử lý khiếu nại – kết quả Trạm 1

**KET QUA AI**

```text
{
  "loai_su_co": "tre_hen",
  "so_khach": 3,
  "so_lan_hen_bi_tre": 2,
  "tom_tat": "Gia đình 3 người phải chờ hơn 1 tiếng trong cả 2 lần hẹn; không phàn nàn về bác sĩ."
}
```

**Link trò chuyện:**
https://chatgpt.com/share/6b07e568-b144-83ec-9979-bd7f1ef605cb
## 4.5. Prompt chấm bài theo Rubric

**KET QUA AI**

```text
(Dán câu trả lời của AI vào đây (bấm nút Copy dưới câu trả lời) – xoá dòng này)
```

**Link trò chuyện:**
