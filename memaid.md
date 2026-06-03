flowchart TD
    A[Sinh Vien] -->|Truy cap| B(thiết kế website hổ trợ sinh viên lựa chọn laptop theo nhu cầu sử dụng)
    B --> C[Trang Chủ]
    C -->|Tìm Kiếm | E(Tìm kiếm laptop)
    E --> F(Danh Sách Laptop)
    F --> |Two| G[Laptop Gamming]
    F --> |Three| H[Laptop Văn Phòng]
    F --> |One| I[Máy Trạm]
    I --> S[Xem Chi Tiết Laptop]
    G --> S[Xem Chi Tiết Laptop]
    H --> S[Xem Chi Tiết Laptop]
    S --> K[So Sánh Laptop]
    K --> |Kết quả| L(Gợi ý Laptop phù hợp)

    B --> U[Bootstrap Framework]
    U --> |One|P(HTML)
    U --> |Two|Q(CSS)
    U --> |Three|Z(JAVASCRIPT)
