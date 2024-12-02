# Lab6Web
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Arkosecond.id</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" />
    <script src="https://code.jquery-3.4.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js"></script>
    <style>
        body {
            padding-top: 56px;
        }
        .header, .footer {
            background-color: #f8f9fa;
            padding: 20px;
            text-align: center;
        }
        .footer {
            margin-top: 20px;
        }
        .card-img-top {
            width: 100%; 
            height: 200px; 
            object-fit: cover; 
        }
        .card-body p {
            text-align: justify;
        }
        .card {
        border: 2px solid #87ceeb; 
        border-radius: 8px;
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header class="header">
        <h1>Arkosecond</h1>
        <p>Toko Casual Terbaik Dan Berkualitas Serta Terjangkau</p>
    </header>

    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
        <a class="navbar-brand" href="#">arkosecond.id</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item active">
                    <a class="nav-link" href="#">Sekilas Toko</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Produk</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Layanan</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Tentang</a>
                </li>
            </ul>
        </div>
    </nav>

    <!-- Main Content -->
    <div class="container mt-5">
        <div class="row">
            <!-- Sidebar -->
            <div class="col-md-3 mb-4">
                <h5>Item Tersedia</h5>
                <ul class="list-group">
                    <li class="list-group-item">T-Shirt</li>
                    <li class="list-group-item">Jacket</li>
                    <li class="list-group-item">Polo</li>
                    <li class="list-group-item">Sepatu</li>
                </ul>
            </div>

            <!-- Main Content Area -->
            <div class="col-md-9">
                <div class="row">
                    <div class="col-md-3">
                        <div class="card mb-4">
                            <img src="img/baju 1.jpg" class="card-img-top" alt="baju1">
                            <div class="card-body">
                                <h5 class="card-title">T-Shirt</h5>
                                <p class="card-text">Adidas merupakan sebuah brand yang banyak dipakai di kalangan remaja hingga orang tua</p>
                                <a href="#" class="btn btn-primary">Beli Disini</a>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-3">
                        <div class="card mb-4">
                            <img src="img/jacket 1.jpg" class="card-img-top" alt="jacket1">
                            <div class="card-body">
                                <h5 class="card-title">Jacket</h5>
                                <p class="card-text">Adidas merupakan sebuah brand yang banyak dipakai di kalangan remaja hingga orang tua</p>
                                <a href="#" class="btn btn-primary">Beli Disini</a>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-3">
                        <div class="card mb-4">
                            <img src="img/polo 1.jpg" class="card-img-top" alt="polo1">
                            <div class="card-body">
                                <h5 class="card-title">Polo</h5>
                                <p class="card-text">Adidas merupakan sebuah brand yang banyak dipakai di kalangan remaja hingga orang tua</p>
                                <a href="#" class="btn btn-primary">Beli Disini</a>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-3">
                        <div class="card mb-4">
                            <img src="img/sepatu 1.jpg" class="card-img-top" alt="sepatu1">
                            <div class="card-body">
                                <h5 class="card-title">Sepatu</h5>
                                <p class="card-text">Adidas merupakan sebuah brand yang banyak dipakai di kalangan remaja hingga orang tua </p>
                                <a href="#" class="btn btn-primary">Beli Disini</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Footer -->
    <footer class="footer">
        <p>Arkosecond</p>
    </footer>
</body>
</html>

penjelasan :
# pada gambar ini menjukan sebuah web yang masih kosong dengan menggunaakan bootstrap
![Screenshot (276)](https://github.com/user-attachments/assets/e8c4567e-b639-4718-8aa2-f617fc3919dd)
![Screenshot (277)](https://github.com/user-attachments/assets/8e9287b8-c9ce-4fc4-9415-2f5d8bba57c9)
# pada bagian ini adalah menambahkan sebuah card foto menjadi 3 pada main container
<div class="col-md-3">
                        <div class="card mb-4">
                            <img src="img/sepatu 1.jpg" class="card-img-top" alt="sepatu1">
                            <div class="card-body">
                                <h5 class="card-title">Sepatu</h5>
                                <p class="card-text">Adidas merupakan sebuah brand yang banyak dipakai di kalangan remaja hingga orang tua </p>
                                <a href="#" class="btn btn-primary">Beli Disini</a>
                            </div>
                        </div>
                    </div>
![Screenshot (278)](https://github.com/user-attachments/assets/2b58725a-cc23-442e-be22-66b12a6549af)

# pada bagian ini menjukan tampilan yang sudah ada gambarnya dengan membuat folder baru pada file praktikum 6 dengan folder img lalu tambahkan foto tersebut lalu di panggil didalam source codenya
![Screenshot (279)](https://github.com/user-attachments/assets/bb343889-5c97-410e-8077-cd55b188e656)
![Screenshot (280)](https://github.com/user-attachments/assets/dac6b4bc-6290-40d1-9336-a9e11a991ee4)
![Screenshot (281)](https://github.com/user-attachments/assets/bbc51da6-7af2-4153-90fb-66894f17f451)

# bagian ini menunjukan tampilan mengatur ukuran gambar di dalam card tsb agar sama rata lebar dan tinggi nya
![Screenshot (282)](https://github.com/user-attachments/assets/98e0e125-7ed2-485e-873e-4fd8503a70fe)
![Screenshot (283)](https://github.com/user-attachments/assets/e326d691-486e-458d-80fb-5501ba23bb70)

# tampilan ini menampilkan untuk mengatur sebuah teks paragraf agar menjadi sama rata menggunakan text-align justify
![Screenshot (284)](https://github.com/user-attachments/assets/74e6c0cc-e15d-446c-b7f1-2d8326dc6bc4)
![Screenshot (286)](https://github.com/user-attachments/assets/a4f5b81f-bfa9-4ec5-859c-15b0c2d92ca7)
![Screenshot (287)](https://github.com/user-attachments/assets/fa4dcbc5-d11a-4ccb-8a71-a108b4a41dab)

# pada bagiann ini menunjukunan tampilan untuk mengatur sebuah card border agar  berwarna
![Screenshot (288)](https://github.com/user-attachments/assets/e330df4e-2a5a-46f5-a030-4e88fcc9d17e)
![Screenshot (289)](https://github.com/user-attachments/assets/a7c15c2a-d620-4f62-9636-7252983513a1)
