- Các bước chi tiết:
    + Tạo Droplet chạy hệ điều hành Ubuntu 22.04 LTS (hoặc bản mới nhất).
    + Lựa chọn cấu hình tối giản tiết kiệm chi phí
    + Chọn datacenter region gần Việt Nam nhất
    + Tại mục Authentication, bắt buộc chọn SSH Keys. Tạo mới một cặp khóa SSH từ máy cá nhân của bạn, thêm khóa công khai (Public Key) vào tài khoản DigitalOcean và gán vào Droplet khi khởi tạo
    + Kết nối thành công tới Droplet thông qua SSH từ máy tính cá nhân bằng tài khoản mặc định root
- Link github:

- Log kết nối thành công:

```bash
Welcome to Ubuntu 24.04 LTS (GNU/Linux 6.8.0-31-generic x86_64)

 * Documentation:  https://help.ubuntu.com
 * Management:     https://landscape.canonical.com
 * Support:        https://ubuntu.com/pro

 System information as of Sat Oct  3 15:24:14 UTC 2026

  System load:           0.0
  Usage of /:            9.5% of 18.33GB
  Memory usage:          17%
  Swap usage:            0%
  Processes:             100
  Users logged in:       1
  IPv4 address for eth0: 160.30.160.103
  IPv6 address for eth0: 2001:df4:2ec0:160:eaf5:51ff:febe:2fae

 * Canonical Workshop gives developers fast, composable, reproducible, and
   secure developer environments that are perfect for agentic workflows.

   https://ubuntu.com/workshop

Expanded Security Maintenance for Applications is not enabled.

390 updates can be applied immediately.
218 of these updates are standard security updates.
To see these additional updates run: apt list --upgradable

Enable ESM Apps to receive additional future security updates.
See https://ubuntu.com/esm or run: sudo pro status

New release '26.04.1 LTS' available.
Run 'do-release-upgrade' to upgrade to it.


Last login: Sat Oct  3 15:21:45 2026 from 183.80.151.238

```