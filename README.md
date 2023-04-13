# Đồ án cuối kỳ: KHOA HỌC DỮ LIỆU ỨNG DỤNG

| MSSV     | Họ và tên       | Github                      |
|----------|-----------------|-----------------------------|
| 19120511 | Võ Văn Hiếu     | https://github.com/vv-hieu  |
| 19120526 | Huỳnh Đức Huy   | https://github.com/KaiKush  |
| 19120539 | Vương Thế Khang | https://github.com/vt-khang |

### GVHD: Lê Ngọc Thành, Nguyễn Thị Thu Hằng

### Mục tiêu đề tài

Cuộc thi này nhằm mục đích xác định những cách giúp học sinh tham gia vào nội dung giáo dục bằng hinh thức trò chơi giáo dục, từ đó đưa ra các dự đoán hiệu suất học tập của học sinh. Trong đồ án này sử dụng trò chơi giáo dục trực tuyến [Jo Wilder](https://pbswisconsineducation.org/jowilder/play-the-game) để theo dõi quá trình học tập của học sinh từ lớp 3-5, chủ yếu về các chủ đề lịch sử. Dưới đây là một số yếu tố cốt lõi của trò chơi:
- Nhân vật: Trong trò chơi này, bạn phải tương tác với nhân vật chính (nhân vật người chơi) cùng với các nhân vật khác nhau và ghé thăm nhiều địa điểm khác nhau trên bản đồ để tìm ra manh mối, từ đó giải đáp những bí ẩn liên quan đến lịch sử Wisconsin.
- Điều khiển: Để di chuyển qua các khung cảnh khác nhau, bạn phải sử dụng chuột để click vào nơi bạn muốn di chuyển, điều này cũng tương tự đối với tương tác với các nhân vật (đọc tài liệu, di chuyển, trò chuyện, ...).
- Notebook: Đây là nơi cung cấp thông tin và lưu những phát hiện của từng manh mối bạn có được trong trò chơi.
- Thời gian: Là thời gian bạn dành cho mỗi địa điểm khác nhau tùy thuộc vào cách bạn theo dõi câu chuyện của trò chơi.

### Giới thiệu bộ dữ liệu

Bộ dữ liệu của cuộc thi là dữ liệu về chuỗi thời gian được ghi lại từ trò chơi giáo dục trực tuyến [Jo Wilder](https://pbswisconsineducation.org/jowilder/play-the-game). Trò chơi được chia thành 4 chương, sau mỗi chương người chơi sẽ được trả lời một số câu hỏi. Có tổng cộng 18 câu hỏi liên quan trực tiếp trong trò chơi. Mục tiêu của cuộc thi là sử dụng bộ dữ liệu từ những câu hỏi trên để xác định xem người chơi có trả lời đúng câu hỏi hay không, từ đó có thể đưa ra các kết luận về hiệu suất học tập của học sinh.

Các file dữ liệu này bao gồm:
- **train.csv** - tập train
- **test.csv** - tập test
- **sample_submission.csv** - định dạng file dùng để nộp trên Kaggle
- **train_labels.csv** - câu trả lời cho 18 câu hỏi của mỗi session trong tập train

Cuộc thi: [Predict Student Performance from Game Play](https://www.kaggle.com/competitions/predict-student-performance-from-game-play) \
Nhà tổ chức cuộc thi: [Field Day Lab](https://fielddaylab.wisc.edu) \
Nhà tài trợ: [The Learning Agency Lab](https://www.the-learning-agency-lab.com) \
License: OPEN SOURCE - MIT

### Ứng dụng và ý nghĩa

- Thúc đẩy nghiên cứu về các phương pháp giáo dục, dạy học, tiếp thu kiến thức, ... từ các trò chơi giáo dục.
- Hỗ trợ các nhà phát triển phần mềm trò chơi (Game Developer) để tạo ra thêm nhiều trải nghiệm học tập có hiệu quả hơn cho học sinh.
- Thấy được các lợi ích rộng rãi của các nền tảng học tập dựa trên trò chơi đến với nhiều người hơn.

---