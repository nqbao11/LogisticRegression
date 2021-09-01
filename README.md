# Logistic Regression

1. Một bài toán Regression được áp dụng vào Classification

- Regression: Đầu ra là một số thực thuộc khoảng (0,1), là xác suất để một điểm dữ liệu **x** thuộc một class *y*
- Classification: vì đầu ra là xác xuất để thuộc 1 lớp, nên được xem như là bài toán phân loại.
2. Hàm activate:
        ![equation](<img src="http://www.sciweavers.org/tex2img.php?eq=y%20%3D%20f%28%20w%5E%7BT%7Dx%29%20&bc=White&fc=Black&im=jpg&fs=12&ff=modern&edit=0" align="center" border="0" alt="y = f( w^{T}x) " width="86" height="21"/>)
        Nếu đặt: 
        $$ s = w^Tx $$
        Thì:
        $$ f(s) = \frac{1}{1 + e^{-s}} \triangleq \sigma(s) $$
        Gọi làm **hàm signmoid**

    
