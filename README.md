### Laravel sanctum
Laravel Sanctum là một gói mở rộng (package) của Laravel, được xây dựng để cung cấp tích hợp xác thực API (API authentication) và xác thực người dùng (user authentication) cho ứng dụng

Sanctum sử dụng phương pháp xác thực dựa trên token (token-based authentication) và hỗ trợ các loại xác thực như xác thực API thông qua token API và xác thực người dùng thông qua token CSRF (Cross-Site Request Forgery).

Với Sanctum, bạn có thể tạo token xác thực cho người dùng đã đăng nhập và sử dụng token đó để xác thực các yêu cầu API trong ứng dụng của mình. Sanctum cung cấp các middleware và phương thức giúp bạn xác thực token và bảo vệ các tài nguyên chỉ cho các người dùng đã xác thực.

Sanctum cũng hỗ trợ việc xác thực người dùng thông qua session. Điều này cho phép bạn xác thực người dùng thông qua session cookie và sử dụng Sanctum để bảo vệ các yêu cầu API cùng với các yêu cầu web thông thường.
## Cách cài đặt 
'composer require laravel/sanctum'
---
** Sau khi cài đặt gói, bạn cần cấu hình ứng dụng Laravel của mình để sử dụng Sanctum. Vui lòng tham khảo tài liệu chính thức của Laravel Sanctum để biết hướng dẫn chi tiết về cách cấu hình và sử dụng gói một cách hiệu quả. **
