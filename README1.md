📚 Dự Án C++: Cấu Trúc Dữ Liệu và Giải ThuậtGiáo trình: Cấu trúc dữ liệu và Giải thuậtNgôn ngữ: C++17📁 Cấu Trúc Dự ÁnPlaintextCTDL_GT/
├── include/
│   └── utils.h                        # Hàm tiện ích dùng chung
│
├── Chuong1_TongQuan/
│   └── Chuong1_TongQuan.cpp           # Kiểu DL, CTDL, Big-O
│
├── Chuong2_TimKiem_SapXep/
│   ├── Chuong2_TimKiem_SapXep.cpp     # 2 tìm kiếm + các thuật toán sắp xếp cơ bản
│   └── Bt_Chuong2_TimKiem_SapXep_NganGon.cpp  # Bản rút gọn các giải thuật tìm kiếm & sắp xếp
│
├── Chuong3_DanhSachLienKet/
│   └── Chuong3_DanhSachLienKet.cpp    # DSLK đơn, Stack, Queue
│
├── Chuong4_CauTrucCay/
│   └── Chuong4_CauTrucCay.cpp         # Cây nhị phân, BST
│
├── BaiTapTongHop/
│   └── BaiTapTongHop.cpp              # 5 ứng dụng thực tế
│
├── Makefile
└── README.md
📖 Nội Dung Chương 2: Tìm Kiếm & Sắp XếpChương này tập trung vào các giải thuật nền tảng để tối ưu hóa việc truy xuất và tổ chức dữ liệu.🔍 Các giải thuật Tìm kiếmLinear Search: Duyệt tuần tự, độ phức tạp $O(n)$.Binary Search: Chia đôi mảng đã sắp xếp, độ phức tạp $O(\log n)$.📊 Các giải thuật Sắp xếpGiải thuậtĐộ phức tạpGhi chúSelection Sort$O(n^2)$Luôn tìm phần tử nhỏ nhất để hoán đổi.Insertion Sort$O(n^2)$Tốt nhất khi mảng đã gần sắp xếp ($O(n)$).Quick Sort$O(n \log n)$Chiến lược chia để trị, hiệu suất thực tế rất cao.⚙️ Biên Dịch và ChạyBiên dịch chương 2 (Bản rút gọn)Nếu bạn muốn chạy file bài tập ngắn gọn mới thêm vào:Bash# Biên dịch
g++ -std=c++17 Chuong2_TimKiem_SapXep/Bt_Chuong2_TimKiem_SapXep_NganGon.cpp -o bin/Chuong2_NganGon

# Chạy
./bin/Chuong2_NganGon
Sử dụng MakefileBashmake        # Biên dịch toàn bộ các chương
make clean  # Dọn dẹp các file thực thi
📝 Ghi Chú Kỹ ThuậtBt_Chuong2_TimKiem_SapXep_NganGon.cpp: Đây là file tối ưu, tập trung vào việc cài đặt nhanh các hàm TimTuyenTinh, TimNhiPhan, SelectionSort, InsertionSort, và QuickSort để dễ dàng ôn tập hoặc tích hợp.
