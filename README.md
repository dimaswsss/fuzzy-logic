# Deskripsi
Halo. Ini merupakan repositori untuk tugas praktikum *Kecerdasan Buatan*. Tugasnya, yaitu mencari artikel ilmiah, kemudian mengimplementasikan algoritma *fuzzy logic* sesuai dengan jurnal yang ada. 

# Teknologi yang digunakan
Python, dengan library Skfuzzy, Numpy, dan Matplotlib.

# Metode yang digunakan
Metode Mamdani, dengan langkah pertama yaitu menentukan himpunan fuzzy dari masing – masing variabel input dan output. Langkah yang kedua yaitu aplikasi fungsi implikasi dengan fungsi MIN. Langkah yang ketiga yaitu komposisi aturan dengan fungsi MAX. Langkah yang keempat yaitu mengubah output dari bilangan fuzzy ke bilangan tegas atau defuzzyfikasi, metode defuzzyfikasi yang digunakan adalah metode centroid.

# Contoh
## Input
```python
berat_score = 51
tinggi_score = 163
```
## Membership Function
![Gambar](1_membership%20functions.png)
## Aggregated and Result
![Gambar](2_Aggregated%20membership%20and%20result.png)
## Input
```python
print(gizi_trian)
```
akan menghasilkan output *21.587813620071678*, yang berarti normal.

# Referensi
1. [Python-Inventory-Control-Model](https://github.com/AlexandrPerun/Python-Inventory-Control-Model)
2. [Fuzzy Control Systems: The Tipping Problem](https://pythonhosted.org/scikit-fuzzy/auto_examples/plot_tipping_problem_newapi.html)
3. Modul Praktikum Kecerdasan Buatan
4. [Artikelnya](https://e-journal.potensi-utama.ac.id/ojs/index.php/INFOSYS/article/view/1744)