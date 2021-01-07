# 18020287 - Nguyễn Tiến Đạt
# Reinforcement-Pacman

# Câu 1
 * Hàm tính value: với mỗi action trong mỗi state tính ra tổng điểm rồi lấy giá trị lớn nhất tương ứng với action.

 * Hàm computeQValueFromValues: tương tự hàm trên nhưng chỉ tính value của từng cặp state, action, không lấy max

 * Hàm computeActionFromValues: trả về hành động có điểm số tốt nhất

# Câu 2
 * Ta chọn hai giá trị answerDiscount = 0.9 và answerNoise = 0 vì với noise = 0 thì mới có thể dễ dàng xác đinh đồng thời agent sẽ luôn kế thúc khi có Agent mới.

# Câu 3 

# Câu 4
 * Làm giống như câu 1 nhưng trừ hàm update
 
# Câu 5
 * Với việc chọn ngẫu nhiên một action epsilon chỉ khi đánh giá được self.epsilon còn không sẽ trả về giá trị hành động của hàm computeActionFromQValues
 
# Câu 6
 * Ta chọn các giá trị : answerEpsilon = 0.1 answerLearningRate = 0.8 Vì không thể tìm được con đường tối ưu đến 99%, 50 tập là quá nhỏ nên cần thêm để tìm kiếm.
 
# Câu 7

# Câu 8
