LAB_WEEK_05 - API Integration with Retrofit and Glide

Link Google Drive

Keseluruhan Project: https://drive.google.com/drive/u/5/folders/1H-iysz0l7z6x7v9wX2DYQcmlPN5riawp

Images & Screenshots: https://drive.google.com/drive/u/5/folders/1FO2x8_2ZaOWkmyJ80Ib1miQ4kHzO465Q

APK File: https://drive.google.com/drive/u/5/folders/1MSQtYJ4uCMfXRzZvabCpUgQJOXDYhRcU

Commit History

Commit No. 1 - Retrofit Setup and Fetch API JSON Response
Commit No. 2 - Parse JSON with Moshi and Display Image URL
Commit No. 3 - Load and Display Cat Image using Glide
Commit No. 4 - Display Cat Breed Information Instead of URL

Fitur Aplikasi

- API Integration dengan The Cat API untuk mendapatkan data gambar kucing secara real-time
- JSON Parsing menggunakan Moshi converter untuk parsing response API
- Image Loading dengan Glide library untuk menampilkan gambar dari URL
- Breed Information menampilkan nama breed kucing dari data API
- Error Handling untuk menangani kasus data breed yang tidak tersedia
- Clean Architecture dengan separation of concerns menggunakan interface

API yang Digunakan

- The Cat API - https://thecatapi.com/
- Endpoint: https://api.thecatapi.com/v1/images/search


Teknologi yang Digunakan

- Android Studio
- Kotlin
- Retrofit 2.9.0 - HTTP client untuk API calls
- Moshi Converter - JSON parsing library
- Glide 4.14.2 - Image loading library
- ViewBinding - Untuk mengakses view components
- Coroutines - Untuk asynchronous operations
