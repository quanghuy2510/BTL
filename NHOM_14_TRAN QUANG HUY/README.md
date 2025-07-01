
## 📁 Cấu trúc thư mục

```
secure-voice-chat/
├── app.py                 # Server backend (WebSocket)
├── crypto_utils.py        # Tiện ích mã hóa
├── index.html            # Frontend Bootstrap
├── requirements.txt      # Dependencies Python
└── README.md            # Tài liệu này
```

## 🛠️ Cài đặt và chạy

### Yêu cầu hệ thống
- Python 3.7+
- Trình duyệt web hỗ trợ WebRTC
- Microphone cho ghi âm

### Bước 1: Cài đặt dependencies

```bash
pip install -r requirements.txt
```

### Bước 2: Chạy server

```bash
python app.py
```

Server sẽ chạy trên `ws://localhost:8765`

### Bước 3: Mở frontend

Mở file `index.html` trong trình duyệt web hoặc phục vụ qua HTTP server:

```bash
# Phương pháp 1: Mở trực tiếp
open index.html

# Phương pháp 2: Sử dụng Python HTTP server
python -m http.server 8000
# Sau đó truy cập http://localhost:8000
```

