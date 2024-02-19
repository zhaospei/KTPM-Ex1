# Bài tập lý thuyết
## Docker, docker-composer là gì?
`Docker` là một nền tảng phần mềm được sử dụng để tạo, quản lý và chạy các container ứng dụng. Container là một môi trường chứa ứng dụng cùng với tất cả các phụ thuộc của nó, bao gồm các thư viện và các tài nguyên hệ thống cần thiết. Điều này giúp đơn giản hóa việc đóng gói và triển khai ứng dụng mà không cần phải quan tâm đến môi trường hệ thống nơi nó sẽ chạy. Docker cung cấp một cách tiện lợi để xây dựng, chia sẻ và triển khai các ứng dụng ở mọi nơi, từ máy tính cá nhân đến môi trường đám mây.

`Docker Compose` là một công cụ bổ sung cho Docker, được sử dụng để định nghĩa và quản lý nhiều container ứng dụng trong một tệp cấu hình duy nhất. Thay vì phải quản lý từng container một cách riêng lẻ, Docker Compose cho phép bạn định nghĩa cấu hình của toàn bộ ứng dụng, bao gồm các dịch vụ, cài đặt mạng và volume, và các yêu cầu khác. Docker Compose giúp đơn giản hóa việc phát triển và triển khai ứng dụng đa-container, đặc biệt là trong môi trường phát triển cục bộ.
## Linux vs Unix vs BSD hay *nix? masOS thuộc loại nào?
`Unix` là một trong những hệ điều hành ra đời sớm nhất, được phát triển vào cuối những năm 1960 và đầu những năm 1970 tại Bell Labs. Nó là một họ hệ điều hành máy tính đa nhiệm, đa người dùng bắt nguồn từ Unix AT&T ban đầu. Các hệ thống Unix được biết đến với tính ổn định, bảo mật và khả năng mở rộng. Chúng tuân thủ các tiêu chuẩn khác nhau như POSIX (Giao diện hệ điều hành di động) và Thông số kỹ thuật UNIX đơn.

`Linux` chỉ là một Kernel, nó không phải là một hệ điều hành hoàn chỉnh được code bởi Linus Torvalds, vào năm 1991. Linux là nhân hệ điều hành giống Unix, mã nguồn mở và được phân phối theo Giấy phép Công cộng GNU (GPL). Các bản phân phối Linux (thường được gọi là distro) kết hợp nhân Linux với phần mềm khác để tạo ra hệ điều hành hoàn chỉnh. Các bản phân phối Linux phổ biến bao gồm Ubuntu, Fedora, Debian và CentOS

`BSD` (Berkeley Software Distribution): là phiên bản giáo dục của Unix được xây dựng được phân phối bởi Đại học California, Berkeley. Hệ thống BSD được biết đến với sự mạnh mẽ, tính năng bảo mật và khả năng kết nối mạng. Các biến thể BSD nổi tiếng nhất bao gồm FreeBSD, OpenBSD và NetBSD.

`*nix` là để chỉ các hệ điều hành thuộc Unix-Like, tức là có cách thức hoạt động tương tự với hệ điều hành Unix. Có 3 loại Unix-like: Genetic UNIX, Trademark UNIX và Functional UNIX.

- `MacOS` thuộc `*nix` dựa trên nền tảng BSD.
## Alpine vs Ubuntu?
Alpine Linux và Ubuntu là hai bản phân phối Linux phổ biến, mỗi bản có các tính năng độc đáo và trường hợp sử dụng mục tiêu riêng.
- `Alpine` là bản phân phối Linux nhẹ và hướng đến bảo mật, được thiết kế chủ yếu cho các môi trường bị hạn chế về tài nguyên, chẳng hạn như vùng chứa và hệ thống nhúng.
- `Ubuntu` là một trong những bản phân phối Linux được sử dụng rộng rãi nhất, được biết đến vì tính dễ sử dụng, hỗ trợ phần mềm rộng rãi và cộng đồng lớn. Ubuntu cung cấp nhiều gói phần mềm thông qua kho lưu trữ của nó và có các bản phát hành hỗ trợ dài hạn (LTS), được hỗ trợ các bản cập nhật bảo mật và sửa lỗi trong 5 năm. Nó phù hợp với nhiều trường hợp sử dụng khác nhau, bao gồm máy tính để bàn, máy chủ, triển khai đám mây và môi trường phát triển.
## VNC
`VNC`, hay Virtual Network Computing là một hệ thống chia sẻ màn hình đa nền tảng được tạo ra để điều khiển từ xa một máy tính khác thông qua kết nối mạng. Công nghệ này hoạt động bằng cách chia sẻ màn hình và gửi các dữ liệu đầu vào (như các lệnh từ bàn phím và chuột) qua mạng giữa hai máy tính. Điều này cho phép từ xa truy cập vào máy tính mục tiêu mà không cần phải ngồi trực tiếp trước nó. Có nhiều phần mềm VNC khác nhau có sẵn, bao gồm RealVNC, TightVNC, UltraVNC, và TigerVNC, giúp người dùng thiết lập và sử dụng kết nối VNC một cách dễ dàng. VNC thường được sử dụng để hỗ trợ từ xa, quản lý máy chủ từ xa, hoặc để chia sẻ màn hình giữa các máy tính trong một mạng nội bộ.
