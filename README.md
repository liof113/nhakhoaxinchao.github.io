<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nha Khoa Xin Chào</title>
    <!-- Thêm Bootstrap -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body class="bg-light">

    <!-- Thanh điều hướng -->
    <nav class="navbar navbar-expand-lg navbar-light bg-white shadow-sm">
        <div class="container">
            <a class="navbar-brand fw-bold" href="#">Nha Khoa Xin Chào</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#">Trang chủ</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Dịch vụ</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Liên hệ</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Phần giới thiệu -->
    <header class="container text-center mt-5">
        <h1 class="fw-bold">Chào mừng đến với Nha Khoa Xin Chào</h1>
        <p class="lead text-muted">Dịch vụ nha khoa chuyên nghiệp - Tận tâm vì nụ cười của bạn!</p>
        <!-- Nút đặt lịch -->
        <a href="https://forms.gle/your-google-form-link" class="btn btn-primary btn-lg">Đặt lịch hẹn ngay</a>
    </header>

    <!-- Danh sách dịch vụ -->
    <section class="container mt-5">
        <h2 class="text-center">Dịch vụ của chúng tôi</h2>
        <div class="row">
            <div class="col-md-4">
                <div class="card shadow-sm">
                    <img src="https://via.placeholder.com/350x200" class="card-img-top" alt="Dịch vụ 1">
                    <div class="card-body">
                        <h5 class="card-title">Tẩy trắng răng</h5>
                        <p class="card-text">Giúp răng trắng sáng chỉ sau 1 lần điều trị.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card shadow-sm">
                    <img src="https://via.placeholder.com/350x200" class="card-img-top" alt="Dịch vụ 2">
                    <div class="card-body">
                        <h5 class="card-title">Niềng răng</h5>
                        <p class="card-text">Chỉnh nha chuyên nghiệp giúp nụ cười hoàn hảo.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card shadow-sm">
                    <img src="https://via.placeholder.com/350x200" class="card-img-top" alt="Dịch vụ 3">
                    <div class="card-body">
                        <h5 class="card-title">Cấy ghép Implant</h5>
                        <p class="card-text">Giải pháp phục hồi răng mất bền vững.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Chân trang -->
    <footer class="bg-dark text-white text-center py-3 mt-5">
        <p>© 2025 Nha Khoa Xin Chào. Mọi quyền được bảo lưu.</p>
    </footer>

    <!-- Thêm Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
