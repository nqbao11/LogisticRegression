# Logistic Regression

1. Một bài toán Regression được áp dụng vào Classification

- Regression: Đầu ra là một số thực thuộc khoảng (0,1), là xác suất để một điểm dữ liệu **x** thuộc một class *y*
- Classification: vì đầu ra là xác xuất để thuộc 1 lớp, nên được xem như là bài toán phân loại.
2. Hàm activate:
        $$ y = f(w^Tx) $$  
        Nếu đặt: 
        $$ s = w^Tx $$
        Thì:
        $$ f(s) = \frac{1}{1 + e^{-s}} \triangleq \sigma(s) $$
        Gọi làm **hàm signmoid**

    