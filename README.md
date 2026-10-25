# bookshelf-api
RESTful API for managing bookshelf application built with Node.js and Hapi Framework.

## Menjalankan

```bash
npm install
npm run start      # server berjalan di http://localhost:9000
npm run start:dev  # mode pengembangan dengan nodemon
npm run lint       # cek gaya kode dengan ESLint
```

## Endpoint

| Method | Path               | Keterangan                                                        |
| ------ | ------------------ | ----------------------------------------------------------------- |
| POST   | `/books`           | Menambahkan buku                                                  |
| GET    | `/books`           | Menampilkan semua buku (query opsional: `name`, `reading`, `finished`) |
| GET    | `/books/{bookId}`  | Menampilkan detail buku                                           |
| PUT    | `/books/{bookId}`  | Mengubah data buku                                                |
| DELETE | `/books/{bookId}`  | Menghapus buku                                                    |
