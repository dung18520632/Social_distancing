# Social distance detection
## Input và Output:
- Input: Đầu vào 1 video.
- Output: Bounding box tương ứng cho mỗi người ( xanh  không vi phạm, đỏ vi phạm) về khoảng cách và vị trí của người trên bird-eye-view.
# Sử dụng Yolov4:
<img src="images/Yolov4.png">

# Các bước xử lý
<img src="images/Process.png">

# Chi tiết các bước
<img src="images/why.png">
Vì vậy dựa trên tọa độ 2D thì không thể tính chính xác khoảng cách. Chúng ta tiến hành chuyển về dạng top-down để tính toán lại khoảng cách trên tọa độ thực. 
<img src="images/distance_bird.png">



