# finance-app# Finance App (Monorepo)

Ứng dụng theo dõi tài chính gồm:
- **Backend**: Laravel (API)
- **Frontend**: Vue 3 (Vite)

## 🚀 Cách chạy local

### Backend (Laravel)
```bash
cd backend
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve
