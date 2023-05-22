# Đồ án cuối kỳ: KHOA HỌC DỮ LIỆU ỨNG DỤNG

### Đề tài: Dự đoán kết quả học tập của học sinh dựa trên việc chơi game

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

### Hướng dẫn cách chạy code
**Cách 1:** Chạy trực tiếp trên trang Kaggle
- Bước 1: Đăng nhập tài khoản trên trang Kaggle (yêu cầu tài khoản phải được xác minh bằng số điện thoại thì mới tham gia được các cuộc thi).
- Bước 2: Nhấn "Join Competition" để tham gia vào [cuộc thi](https://www.kaggle.com/competitions/predict-student-performance-from-game-play).
- Bước 3: Mở các file notebook trực tiếp trên Kaggle theo các đường dẫn dưới đây và chọn "Copy & Edit".
  - Student Performance Prediction - R.Forest: https://www.kaggle.com/code/crawll/hcmus-student-performance-prediction-r-forest
  - Student Performance Prediction - LightGBM: https://www.kaggle.com/code/crawll/hcmus-student-performance-prediction-lightgbm
  - Student Performance Prediction - XGBoost: https://www.kaggle.com/code/crawll/hcmus-student-performance-prediction-xgboost
- Bước 4: Chạy file notebook từ đầu tới cuối như bình thường.

**Cách 2:** Chạy trên máy local đã cài đặt Jupyter Notebook
- Bước 1: Tải dữ liệu theo đường dẫn [sau](https://drive.google.com/file/d/1VwFnaXYtIeV3ZeadrcCpLyEXKhFcc-dS).
- Bước 2: Tạo thư mục "data" đặt kế bên file "19120511_19120526_19120539.ipynb"
- Bước 3: Giải nén file "predict-student-performance-from-game-play.zip" trong thư mục "data". Phân cấp cây thư mục giống như vậy là có thể chạy được.
  ├── KHDLUD-FinalProject
  │   ├── data
  │   │   ├── jo_wilder
  │   │   │   ├── *.*
  │   │   ├── jo_wilder_310
  │   │   │   ├── *.*
  │   │   ├── sample_submission.csv
  │   │   ├── test.csv
  │   │   ├── train.csv
  │   │   ├── train_labels.csv
  │   ├── .gitignore
  │   ├── 19120511_19120526_19120539.ipynb
  │   ├── hcmus-student-performance-prediction-lightgbm.ipynb
  │   ├── hcmus-student-performance-prediction-random-forest.ipynb
  │   ├── hcmus-student-performance-prediction-xgboost.ipynb
- Bước 2: Mở file "19120511_19120526_19120539.ipynb".
- Bước 3: Chạy file notebook từ đầu tới cuối như bình thường.

**Cách 3:** Chạy trên Google Colab
- Bước 1: Mở file notebook trên Google Colab theo đường dẫn [sau](https://colab.research.google.com/drive/1GvCJux1hCS4HTIIFdfS6okKh-986-JFq).
- Bước 2: Chạy file notebook từ đầu tới cuối như bình thường.

**Lưu ý:** 

*- Cách 2 chỉ khả dụng khi máy tính bạn có đủ tài nguyên RAM để chạy với tập dữ liệu có kích thước lớn và cách 3 chỉ khả dụng khi nền tảng Google Colab mà nhóm thực hiện đã được nâng cấp phiên bản Pro, do nhóm mình đã thử chạy nhưng không đủ RAM.*

*- Các kết quả chạy của cách 2 và cách 3 không biết chính xác được độ đo F1 Score trên tập test ẩn của Kaggle, chỉ thể hiện kết quả dự đoán trên tập valid.*

### Kết quả
- Hiệu suất tốt nhất của bài toán do nhóm thực hiện: **F1-Score ~ 0.672** (Mô hình XGBoost)
- Hiệu suất tốt nhất của bài toán đã được các nhóm khác hoặc tổ chức khác nghiên cứu/thực hiện: **F1-Score ~ 0.706** (được thực hiện bởi [GKOS](https://www.kaggle.com/competitions/predict-student-performance-from-game-play/leaderboard) và đạt top 1 trên bảng xếp hạng tính tới ngày 21/5/2023).

---
