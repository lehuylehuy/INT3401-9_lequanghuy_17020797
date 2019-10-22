# INT3401-9_lequanghuy_17020797
1: Reflex Agent
  - Trả về khoảng cách mahattan vị trí pacman sau khi thực hiện hành động tới điểm TĂ gần nhất mà pac man trước khi thực hiện hành động.
  - Bài toán trả về số lớn tốt hơn => nhân với -1.

2: Minimax
  - Sử dụng thuật toán Minimax.
  - Có 2 hàm minvalue va maxvelue dẻ tim min mã cac doi thu, đầu vào là trạng thái và độ sâu , hàm min có thêm agenidex vì nhiều hơn 1 con ma 
  - Sau khi tất cả Agent hoạt động thì depth tăng lên 1.

3: Alpha-Beta Pruning
  - Giống với minimax nhưng cắt tỉa nhánh không cần thiết , đầu vào sd thêm 2 tham số a, b -> giúp thuật toán chạy nhanh hơn.

4: Expectimax
	gần giống minimax nhưng ko sd minvalue nữa sd expextvalue , xét trung bình agentindex
  - Tất cả các con ma đều đi ngẫu nhiên => xác suất chọn 1 trong các hành động là như nhau nên hàm expectvalue trả về tổng giá trị các điểm của các trạng thái sau khi đã thực các hành động chia cho tổng số hành động.

5: Evaluation Function
  - ý tưởng dữa trên chiến thuật ưu tiên thức ăn trạng thái nào càng gần thức ăn thì càng ưu tiên 
