# .☘︎ ݁˖ Fruit Shopping-Chart 🍎🍌🍊🍇🥝

> Dhita Olivia Ramadhayanti Kusuma

> 2409116040

> Kelas A'2024

> Mata Kuliah Pemrograman Aplikasi Bergerak

## 𔓘 Struktur Folder 
```
lib/
 ├── models/
 │    ├── product.dart
 │    ├── cart_item.dart
 │    └── cart_model.dart
 │
 ├── pages/
 │    ├── product_list_page.dart
 │    ├── cart_page.dart
 │    └── checkout_page.dart
 │
 └── main.dart
```

## 𔓘 Penjelasan 

Aplikasi Shopping Cart bertema buah yang dibuat menggunakan Flutter dan menerapkan materi state management dengan Provider. Project ini dibuat untuk memenuhi tugas mata kuliah **Pemrograman Aplikasi Bergerak** dengan ketentuan fitur wajib dan bonus.

### ᯓ➤ Halaman Utama 

Gambar dibawah ini merupakan halaman utam dari Fruit Shopping-Cart

<img width="1306" height="997" alt="image" src="https://github.com/user-attachments/assets/efe01081-b659-4926-b37c-1d8c87164df7" />

### ᯓ➤ Add to Chart from Product List

Gambar tersebut menampilkan halaman Product List pada aplikasi Fruit Shop. Halaman ini merupakan implementasi dari poin tugas **Add to cart from product list**, yaitu menambahkan produk ke dalam keranjang langsung dari daftar produk.

<img width="1295" height="989" alt="image" src="https://github.com/user-attachments/assets/f7459cd4-5db3-4649-be8b-88b08c99eb07" />

### ᯓ➤ Show Cart Items with Quantity

Pada halaman Cart Page, semua produk yang telah ditambahkan akan ditampilkan dalam bentuk daftar (ListView).

<img width="1305" height="993" alt="image" src="https://github.com/user-attachments/assets/95d72183-024f-4d04-9649-8e0981324ba2" />

### ᯓ➤ Update Quantity (-/+)

Di setiap item cart terdapat tombol:

➖ untuk mengurangi quantity

➕ untuk menambah quantity

<img width="1305" height="993" alt="image" src="https://github.com/user-attachments/assets/f7ce35d2-0073-4412-8452-a412ffe0d92f" />

### ᯓ➤ Remove Items from Chart

Setiap item pada halaman cart memiliki tombol delete (ikon tempat sampah).

<img width="1301" height="988" alt="image" src="https://github.com/user-attachments/assets/8e4b943e-b29e-432c-a702-8c7d4d8c2d36" />

### ᯓ➤ Display Total Price Correctly

Pada bagian bawah halaman cart terdapat Total Price Bar. Total diperoleh dari penjumlahan seluruh subtotal item dalam cart. Perhitungan dilakukan secara otomatis setiap kali quantity berubah atau item dihapus.

<img width="1301" height="988" alt="Screenshot 2026-02-26 033513" src="https://github.com/user-attachments/assets/5859b484-ed94-4da3-bef5-16c3982084ec" />

### ᯓ➤ Search Product by Name 

Pada halaman Product List terdapat Search Bar. Fitur ini memungkinkan pengguna mencari produk berdasarkan nama buah.

<img width="1298" height="991" alt="image" src="https://github.com/user-attachments/assets/41e06543-9090-4bd0-93cf-8e2b1c427b07" />

### ᯓ➤ Filter Product by Category

Terdapat Dropdown kategori dengan opsi, ketika kategori dipilih:
- Produk difilter berdasarkan kategori.
- Hanya produk sesuai kategori yang ditampilkan.

Jika memilih “All”, maka semua produk ditampilkan kembali.

<img width="1306" height="997" alt="image" src="https://github.com/user-attachments/assets/be95b24d-823e-4652-b5d6-bc91c448a517" />

### ᯓ➤ Checkout Page

Pada halaman Cart terdapat tombol Checkout yang mengarahkan ke halaman Checkout Page. Pada halaman Checkout:
- Ditampilkan ringkasan pesanan (order summary).
- Ditampilkan total harga dan total item.
- Terdapat form sederhana untuk mengisi data (misalnya nama dan alamat).
- Tombol Confirm akan:
  - Mengosongkan cart
  - Menampilkan notifikasi sukses

Fitur ini menunjukkan alur lengkap dari pemilihan produk hingga konfirmasi pesanan.

<img width="1305" height="993" alt="Screenshot 2026-02-26 030735" src="https://github.com/user-attachments/assets/062e3148-621d-46fd-adff-d1e7bc242e46" />

<img width="1305" height="571" alt="image" src="https://github.com/user-attachments/assets/c9a57122-0f59-4fda-892a-5d506448eee0" />

<img width="1308" height="997" alt="image" src="https://github.com/user-attachments/assets/2ea6cef5-4e73-4bc6-9bc9-18d312a737f6" />


