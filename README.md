# Recommender-System-Project

Chạy lần lượt từng cell trong code
Sau khi chạy xong model NCF sẽ thu được weights của nó, tên là 'model_weights.pth'
Truyền đường dẫn của file weights vào model phần Predict ở dưới cùng, sau đó thay số 0 bằng user muốn dự đoán trong hàm Predict(0, model), hàm sẽ trả về top 5 phim được user đó rating cao nhất
