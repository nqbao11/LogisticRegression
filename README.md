# Logistic Regression

1. Một bài toán Regression được áp dụng vào Classification

- Regression: Đầu ra là một số thực thuộc khoảng (0,1), là xác suất để một điểm dữ liệu **x** thuộc một class *y*
- Classification: vì đầu ra là xác xuất để thuộc 1 lớp, nên được xem như là bài toán phân loại.
2. Hàm activate:
        <img src="https://bit.ly/3zBHbsH" align="center" border="0" alt="y = f( w^{T}x) " width="215" height="52" /> 
        <br>
        Nếu đặt:
        <img src="https://bit.ly/3BzZr6n" align="center" border="0" alt="s = w^Tx" width="160" height="42" />
        <br>
        Thì: 
        <img src="https://bit.ly/3gS5rzd" align="center" border="0" alt="f(s) = \frac{1}{1 + e^{-s}} \triangleq \sigma(s)" width="403" height="94" /> 
        <br>
        Gọi là **hàm signmoid** 

    
