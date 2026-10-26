# BÀI LÀM – THI THỬ HACKATHON 02 (GAMEZONE)

- **NGUYEN TRUNG THANH:** 
- **Lớp:** 
- **Link repository:** 
- **Hệ điều hành (Windows/macOS):** 

## 4.2. Thao tác CLI

### Các lệnh đã chạy

```shell
# Ghi lệnh vào đây

```

### Kết quả liệt kê toàn bộ dự án

```text
(Dán kết quả vào đây)

```

## 4.3. Lọc log thủ công

### Lệnh đã chạy

```shell
# Ghi lệnh vào đây

```

### 2 dòng lỗi đầu tiên trong daily_report.txt

```text
(Dán kết quả vào đây)

```

## 4.4. README.md

> Chấm trực tiếp trên `README.md` ở gốc dự án.

- [ ] Heading 1
- [ ] Mô tả in đậm + in nghiêng
- [ ] Bảng `Thư mục | Nội dung` (≥3 dòng)
- [ ] Code block lệnh liệt kê
- [ ] Task list (≥2 việc, ≥1 đã xong)
- [ ] Blockquote nhắc không upload `.env`

## 4.5. Chạy script auto_report

### Lệnh chạy

```shell ### 4.5. Hoàn thiện script `auto_report`
**Lệnh chạy:**
.\auto_report.ps1

**Nội dung logs/auto_report.txt:**
[Dán nội dung bạn vừa copy từ file auto_report.txt vào đây]

```

### Nội dung file logs/auto_report.txt

```text
(Dán kết quả vào đây)

```

## 4.6. Đếm số dòng lỗi

### Lệnh

```shell
#  Select-String -Pattern "ERROR" logs\game.log | Measure-Object


Count    : 6
Average  :
Sum      :
Maximum  :
Minimum  :
Property :


```

### Kết quả đếm

```text
(Dán kết quả vào đây)

```

## 4.7. Báo cáo tổng hợp

### Các lệnh đã chạy

```shell
echo "=== TONG HOP LOG GAMEZONE ===" > logs\tong_hop.txt
Select-String -Pattern "WARNING" logs\game.log >> logs\tong_hop.txt
(Select-String -Pattern "ERROR" logs\game.log | Measure-Object).Count >> logs\tong_hop.txt

**Nội dung file logs/tong_hop.txt:**
[Bạn hãy copy kết quả hiển thị trên màn hình PowerShell ở Bước 2 và dán vào đây]

```

### Nội dung file logs/tong_hop.txt

```text
(Dán kết quả vào đây)

```

## 4.8. Excel

> Chấm trực tiếp trên file `data/giao_dich_thang_11.xlsx`.
