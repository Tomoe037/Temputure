# 📱 Tempature
## 🚀 Giới thiệu
Ứng dụng này được xây dựng bằng **React**, **Vite**, và **Capacitor** để phát triển ứng dụng chuyển đổi độ C sang độ F

## 📦 Công nghệ sử dụng
- **React**: Thư viện xây dựng giao diện người dùng.
- **Vite**: Công cụ build nhanh cho React.
- **Capacitor**: Cung cấp khả năng truy cập tính năng gốc trên thiết bị di động.

## 🛠 Cài đặt
1. **Clone dự án**
   ```sh
   git clone https://github.com/Tomoe037/Temputure.git
   cd your-repo
   ```

2. **Cài đặt thư viện**
   ```sh
   npm install
   ```

3. **Cài đặt Capacitor**
   ```sh
   npm install @capacitor/core @capacitor/cli
   ```

## 🔥 Chạy ứng dụng
### 1️⃣ Chạy trên trình duyệt
```sh
npm run dev

### 2️⃣ Thêm nền tảng di động
- **Android:**
  ```sh
  npx cap add android
  ```
- **iOS:**
  ```sh
  npx cap add ios
  ```

### 3️⃣ Build & chạy trên thiết bị di động
- **Build web**:
  ```sh
  npm run build
  ```
- **Sync với Capacitor**:
  ```sh
  npx cap sync
  ```
- **Mở dự án trong Android Studio/Xcode**:
  ```sh
  npx cap open android
  ```
  hoặc
  ```sh
  npx cap open ios
  ```

## 🛠 Các lệnh hữu ích
| Lệnh | Mô tả |
|------------|------------------------------------------------|
| `npm run dev` | Chạy ứng dụng trên trình duyệt |
| `npm run build` | Build dự án để triển khai |
| `npx cap sync` | Đồng bộ Capacitor với dự án |
| `npx cap open android` | Mở dự án trong Android Studio |
| `npx cap open ios` | Mở dự án trong Xcode |

