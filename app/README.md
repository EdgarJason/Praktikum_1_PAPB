# Profil App (Praktikum 1 PAPB)

## 1. Penjelasan singkat kode:

Kode tersebut merupakan aplikasi Android sederhana yang dibuat menggunakan Kotlin dan Jetpack Compose untuk menampilkan halaman profil mahasiswa. Pada MainActivity, fungsi onCreate() digunakan untuk menjalankan tampilan aplikasi melalui setContent(), kemudian MaterialTheme dan Surface digunakan sebagai dasar tampilan dengan latar belakang berwarna biru gelap. Fungsi ProfileScreen() mengatur isi halaman menggunakan Column yang dapat di-scroll, kemudian terdapat Card sebagai wadah informasi profil. Di dalam Card terdapat Image untuk menampilkan foto profil dari resource ic_profile, beberapa Text untuk menampilkan nama, NIM, dan jurusan, serta Spacer untuk mengatur jarak antar komponen. Selanjutnya, fungsi FollowButton() digunakan untuk membuat tombol Follow yang bersifat interaktif. Status tombol disimpan menggunakan mutableStateOf, dengan nilai awal false. Ketika tombol ditekan, nilai tersebut dibalik menggunakan !isFollowed, sehingga teks tombol berubah dari Follow menjadi Unfollow dan warna tombol juga ikut berubah.

## 2. Analisis singkat keuntungan Compose dibandingkan XML layout:

Jetpack Compose memiliki beberapa keuntungan dibandingkan XML Layout, salah satunya adalah penulisan kode yang lebih sederhana karena tampilan dan logika UI dapat dibuat langsung menggunakan Kotlin dalam satu tempat. Compose juga lebih mudah digunakan untuk membuat tampilan yang interaktif karena perubahan state dapat langsung memperbarui tampilan secara otomatis. Selain itu, Compose mengurangi kebutuhan penggunaan banyak file XML dan kode tambahan seperti findViewById, sehingga pengembangan aplikasi menjadi lebih cepat dan kode lebih mudah untuk dimanage.

