# Lingo Cub Warm-up

Trang khởi động đầu giờ cho lớp Lingo Cub (Việt – Anh – Trung, trẻ 4–10 tuổi).
Mỗi Unit là một danh sách bài hát Little Fox tự phát nối tiếp nhau. Con hát hết mỗi bài được 1 sao, đủ sao thì được khen.

## Cấu trúc thư mục

```
index.html                 ← trang chọn Unit
README.md
unit-1/
  index.html               ← Unit 1: Hello & Good-bye (6 bài)
  videos/  (6 .mp4 + 6 .jpg)
unit-2/
  index.html               ← Unit 2: Name & Age (5 bài)
  videos/  (5 .mp4 + 5 .jpg)
unit-3/
  index.html               ← Unit 3: Family (4 bài)
  videos/  (4 .mp4 + 4 .jpg)
unit-4/
  index.html               ← Unit 4: Body & Dance (2 bài, có camera nhảy theo)
  videos/  (2 .mp4 + 2 .jpg)
unit-5/
  index.html               ← Unit 5: Feelings & Actions (4 bài, camera + chỉ dẫn động tác + filter biểu cảm)
  videos/  (4 .mp4 + 4 .jpg)
  lib/face/                ← bộ nhận diện khuôn mặt cho filter (MediaPipe, 8 file)
unit-6/
  index.html               ← Unit 6: What's This? (3 bài)
  videos/  (3 .mp4 + 3 .jpg)
unit-7/
  index.html               ← Unit 7: Things & Places (4 bài)
  videos/  (4 .mp4 + 4 .jpg)
unit-10/
  index.html               ← Unit 10: Weather (4 bài, camera + filter thời tiết)
  videos/  (4 .mp4 + 4 .jpg)
```

Địa chỉ sau khi đưa lên GitHub Pages (ví dụ repo tên `warm-up`):

- Trang chọn Unit: `https://<tài-khoản>.github.io/warm-up/`
- Unit 1: `https://<tài-khoản>.github.io/warm-up/unit-1/`
- Unit 2: `https://<tài-khoản>.github.io/warm-up/unit-2/`
- Unit 3: `https://<tài-khoản>.github.io/warm-up/unit-3/`
- Unit 4: `https://<tài-khoản>.github.io/warm-up/unit-4/`
- Unit 5: `https://<tài-khoản>.github.io/warm-up/unit-5/`
- Unit 6: `https://<tài-khoản>.github.io/warm-up/unit-6/`
- Unit 7: `https://<tài-khoản>.github.io/warm-up/unit-7/`
- Unit 10: `https://<tài-khoản>.github.io/warm-up/unit-10/`

Có thể gửi thẳng link của từng Unit cho lớp.

### Unit 1 · Hello & Good-bye

1. Hello Song · Chào hỏi & Số đếm (tiếng Trung)
2. Good-bye Song · Chào hỏi & Số đếm (tiếng Trung)
3. Good-bye · Learning Songs (tiếng Anh)
4. Good-bye · Learning Songs 1 (tiếng Trung)
5. Hello · Learning Songs (tiếng Anh)
6. Hello · Learning Songs 1 (tiếng Trung)

### Unit 2 · Name & Age

1. What's Your Name? · Sing-Alongs (tiếng Trung)
2. My Name Is Minwoo · Learning Songs (tiếng Anh)
3. My Name Is Minwoo · Learning Songs 1 (tiếng Trung)
4. How Old Are You? (tiếng Anh)
5. How Old Are You? · Learning Songs 1 (tiếng Trung)

### Unit 3 · Family

1. The Finger Family 2 · Learning Songs (tiếng Anh)
2. The Finger Family · Sing-Alongs (tiếng Trung)
3. She's My Mother · Learning Songs (tiếng Anh)
4. She's My Mother · Learning Songs 1 (tiếng Trung)

### Unit 4 · Body & Dance

1. Head and Shoulders · Nursery Rhymes (tiếng Anh)
2. Head and Shoulders · Sing-Alongs (tiếng Trung)

### Unit 5 · Feelings & Actions

1. If You're Happy · Noodle & Pals (tiếng Anh)
2. If You're Happy and You Know It (tiếng Trung)
3. They Are Angry · Learning Songs (tiếng Anh) — có filter biểu cảm
4. They Are Angry · Learning Songs 2 (tiếng Trung) — có filter biểu cảm

### Unit 6 · What's This?

1. What's This? · Learning Songs (tiếng Anh)
2. What's This? · Learning Songs 1 (tiếng Trung)
3. Teacher, Happy Birthday · Chants (tiếng Trung)

### Unit 7 · Things & Places

1. What Is This? (tiếng Anh)
2. 这是什么？ Zhè shì shénme? (tiếng Trung)
3. Where Is the Kitty? · Chants (tiếng Trung)
4. Where Are the Books? (tiếng Anh)

### Unit 10 · Weather

1. How Is the Weather? (tiếng Anh)
2. 天气怎么样？ How Is the Weather? · Sing-Alongs (tiếng Trung)
3. How's the Weather? (tiếng Anh)
4. 天气怎么样？ How's the Weather? · Learning Songs 1 (tiếng Trung)

**Filter thời tiết (Unit 10):** bấm **📷 Bật camera**, camera nằm cạnh video. Khi bài hát đến câu nắng / mây / mưa / gió / tuyết, filter tương ứng tự hiện trên camera (kèm nhãn ba thứ tiếng) và nút đúng nhấp nháy. Học sinh cũng có thể bấm một hình để tự chọn; sang đoạn hát mới thì filter tự đổi lại. Tắt công tắc **Tự đổi theo lời hát** nếu chỉ muốn chọn bằng tay. Thời điểm đổi filter nằm trong `const CUES` của `unit-10/index.html` (giây bắt đầu, giây kết thúc, `"w-sunny"`, `"w-cloudy"`, `"w-rainy"`, `"w-windy"`, `"w-snowy"`); lệch thì sửa số giây.

## Camera nhảy theo (Unit 4, Unit 5)

Bé nhìn thấy mình trên màn hình (như soi gương) để làm động tác theo bài hát.

1. Mở Unit 4 hoặc Unit 5, bấm **📷 Bật camera** trong ô vàng dưới video.
2. Lần đầu, trình duyệt hỏi quyền dùng camera: bấm **Cho phép**.
3. Chọn kiểu hiển thị:
   - **Góc màn hình**: hình bé nằm ở góc trên bên phải video. Bấm **Ô camera to hơn** để phóng to.
   - **Hai khung cạnh nhau**: video và hình bé đứng cạnh nhau (trên điện thoại thì xếp trên – dưới).
4. Bấm **Toàn màn hình** để chiếu cả video lẫn camera lên TV.
5. Bấm **📷 Tắt camera** khi xong. Camera cũng tự tắt khi đóng trang.

> Hình từ camera chỉ hiện trên màn hình đang dùng, không được ghi lại hay gửi đi đâu.
> Camera chỉ chạy khi mở trang bằng địa chỉ `github.io`, không chạy khi bấm đúp mở file trên máy.

## Chỉ dẫn động tác (Unit 5)

Khi bài hát đến đoạn có động tác, góc trên bên trái video hiện **thẻ động tác** ba thứ tiếng, ví dụ:
👏 **Clap your hands!** · Vỗ tay · 拍拍手 pāi pāi shǒu. Khi camera đang bật, hình bé cũng hiện biểu tượng động tác.

| Bài | Đoạn (giây) | Động tác |
|---|---|---|
| 1. Noodle & Pals | 12–34 | 👏 Vỗ tay |
| | 35–55 | 🦶 Dậm chân |
| | 56–75 | 😱 Kêu "Ôi không!" |
| | 76–97 | 😴 Giả vờ ngủ |
| | 98–114 | 👏 Vỗ tay |
| | 115–120 | 👋 Vẫy tay chào |
| 2. Tiếng Trung | 14–34 | 👏 拍拍手 |
| | 38–56 | 🦶 跺跺脚 |
| | 62–81 | 🙌 大声喊 |
| | 85–109 | 👏🦶🙌 一起做 (cả ba) |

- Thời điểm được đặt theo hình trong video. Nếu thấy lệch, cô sửa số giây trong `unit-5/index.html`, đoạn `const CUES = {`. Mỗi dòng có dạng `[giây bắt đầu, giây kết thúc, "động tác"]`.
- Tên các động tác dùng được: `clap`, `stomp`, `hooray`, `all3`, `ohno`, `nap`, `wave`.
- **Bảng nút động tác** dưới video: cô bấm một nút để hiện ngay động tác đó trong 5 giây (bấm lại để tắt). Dùng khi muốn nhắc thêm hoặc khi dạy không theo video.
- Tắt công tắc **Tự hiện chỉ dẫn** nếu chỉ muốn tự bấm.

## Filter biểu cảm (Unit 5, bài 3 và 4)

Ở hai bài They Are Angry, dưới video hiện dải **5 nút khuôn mặt**: 🙂 Bỏ filter · 😀 Happy · 😢 Sad · 😠 Angry · 😨 Scared (kèm tiếng Việt và 高兴 / 伤心 / 生气 / 害怕).

- Bé **bấm vào khuôn mặt đúng với lời hát** thì camera đổi filter, rồi bé làm mặt giống như vậy:
  - 😀 Vui: má hồng, sao lấp lánh, ông mặt trời
  - 😢 Buồn: đám mây mưa trên đầu, giọt nước mắt, màu xanh
  - 😠 Tức giận: hơi nước bốc từ đầu, ngọn lửa, màu đỏ
  - 😨 Sợ hãi: nền tối, ma nhỏ, tia chớp, mồ hôi
- Đến câu hát cảm xúc nào, thẻ nhắc **"Make an angry face!"** hiện lên và **nút đúng sẽ nhấp nháy** để bé tìm.
- Nếu camera chưa bật, bấm một khuôn mặt sẽ tự bật camera.
- Filter tự bám theo khuôn mặt bé (nhận diện khuôn mặt chạy ngay trên máy, không gửi hình đi đâu). Nếu máy yếu hoặc không nhận ra mặt, hiệu ứng vẫn hiện ở giữa khung camera.
- Khi có filter, ô camera tự to hơn để bé nhìn rõ mặt mình.

Thời điểm các thẻ nhắc cảm xúc (giây), sửa được trong `const CUES` như phần động tác (tên: `f-happy`, `f-sad`, `f-angry`, `f-scared`):

| Bài | Vui | Buồn | Tức giận | Sợ hãi |
|---|---|---|---|---|
| 3. Tiếng Anh | 18–27 · 62–70 | 27–34 · 70–78 | 34–41 · 78–85 | 41–50 · 85–93 |
| 4. Tiếng Trung | 8–14 · 44–52 | 14–22 · 52–60 | 22–29 · 60–68 | 29–38 · 68–82 |

> Thư mục `unit-5/lib/face/` phải được tải lên đầy đủ (8 file) thì filter mới bám theo mặt.

## Sao và lời khen

- Con **xem hết một bài** (video chạy đến cuối) thì được **1 sao**: ngôi sao lớn hiện lên kèm tiếng "ting" và một câu khen ba thứ tiếng, rồi bài tiếp theo tự chạy.
- Bấm **Tiếp** để bỏ qua bài thì **không** được sao.
- Đủ sao (6/6 ở Unit 1, 5/5 ở Unit 2, 4/4 ở Unit 3, 2/2 ở Unit 4, 4/4 ở Unit 5, 3/3 ở Unit 6, 4/4 ở Unit 7, 4/4 ở Unit 10): hiện màn hình **"Con giỏi quá! 太棒了！ Well done!"** có pháo giấy.
- Hết danh sách mà còn thiếu sao: trang báo còn bài nào chưa xong, có nút **Hát bài còn thiếu**.
- Sao được lưu trên máy/trình duyệt đang dùng. Trang chọn Unit hiện số sao của từng Unit.
- Muốn xoá sao cho lượt mới (ví dụ lớp khác dùng chung máy): bấm **Hát lại từ đầu** ở màn hình khen, hoặc dòng **Xoá sao, bắt đầu lại** dưới Playlist.

## Đưa lên GitHub Pages

**Thêm một Unit mới vào repo đã có** (ví dụ Unit 7): tải lên thư mục `unit-7` cùng `index.html` và `README.md` mới ở ngoài cùng. Không cần tải lại các Unit cũ.

**Repo đang có bản cũ** (file `index.html` và thư mục `videos/` ở ngoài cùng):

1. Giải nén file zip.
2. Trên repo, bấm **Add file → Upload files**. Kéo `index.html`, `README.md`, thư mục `unit-1` và thư mục `unit-2` vào. Bấm **Commit changes**. File `index.html` cũ sẽ được thay bằng trang chọn Unit.
3. Thư mục `videos/` cũ ở ngoài cùng không còn dùng nữa. Có thể để nguyên hoặc xoá từng file (bấm vào file → biểu tượng thùng rác).

**Repo mới:**

1. Tạo repo, chọn **Public**, tải lên như bước 2 ở trên.
2. Vào **Settings → Pages**. Ở mục *Branch* chọn `main`, thư mục `/ (root)`, bấm **Save**.
3. Đợi 1–2 phút rồi mở địa chỉ.

> GitHub cho tải tối đa 100 file mỗi lần. Gói này có khoảng 30 file nên tải một lần được.

## Thêm lời karaoke cho một bài

Các video đã có lời in sẵn ở dưới khung hình. Karaoke riêng của trang (hiện ở **phía trên** khung hình) chỉ cần khi cô muốn thêm, ví dụ nghĩa tiếng Việt.

1. Mở Unit, bấm vào bài cần soạn trong Playlist.
2. Mở mục **Soạn lời karaoke** ở dưới video.
3. Dán lời, **mỗi câu một dòng**. Muốn thêm dòng phụ thì viết sau dấu `|`:

   ```
   Câu hát | pinyin hoặc nghĩa tiếng Việt
   ```

4. Bấm **Bắt đầu canh giờ**. Mỗi khi một câu **bắt đầu được hát**, chạm nút xanh (hoặc phím **Space**). Chạm nhầm thì bấm **Lùi 1 câu**.
5. Chữ hiện lệch nhạc thì dùng **Sớm hơn / Muộn hơn 0,2 giây**.
6. Bấm **Tải trang đã có lời**, máy tải về `index.html` của Unit đó.
7. Trên repo, mở thư mục Unit (ví dụ `unit-2`), **Add file → Upload files**, tải `index.html` mới lên thay file cũ.

> Phải tải file vào **đúng thư mục Unit**, không phải ngoài cùng.

## Thêm Unit mới

1. Chép cả thư mục `unit-7` thành `unit-8`.
2. Thay video trong `unit-8/videos/` (tên không dấu, không khoảng trắng; nên dùng định dạng H.264).
3. Mở `unit-8/index.html`, sửa:
   - `const UNIT = "unit-7";` → `"unit-8"` (để sao của các Unit không lẫn vào nhau)
   - `const UNIT_LABEL = "Unit 7";` → `"Unit 8"`, và chữ `Unit 7` ở đầu trang
   - danh sách `const VIDEOS = [ ... ]` (mỗi dòng một bài, `id` = tên file không có `.mp4`)
   - danh sách trong phần `karaoke-data` (mỗi bài một dòng `"tên-file": ""`)
4. Thêm một thẻ Unit 8 trong `index.html` ở ngoài cùng (chép thẻ Unit 7 rồi sửa).

Hoặc gửi video cho Claude để làm giúp.

## Khi có lỗi

| Hiện tượng | Cách xử lý |
|---|---|
| Báo "Không mở được file videos/…" | Video chưa nằm trong thư mục `videos/` của đúng Unit, hoặc tên file khác với `id`. |
| Không được sao dù đã xem | Phải để video chạy đến hết. Bấm **Tiếp** để bỏ qua thì không tính. |
| Sao của lớp trước vẫn còn | Bấm **Xoá sao, bắt đầu lại** dưới Playlist. |
| Bật Karaoke nhưng không thấy chữ | Bài đó chưa được soạn lời, hoặc chưa tải `index.html` mới lên đúng thư mục Unit. |
| Video không tự chạy bài tiếp | Bấm **Bắt đầu** trên trang trước; trình duyệt chỉ cho tự phát sau khi có người bấm. |
| Bấm Bật camera nhưng không thấy hình | Trang chưa được phép dùng camera: bấm biểu tượng camera hoặc ổ khoá trên thanh địa chỉ → Cho phép. Nếu Zoom/Meet đang mở thì tắt đi. |
| Filter không bám theo mặt, chỉ hiện ở giữa | Kiểm tra thư mục `unit-5/lib/face/` đã có đủ 8 file. Đứng đủ sáng, mặt nhìn thẳng camera. |
| Sửa file xong trang chưa đổi | Đợi 1–2 phút rồi tải lại trang (Ctrl+F5). |
