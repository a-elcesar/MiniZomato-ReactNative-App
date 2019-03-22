# MiniZomato-ReactNative-App
A simple React Native application for finding restaurants

Sebuah aplikasi React Native pencari restaurant, yang memenuhi spesifikasi berikut:

Elemen utama aplikasi: 1 buah input teks, 1 buah button dan card untuk menampilkan hasil pencarian.

Elemen input teks digunakan oleh user untuk memasukkan nama menu makanan yang dicari, kemudian aplikasi akan menampilkan daftar restaurant yang menyediakan menu tersebut. Misal: user memasukkan kata kebab, kemudian usai menekan tombol, aplikasi akan menampilkan daftar restaurant yang memiliki menu kebab dalam bentuk card.

Aplikasi memanfaatkan API dari Zomato. API Zomato dapat diakses dengan menggunakan API key sebagai header.

A. GET Request URL = https://developers.zomato.com/api/v2.1/search?q=**_namaMenuYangDicari_**.

B. Setting Header = key/param: user-key dan value: API key.

C. Data yang diambil yakni:

1. Nama restaurant (.data.restaurants.restaurant.name)

2. Kota restaurant (.data.restaurants.restaurant.location.city)

3. Alamat restaurant (.data.restaurants.restaurant.location.address)

4. Harga menu rata-rata 2 porsi (.data.restaurants.restaurant.average_cost_for_two)

5. Gambar thumbnail (.data.restaurants.restaurant.thumb)

D. Data ditampilkan dalam bentuk card, format bebas. Data yang ditampilkan yakni:

1. Nama restaurant

2. Kota restaurant

3. Alamat restaurant

4. Harga menu rata-rata untuk 1 porsi

5. Gambar thumbnail
