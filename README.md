# Software-Engineering-Project
## 📌 Giới thiệu
Đây là Repo cho đồ án môn Nhập môn công nghệ phần mềm

## 👥 Thành viên
- Đinh Quốc Bình    23120217
- Trần Khánh Dư     23120234
- Trần Đại Hiệp     23120256
- Nguyễn Hoàn Long  22120193

## 🤝 Quy tắc làm việc nhóm trên GitHub

### 🌐 Ngôn ngữ sử dụng

* Có thể dùng Tiếng Việt hoặc Tiếng Anh
* Ưu tiên:
    * Viết sao cho dễ hiểu với bản thân và người khác
    * Giữ cách viết nhất quán
* Khuyến khích:
    * Code, tên biến: dùng Tiếng Anh
    * Comment, mô tả: có thể dùng Tiếng Việt hoặc Anh

Để tránh xung đột code và làm việc hiệu quả, mọi người tuân thủ các quy tắc sau:

### 📌 1. Không code trực tiếp lên `main`

* Luôn tạo branch mới khi làm task:

```bash
git checkout -b feature-ten-chuc-nang
```

---

### 📌 2. Luôn pull code mới trước khi làm

```bash
git pull
```

👉 Tránh việc code trên phiên bản cũ gây conflict

---

### 📌 3. Sau khi code xong

```bash
git add .
git commit -m "mô tả thay đổi"
git push origin ten-branch
```

---

### 📌 4. Tạo Pull Request (PR)

* Không merge trực tiếp vào `main`
* Tạo PR trên GitHub để review trước khi merge

---

### 📌 5. Đặt tên branch rõ ràng

* `feature-login`
* `fix-bug-login`
* `update-ui-home`

---

### 📌 6. Không push các file không cần thiết

* Không push `venv/`
* Không push file hệ thống

---

### 📌 7. Nếu có conflict

* Bình tĩnh
* Pull về → resolve → commit lại

---

## 🎯 Mục tiêu

* Tránh conflict
* Dễ quản lý code
* Làm việc chuyên nghiệp như team thật


## 🛠️ Công nghệ
* Python và các thư viện trong file requirement.txt

## 🚀 Cách chạy project


## 📂 Cấu trúc thư mục
```bash
project-root/
│
├── src/                       # Chứa toàn bộ source code
│   ├── backend/               # Xử lý logic phía sau
│   ├── frontend/              # Giao diện người dùng
│   └── common/                # Code dùng chung
│
├── docs/                      # Chứa tài liệu dự án
│   ├── management/            # Kế hoạch & báo cáo
│   │   ├── weekly-reports/    # Báo cáo hàng tuần
│   │   ├── project-status/    # Báo cáo tiến độ
│   │   └── planning-docs/     # Tài liệu lập kế hoạch
│   │
│   ├── requirements/          # Tài liệu yêu cầu
│   │   ├── vision-doc/        # Vision document
│   │   └── use-cases/         # Use case
│   │
│   ├── analysis-and-design/   # Phân tích & thiết kế
│   │   ├── architecture/      # Kiến trúc hệ thống
│   │   ├── uml/               # Sơ đồ UML
│   │   └── ui-design/         # Thiết kế UI
│   │
│   └── test/                  # Tài liệu kiểm thử
│       ├── test-plan/         # Kế hoạch test
│       ├── test-cases/        # Test case
│       └── test-reports/      # Báo cáo test
│
├── pa/                        # Nơi lưu các lần nộp bài (PA)
│   ├── pa1/
│   ├── pa2/
│   └── pa3/
│
├── README.md                  # Mô tả project
└── requirements.txt           # Thư viện Python sử dụng
```
