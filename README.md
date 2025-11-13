MiniGame Pro (React + Node WebSocket)
Run
Backend
cd backend
npm install
npm start
Ghi chú: server auto đổi cổng nếu 9000 bận, ví dụ 9001. Console sẽ in URL.

Frontend
cd frontend
npm install
npm run dev
Mở URL Vite (ví dụ http://localhost:5173), nhập ws://localhost:9000 (hoặc cổng server in ra) vào ô Server URL → Connect.

Tính năng
Splash/Lobby gradient + float animation (CSS), nút có hiệu ứng hover/press.
Lobby: danh sách phòng, chat realtime, đổi game (RPS / Guess / TicTacToe).
Games:
RPS: chấm kết quả server-side; phòng 1 người có đối thủ bot.
GuessNumber: đoán 1..100, server trả low/high/correct.
TicTacToe: server giữ state, relay lượt; reset khi win/draw.
Pong: demo offline trên canvas (dễ chụp ảnh + trình bày).
Gợi ý nộp bài
Chụp Splash (có animation), Lobby (list + chat), các màn RPS/Guess/TTT, và terminal server.
