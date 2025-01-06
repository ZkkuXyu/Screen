# Screen
Perintah screen adalah salah satu tools yang sangat penting di MobaXterm dan terminal berbasis Linux. screen digunakan untuk membuat session terminal yang dapat berjalan di background sehingga Anda tetap bisa menjalankan proses meskipun koneksi ke server terputus.

# Install screen   
    
    sudo apt update
    sudo apt install screen -y
    
# Membuat Screen   
    
    Screen -S (Name screen/Project)
    
# keluar dari screen 
    
    Klik ctrl A+D
    
# Hapus screen 
    
    screen -X -S (Nama screen/Project) quit
    
# Printah Dasar screen 
Perintah	                        Deskripsi
screen -S <nama-session>	        Membuat session screen dengan nama tertentu
screen -ls	                      Menampilkan daftar session screen yang aktif
screen -r <ID-session>	          Melanjutkan session screen yang sudah berjalan
CTRL + A + D	                    Keluar dari session screen (detach) tanpa menutupnya

# Kombinasi Shortcut screen yang Berguna
Shortcut	    Fungsi
CTRL + A + D	Detach dari session screen
CTRL + A + C	Membuat window baru di dalam screen
CTRL + A + N	Beralih ke window berikutnya
CTRL + A + P	Beralih ke window sebelumnya
CTRL + A + K	Menutup window saat ini di dalam screen
