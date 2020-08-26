# Instalasi Git pada macOS

Git adalah _version control system_ yang berfungsi untuk mendokumenatasikan perubahan kode yang terjadi pada aplikasi yang sedang kita buat. Selain itu, Git juga berguna saat melakukan kolaborasi dalam pembangunan sebuah aplikasi, agar kita bisa lebih mudah menggabungkan kode dari komputer yang berbeda-beda secara _remote_ (dibantu dengan GitHub).

## Instalasi Git menggunakan Homebrew Pada macOS

1. Instal XCode pada dari Apple Store di link [ini](https://apps.apple.com/id/app/xcode/id497799835?mt=12). XCode memiliki _command-line tools_ yang dibutuhkan oleh Homebrew (Lewati langkah ini jika sudah melakukan instalasi XCode sebelumnya).

2. Instal Homebrew dengan menjalankan _script_ di bawah ini pada _terminal_ (Lewati langkah ini jika sudah melakukan instalasi Homebrew sebelumnya):

   ```zsh
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
   ```

   Jika sudah selesai, cek apakah Homebrew telah terinstal dengan baik menggunakan:

   ```zsh
   brew --version
   ```

3. Instal Git dengan

   ```zsh
   brew install git
   ```

4. Jika instalasi sudah selesai, Anda bisa cek apakah instalasi berhasil atau tidak dengan

   ```zsh
   git --version
   ```

   Jika instalasi berhasil, _command_ di atas akan menampilkan versi dari Git yang Anda instal.
