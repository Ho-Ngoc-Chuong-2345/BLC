(Vào Remix Ethereum -> Tạo File "Test.sol -> Copy paste Code -> Compile -> Deploy -> Đọc bên dưới tiếp)

Bước 1 (Admin - Account 1): Gọi addCandidate (đã xong).

Bước 2 (Admin - Account 1): Nhấn nút startRegistration.

Bước 3 Kéo lên trên Remix, Vào các Account khác nhau (Không tính Admin là cái đang dùng) và Nhấn Copy các Account.

Bước 4 (Admin - Account 1): Nhập mảng cử tri ["0xAb8...", "0x4B2..."] (nhớ thêm [] trước khi paste Account) vào hàm registerVoters
và nhấn transact. Lúc này log sẽ báo xanh.

Bước 5 (Admin - Account 1): Nhấn nút startVoting để chính thức cho phép bỏ phiếu.

Bước 6 (Cử tri - Đổi sang Account 2,3,4...): Nhập 0 để vote người đầu tiên, 1 để vote người tiếp theo...

Bước 7 (Admin - Quay lại Account 1): Nhấn endElection để kết thúc quá trình Vote

Bước 8 Nhấn getResults để xem kết quả.

