# English Zero to B1 - Lộ trình 120 ngày với AI

> **Hệ thống học tiếng Anh thông minh** - AI nhớ mọi thứ bạn đã học, không bao giờ dạy lại từ cũ, và tự điều chỉnh theo điểm yếu của bạn.

---

## Dành cho ai?

* Người Việt **chưa biết gì** về tiếng Anh hoặc mới bắt đầu
* Muốn đạt **trình độ B1** (giao tiếp cơ bản) trong **120 ngày**
* Có thể dành **90 phút/ngày** để học
* Muốn dùng **AI (Claude)** làm gia sư riêng

## Hệ thống hoạt động thế nào?

### Vấn đề: AI hay "quên"

Mỗi lần mở chat mới, AI **mất hết ngữ cảnh** - không nhớ bạn đã học gì, dễ dạy lại từ cũ, không biết điểm yếu.

### Giải pháp: "Bộ nhớ dài hạn" bằng file

Hệ thống này dùng **5 file text** như "bộ não" cho AI. Trước mỗi buổi học, AI tự đọc các file này để biết bạn đang ở đâu. Cuối buổi, AI tự cập nhật lại.

```
Bộ nhớ AI (Memory System)

    AI đọc 5 file -> biết bạn ở đâu
    |
    Tạo bài học phù hợp (không trùng)
    |
    Cuối buổi -> ghi lại vào 5 file
    |
    Lần sau đọc lại -> nhớ hết
```

---

## Cấu trúc thư mục

```
engish-zero-to-b1/
|
|-- .claude/
|   +-- CLAUDE.md              <- AI tự đọc file này khi khởi động
|
|-- memory/                    <- BỘ NHỚ DÀI HẠN (quan trọng nhất!)
|   |-- profile.md             <- Thông tin của bạn, level, mục tiêu
|   |-- progress.md            <- Nhật ký từng ngày đã học gì
|   |-- vocabulary_bank.md     <- Tất cả từ vựng đã tích lũy
|   |-- grammar_done.md        <- Ngữ pháp đã hoàn thành + mức nắm
|   +-- weak_spots.md          <- Lỗi hay mắc để AI chú ý
|
|-- prompts/                   <- CÁC PROMPT MẪU
|   |-- resume_session.md      <- Dùng khi mở chat mới
|   |-- daily_lesson.md        <- Tạo bài học đầy đủ
|   |-- end_session.md         <- Lưu memory cuối buổi
|   |-- story_format.md        <- Tạo truyện song ngữ
|   |-- fix_mistakes.md        <- Chữa lỗi cụ thể
|   +-- shadowing.md           <- Luyện shadowing
|
|-- lessons/                   <- Bài học theo từng ngày
|   +-- day-XX/
|       +-- story.md           <- Truyện song ngữ của ngày đó
|
|-- stories/                   <- Truyện song ngữ bổ sung
|-- grammar/                   <- Ghi chú ngữ pháp chi tiết
|-- vocabulary/                <- Từ vựng theo chủ đề
|-- writing/                   <- Bài viết của học viên
|-- shadowing/                 <- Bài tập shadowing
+-- progress/                  <- Báo cáo tiến độ tổng hợp
```

---

## Lộ trình 4 giai đoạn

### Giai đoạn 1 - Ngày 1-30: Nền tảng

| Tuần | Nội dung                                                  |
| ---- | --------------------------------------------------------- |
| 1-2  | IPA (phiên âm quốc tế) - học cách đọc phát âm             |
| 2-3  | To be (am/is/are) - ghép câu đầu tiên                     |
| 3-4  | Present Simple & Continuous - nói về thói quen & hiện tại |

**Kết quả:** Đọc được IPA, nói câu đơn giản, ~150 từ vựng

### Giai đoạn 2 - Ngày 31-60: Giao tiếp cơ bản

| Tuần | Nội dung                                               |
| ---- | ------------------------------------------------------ |
| 5-6  | Past Simple - kể chuyện đã xảy ra                      |
| 7-8  | Future (will/going to) + Modal verbs (can/must/should) |

**Kết quả:** Nói về quá khứ/tương lai, giao tiếp qua lại, ~350 từ

### Giai đoạn 3 - Ngày 61-90: Nâng cao

| Tuần  | Nội dung                                    |
| ----- | ------------------------------------------- |
| 9-10  | Câu phức (because/although/if) + Đọc hiểu   |
| 11-12 | Viết luận ngắn (60-80 từ) + Present Perfect |

**Kết quả:** Đọc hiểu đoạn văn, viết email đơn giản, ~500 từ

### Giai đoạn 4 - Ngày 91-120: Thực chiến

| Tuần  | Nội dung                           |
| ----- | ---------------------------------- |
| 13-14 | Shadowing podcast ngắn + TED Talks |
| 15-17 | Nói liên tục 2-3 phút, tổng ôn tập |

**Kết quả:** Nghe hiểu podcast đơn giản, nói tự tin, ~700 từ -> **B1**

---

## Lịch học mỗi ngày (90 phút)

| Thời điểm | Thời lượng | Nội dung            | Mô tả                                |
| --------- | ---------- | ------------------- | ------------------------------------ |
| Sáng 1    | 20 phút    | IPA + Phonics       | Học 2-3 âm mới, luyện phát âm        |
| Sáng 2    | 25 phút    | Ngữ pháp + Từ vựng  | 1 điểm ngữ pháp + 5-7 từ mới         |
| Chiều     | 30 phút    | Đọc truyện song ngữ | Đọc to, luyện phát âm trong ngữ cảnh |
| Tối       | 15 phút    | Viết + Ôn tập       | Viết 3 câu + review lại bài          |

---

## Truyện song ngữ là gì?

Format đặc biệt giúp bạn **học tiếng Anh trong ngữ cảnh tự nhiên** - câu tiếng Việt xen kẽ cụm tiếng Anh **in đậm**:

> Mỗi buổi sáng (**Every morning**), Minh thức dậy lúc 6 giờ (**Minh wakes up at 6**).
> Anh ấy nhìn ra cửa sổ (**He looks out the window**) và mỉm cười (**and smiles**).
> "Hôm nay là một ngày mới" (**"Today is a new day"**), anh ấy nói (**he says**).

**Tại sao hiệu quả?**

* Không cần tra từ điển - nghĩa nằm ngay bên cạnh
* Học từ vựng trong ngữ cảnh, không phải học thuộc lòng
* Ngữ pháp xuất hiện tự nhiên trong câu chuyện
* Não bộ liên kết tiếng Việt và tiếng Anh ngay lập tức

---

## Bắt đầu nhanh

### Cách 1: Dùng Claude Code

```bash
# 1. Mở terminal trong thư mục dự án
cd engish-zero-to-b1

# 2. Gõ claude - AI tự đọc .claude/CLAUDE.md
claude

# 3. Nói với AI:
# "Bắt đầu buổi học hôm nay"
```

Claude Code **tự động đọc** file `CLAUDE.md` nên không cần copy-paste gì cả.

### Cách 2: Dùng ChatGPT / Claude web

```
Bước 1: Copy nội dung prompts/resume_session.md -> paste vào chat
         -> AI đọc memory và báo cáo bạn đang ở đâu

Bước 2: Copy nội dung prompts/daily_lesson.md -> paste vào chat
         -> AI tạo bài học đầy đủ cho hôm nay

Bước 3: Cuối buổi, copy nội dung prompts/end_session.md -> paste vào
         -> AI cập nhật tất cả file memory
```

---

## Lưu ý quan trọng

| # | Lưu ý                                                                            |
| - | -------------------------------------------------------------------------------- |
| 1 | **Backup thư mục `memory/`** định kỳ - đây là toàn bộ "bộ nhớ" của bạn           |
| 2 | **Không xóa** dữ liệu cũ trong memory - chỉ thêm (append)                        |
| 3 | Dùng với tool có thể **đọc/ghi file** (Claude Code, Cursor, VS Code + extension) |
| 4 | **Mỗi buổi dùng `end_session.md`** để AI lưu lại - nếu quên sẽ mất progress      |
| 5 | Có thể dùng **Git** để version control toàn bộ quá trình học                     |

---

## License

Dự án học cá nhân. Tự do sử dụng và chia sẻ.
