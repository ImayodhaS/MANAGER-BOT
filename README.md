# Discord Project Manager Bot

Bot Discord sederhana untuk membantu mengelola proyek langsung dari chat
Discord.

## Fitur Utama

-   Menambahkan proyek baru
-   Melihat daftar proyek
-   Mengupdate proyek
-   Menghapus proyek
-   Menambahkan skill ke proyek

## Cara Install

1.  Clone repository: git clone
    https://github.com/username/project-bot.git cd project-bot

2.  Install dependency: pip install discord.py

3.  Konfigurasi file config.py: TOKEN = "TOKEN_DISCORD_KAMU" DATABASE =
    "database.db"

## Cara Menjalankan Bot

python main.py

## Command yang Tersedia

!start - Memulai bot
!info - Menampilkan daftar perintah
!new_project - Menambahkan proyek baru
!projects - Melihat semua proyek
!update_projects - Mengubah data proyek
!skills - Menambahkan skill ke proyek
!delete - Menghapus proyek

## Contoh Penggunaan

!new_project

Bot akan meminta: - Nama proyek
- Link proyek
- Status proyek

## Struktur Project

project/ │── main.py │── logic.py │── config.py │── database.db


## Author

Dibuat oleh Yogi
