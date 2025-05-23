# Unit Test - Phân tích điểm số học sinh

## Mô tả bài tập
Cách chạy test :
- Mở dự án
- Chuột phải vào file `StudentAnalyzerTest.java` → Run 'StudentAnalyzerTest'
Bài tập yêu cầu viết chương trình Java với lớp `StudentAnalyzer` để thực hiện hai chức năng chính:

1. **Đếm số lượng học sinh đạt loại Giỏi**: Với điểm số từ 0 đến 10, học sinh được coi là Giỏi nếu có điểm >= 8.0. Bỏ qua các điểm không hợp lệ (âm hoặc > 10).
2. **Tính điểm trung bình hợp lệ**: Chỉ tính trung bình các điểm hợp lệ trong khoảng từ 0 đến 10.

Bên cạnh đó, sinh viên cần viết **test case JUnit** để kiểm thử các trường hợp như:
- Trường hợp bình thường (nhiều điểm hợp lệ và không hợp lệ),
- Trường hợp biên (danh sách trống, điểm = 0 hoặc 10),
- Trường hợp ngoại lệ (có điểm âm hoặc lớn hơn 10).

2. Mô tả hàm StudentAnalyzer
   countExcellentStudents(List<Double> scores)
   Mục đích: Đếm số học sinh đạt điểm >= 8.0.

Bỏ qua điểm không hợp lệ (âm hoặc > 10).

Nếu danh sách rỗng → trả về 0.

calculateValidAverage(List<Double> scores)
Mục đích: Tính trung bình cộng các điểm hợp lệ (0 ≤ điểm ≤ 10).

Nếu không có điểm hợp lệ → trả về 0.

