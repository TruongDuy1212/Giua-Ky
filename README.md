# 🎮 MiniGame Pro — React + Node WebSocket

Ứng dụng demo *mini-games realtime* phục vụ đồ án **Lập Trình Mạng**.  
Bao gồm frontend React (Vite) và backend NodeJS + WebSocket Server.

---

## 🚀 Chạy project

### 🔧 1. Backend (NodeJS + WebSocket)
```bash
cd backend
npm install
npm start
**Server mặc định chạy tại:**
http://localhost:9000
Nếu cổng 9000 đang bận, server sẽ tự đổi sang 9001, 9002...
→ Terminal sẽ in ra URL chính xác, ví dụ:
Backend http://localhost:9001

Frontend (React + Vite)
cd frontend
npm install
npm run dev

Vite sẽ hiển thị link, ví dụ:
http://localhost:5173
Mở trình duyệt → truy cập link Vite → nhập URL WebSocket:
ws://localhost:9000
(hoặc cổng mới mà backend sinh ra, ví dụ ws://localhost:9001)

Nhấn Connect để kết nối.
🎮 Các Game triển khai
✊✋✌ RPS – Rock Paper Scissors

Hai người cùng chọn → server chấm thắng thua.

Nếu phòng chỉ có 1 người → server tự sinh đối thủ bot.

Server quản lý state + reset tự động.

🔢 Guess Number (1–100)

Server sinh số bí mật.

Client đoán, server trả:

low

high

correct

Reset khi đoán đúng.

⭕❌ TicTacToe

Server giữ board 3×3.

Gửi lượt cho từng người.

Phát hiện:

thắng

hòa

reset tự động khi kết thúc.
