Các thư viện và công nghệ cụ thể được sử dụng trong các file này bao gồm:

OpenCV (cv2): Đây là thư viện mã nguồn mở rất mạnh mẽ cho thị giác máy tính và xử lý ảnh. Nó được sử dụng rộng rãi trong tất cả các file để đọc, ghi, và thực hiện các phép biến đổi ảnh.
NumPy: Thư viện này được sử dụng để làm việc với các mảng (array), đặc biệt là các mảng đa chiều đại diện cho dữ liệu ảnh.
Matplotlib (pyplot): Dùng để hiển thị ảnh và biểu đồ (ví dụ: histogram).
SciPy (scipy.ndimage): Trong một số trường hợp, có thể SciPy được sử dụng cho các bộ lọc hoặc các tác vụ xử lý ảnh nâng cao hơn (ví dụ như bộ lọc Min/Max trong bai 4.ipynb).
Các kỹ thuật xử lý ảnh cơ bản:
Biến đổi độ sáng/tương phản: Image inverse, Gamma Correction, Log Transformation, Contrast Stretching.
Cân bằng Histogram (Histogram Equalization).
Biến đổi Fourier nhanh (Fast Fourier Transform - FFT): Dùng trong miền tần số.
Bộ lọc tần số: Butterworth Lowpass Filter, Butterworth Highpass Filter.
Các bộ lọc không gian: Median Filter, Gaussian Filter, Average Filter, Min Filter, Max Filter (để giảm nhiễu).