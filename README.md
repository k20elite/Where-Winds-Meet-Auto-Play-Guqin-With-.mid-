# WWM Guqin Freeplay

## 🇬🇧 English Overview
**WWM Guqin Freeplay** is a standalone, portable automation tool designed to parse MIDI files and simulate hardware-level keyboard inputs for in-game musical instruments (tailored for *Where Winds Meet* and *Justice Online*). 

It utilizes a custom **Heuristic Pitch Detection** algorithm to enforce a "Strict Diatonic" mode, ensuring clean, artifact-free audio playback by eliminating game-induced pitch bending.

### Key Features
* **Zero-Dependency:** Portable executable. No Python installation or external libraries required.
* **Low-Latency Injection:** Direct hardware scan-code simulation (Win32 API) to bypass anti-cheat hooks.
* **Smart Transpose Engine:** Automatically analyzes key signatures and transposes compositions to C Major/A Minor.
* **Pure Tone Mode:** Aggressively filters accidental notes (sharps/flats) to prevent audio distortion in-game.
* **Global Hotkey:** Toggle playback via **Scroll Lock** without losing game focus.

### Usage Guide
1.  **Launch:** Run `WWM Guqin Freeplay.exe` as **Administrator** (recommended for high-priority input access).
2.  **Load Music:** Click **"Open MIDI Directory"** and select your folder containing `.mid` files.
3.  **Select Track:** Choose a song from the list.
4.  **Play:** * Press the **PLAY** button in the UI, OR
    * Press **Scroll Lock** on your keyboard while inside the game.

---

## 🇻🇳 Tiếng Việt: Giới thiệu
**WWM Guqin Freeplay** là phần mềm tự động hóa chuyên dụng (dạng Portable - chạy ngay) giúp chuyển đổi file nhạc MIDI thành tín hiệu bàn phím để chơi đàn trong game *Where Winds Meet* và *Nghịch Thủy Hàn*. 

Công cụ sử dụng thuật toán **Dò Giọng Thông Minh** để ép bài hát về giọng Đô Trưởng (C Major), loại bỏ hoàn toàn các nốt thăng/giáng (Shift/Ctrl), giúp âm thanh trong trẻo và chuẩn xác nhất.

### Tính năng nổi bật
* **Độ trễ cực thấp (Low-latency):** Sử dụng tín hiệu Scan Codes phần cứng để thao tác phím chuẩn xác từng mili-giây.
* **Tự động dịch giọng (Auto Transpose):** Tự tính toán để đưa bài nhạc về dải phím phù hợp nhất với game.
* **Chế độ "Natural Keys Only":** Tự động khử nốt đen, đảm bảo giai điệu mượt mà, không bị méo tiếng.
* **Phím tắt toàn cục:** Bấm **Scroll Lock** để Bật/Tắt nhạc ngay trong game mà không cần Alt-Tab.

### Hướng dẫn sử dụng
1.  **Khởi chạy:** Mở file `WWM Guqin Freeplay.exe` (Nên chạy dưới quyền **Run as Administrator** để đảm bảo game nhận phím tốt nhất).
2.  **Nạp dữ liệu:** Nhấn **"Open MIDI Directory"** để chọn thư mục chứa nhạc MIDI.
3.  **Chọn bài:** Chọn bài hát từ danh sách.
4.  **Thưởng thức:** * Nhấn **PLAY** trên giao diện, HOẶC
    * Nhấn phím **Scroll Lock** trên bàn phím khi đang ở trong game.

---

### ⚠️ Disclaimer
This tool is provided "as-is" for educational purposes. Use responsibly within game terms of service.
