### Working Directory Instruction

- WORKDIR adalah instruksi untuk menentukan folder untuk menjalankan instruksi (RUN, CMD, dll)
- jika lokasi WORKDIR relative path, maka dia akan masuk ke directory dari WORKDIR sebelumnya
- WOKRDIR juga bisa digunakan sebagai path pertama saat masuk ke dalam Docker Container

#### Format

```
WORKDIR /app # artinya adalah working directory nya /app
```
