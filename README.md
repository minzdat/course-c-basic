<div align="center">

# 📘 Học Lập Trình C Cơ Bản

> **Nền tảng học lập trình C trực quan, hiện đại — không cần cài đặt**

[![Live Demo](https://img.shields.io/badge/🌐_Live_Demo-GitHub_Pages-blue?style=for-the-badge)](https://minzdat.github.io/course-c-basic/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Vue.js](https://img.shields.io/badge/Vue.js_3-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white)](https://vuejs.org/)
[![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)

</div>

---

## 📖 Giới thiệu

**Học Lập Trình C Cơ Bản** là một web app học lập trình C được thiết kế dành cho sinh viên và người mới bắt đầu. Toàn bộ nội dung 8 chương được tích hợp sẵn trong **một file HTML duy nhất**, không cần backend, không cần cài đặt bất kỳ thứ gì. Chỉ cần mở trình duyệt là học được ngay.

### ✨ Điểm nổi bật

| Tính năng | Mô tả |
|-----------|-------|
| 📚 **8 Chương học đầy đủ** | Từ biến, kiểu dữ liệu đến Struct & Con trỏ |
| 🌐 **Song ngữ VI / EN** | Toàn bộ nội dung, bài tập đều có tiếng Anh |
| 💻 **Xem Code & Output** | Trình xem mã nguồn + màn hình Console mô phỏng |
| 📋 **Copy Code 1 Click** | Nút copy tích hợp sẵn trong khối code |
| 🧪 **Bài tập + Lời giải** | Toggle hiện/ẩn đáp án theo từng bài |
| 📥 **Tải giáo trình Word** | Xuất toàn bộ nội dung ra file `.doc` |
| 📱 **Responsive hoàn toàn** | Tối ưu cho cả mobile, tablet và desktop |
| ⚡ **Không cần Backend** | Chạy 100% trên trình duyệt, không cần server |

---

## 🗂️ Nội dung chương trình

| Chương | Chủ đề | Độ lệch |
|:------:|--------|---------|
| 1 | Biến, Kiểu dữ liệu & Nhập/Xuất chuẩn | Nền tảng |
| 2 | Toán tử và Biểu thức | Nền tảng |
| 3 | Cấu trúc điều khiển (Rẽ nhánh & Vòng lặp) | Trung cấp |
| 4 | Hàm (Functions) | Trung cấp |
| 5 | Mảng (Arrays) | Trung cấp |
| 6 | Chuỗi Ký Tự (Strings) | Trung cấp |
| 7 | Con trỏ cơ bản (Pointers) | Nâng cao |
| 8 | Kiểu Cấu trúc (Structs) | Nâng cao |

---

## 🧱 Công nghệ sử dụng

- **[Vue.js 3](https://vuejs.org/)** — Framework phản ứng (CDN, không cần build) cho UI tương tác
- **[Tailwind CSS](https://tailwindcss.com/)** — Utility-first CSS framework (CDN)
- **[Google Fonts](https://fonts.google.com/)** — `Inter` (giao diện) + `Fira Code` (code block)
- **Vanilla JavaScript** — Logic app (copy clipboard, download Word, animation)
- **HTML5** — Cấu trúc trang, ngữ nghĩa, SEO

### 📐 Kiến trúc

```
Single-Page Application (SPA) — File đơn duy nhất
┌───────────────────────────────────────────────────┐
│  index.html                                       │
│  ├── <head>   (Meta, CDN Links, Custom CSS)       │
│  ├── <body>                                       │
│  │   ├── Header (Tiêu đề, Nút ngôn ngữ, Download)│
│  │   ├── Sidebar Desktop (Danh sách chương)       │
│  │   ├── Mobile Drawer (Responsive menu)          │
│  │   └── Main Content (Theory / Code / Exercises) │
│  └── <script> (Vue 3 App + courseData JSON)       │
└───────────────────────────────────────────────────┘
```

---

## 📂 Cấu trúc Project

```
course-c-basic-w/
├── index.html       # Toàn bộ ứng dụng (HTML + CSS + JS + Data)
└── README.md        # Tài liệu dự án
```

> **Ghi chú:** Toàn bộ dữ liệu 8 chương (lý thuyết, code ví dụ, bài tập, lời giải) được lưu trực tiếp trong `index.html` dưới dạng JavaScript object, đảm bảo hoạt động hoàn toàn offline.

---

## ⚙️ Hướng dẫn Cài đặt & Chạy

### Cách 1: Mở trực tiếp (Đơn giản nhất)

1. **Clone** repository về máy:
   ```bash
   git clone https://github.com/minzdat/course-c-basic.git
   cd course-c-basic
   ```

2. Mở file `index.html` bằng bất kỳ trình duyệt nào:
   ```bash
   # macOS
   open index.html
   
   # Linux
   xdg-open index.html
   
   # Windows
   start index.html
   ```

### Cách 2: Dùng Live Server (Khuyến khích cho Developer)

Nếu bạn dùng **VS Code**, cài extension [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer):

1. Chuột phải vào `index.html`
2. Chọn **"Open with Live Server"**
3. Trình duyệt tự động mở tại `http://127.0.0.1:5500`

### Cách 3: Xem trực tiếp Online

👉 **[https://minzdat.github.io/course-c-basic/](https://minzdat.github.io/course-c-basic/)**

---

## 🚀 Deploy lên GitHub Pages

1. Push code lên GitHub repository
2. Vào **Settings → Pages**
3. Chọn nguồn:
   - **Branch:** `main`
   - **Folder:** `/ (root)`
4. Nhấn **Save**

Website sẽ tự động deploy tại:
```
https://<username>.github.io/<repository-name>/
```

---

## 🖥️ Giao diện Demo

```
┌────────────────────────────────────────────────────────┐
│ [≡] 📗 Lập Trình C Cơ Bản      [↓ Tải Word] [🌐 EN]  │
├──────────────────┬─────────────────────────────────────┤
│ MỤC LỤC GIÁO    │  CHƯƠNG 1                           │
│ TRÌNH            │  Biến, Kiểu dữ liệu & I/O          │
│                  │                                     │
│ ▶ Ch.1 [active]  │  📖 Kiến thức trọng tâm            │
│   Ch.2           │  ─────────────────────────         │
│   Ch.3           │  Lý thuyết HTML...                 │
│   Ch.4           │                                     │
│   Ch.5           │  🖥️ Mã nguồn minh họa              │
│   Ch.6           │  ┌────────────────────────┐        │
│   Ch.7           │  │ MAIN.C │ CONSOLE OUTPUT│        │
│   Ch.8           │  │ [▶ Run]               │        │
│                  │  │  #include <stdio.h>   │        │
│                  │  └────────────────────────┘        │
│                  │                                     │
│                  │  ✏️ Bài tập thực hành               │
│                  │  [ Bài 1.1 ] [ Bài 1.2 ]           │
│                  │  [Xem bài giải]                    │
│                  ├─────────────────────────────────────┤
│                  │  [← Chương trước]  [Chương tiếp →] │
└──────────────────┴─────────────────────────────────────┘
```

---

## 🔑 Các tính năng kỹ thuật nổi bật

### 🔄 Hệ thống đa ngôn ngữ (i18n)
Toàn bộ nội dung (tiêu đề, lý thuyết, bài tập, lời giải, UI labels) đều được lưu song ngữ `vi` / `en`. Toggle chuyển đổi tức thì bằng Vue.js reactive state.

### 📑 Xuất giáo trình Word
Tính năng `handleDownload` tạo file `.doc` từ toàn bộ nội dung hiện tại (theo ngôn ngữ đang chọn) bằng cách tạo Blob với MIME type `application/msword`.

### 📋 Copy Code
Sử dụng `document.execCommand('copy')` với phản hồi trực quan (nút đổi sang trạng thái "Đã chép!" trong 2 giây).

### 📱 Responsive Mobile
- **Desktop (≥1024px):** Sidebar cố định bên trái
- **Mobile/Tablet (<1024px):** Sidebar chuyển thành Drawer overlay với animation slide-in

---

## 🤝 Đóng góp

Mọi đóng góp đều được hoan nghênh!

1. **Fork** repository này
2. Tạo branch mới: `git checkout -b feature/ten-tinh-nang`
3. Commit thay đổi: `git commit -m 'feat: Thêm chương 9 - File I/O'`
4. Push lên branch: `git push origin feature/ten-tinh-nang`
5. Tạo **Pull Request**

---

## 📄 Giấy phép

Dự án này được phân phối dưới giấy phép **MIT License**. Xem file [LICENSE](LICENSE) để biết thêm chi tiết.

---

## 👨‍💻 Tác giả

<div align="center">

**Trương Minh Đạt (Darren)**

[![GitHub](https://img.shields.io/badge/GitHub-minzdat-181717?style=flat-square&logo=github)](https://github.com/minzdat)

*Xây dựng với ❤️ để giúp đỡ sinh viên học lập trình C*

</div>
