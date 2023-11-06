### Command Instruction

- CMD adalah instruksi yang digunakan ketika Docker Container berjalan.
- Tidak dijalankan ketika build
- hanya bisa 1 CMD (kalau lebih hanya menjalankan CMD yg terakhir)

#### Build

```
docker container create --name command lazlanrafar/command
docker start command
docker container logs command
```
