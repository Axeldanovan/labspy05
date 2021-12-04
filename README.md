# labspy05
# latihan
# Latihan yang pertama adalah membuat daftar kontak dengan menggunakan dictionary pada python
berikut input nya

![Screenshot_379](https://user-images.githubusercontent.com/81457697/144693117-60806629-aef0-4167-825a-7a26f9e55302.png)
![Screenshot_380](https://user-images.githubusercontent.com/81457697/144693120-34e8198a-39f4-4c0d-abf3-fb3e4298acbc.png)

Dengan penjelasan source code sebagai berikut:

-Dibawah ini adalah untuk menampung data dari dictionary

```python
daftarkontak = {"Nama":"Nomor Telepon"}
kontak = {'Ari':'081267888', 'Dina':'087677776'}
```


-Sedangkan code dibawah adalah untuk mengakses atau menampilkan kontak yang telah ditampung dalam data dictionary tersebut

```python
print("="*30)
print("   Nama     |    Nomor Telepon   ")
print("="*30)
print(" # Ari   |   ",kontak['Ari'])
print(" # Dina  |   ",kontak['Dina'])
print("="*30)
```

 # hasil output nya
 ![Screenshot_381](https://user-images.githubusercontent.com/81457697/144693222-b577f7b3-21ae-4ddb-9d3b-7d84b5802d1f.png)

-Code dibawah ini adalah untuk menampilkan salah satu dari daftar kontak yang ada, dibawah yang akan di tampilkan adalah daftar kontak Ari
```python
print("Menampilkan kontak Ari")
print("="*30)
print(" # Ari   |   ",kontak['Ari'])
print("="*30)
```

# hasil output nya
![Screenshot_1](https://user-images.githubusercontent.com/81457697/144693251-d1c7c196-2e4d-4332-8fff-47f10ae7e72e.png)

-Code dibawah ini untuk menambahkan kontak dengan nama Riko dan nomor 087654544
```python
print("Menambah kontak dengan dana Riko dan Nomor Telepon 087654544")
kontak['Riko']='087654544'
print("="*30)
print("  Riko   |   ",kontak['Riko'])
print("="*30)
```

# hasil output nya
![Screenshot_2](https://user-images.githubusercontent.com/81457697/144693317-0d92ec1b-3a60-41c2-a0d9-a4682ea8d932.png)

-Code dibawah untuk mengubah kontak Dina dengan nomor baru 0889999776
```python
print("Mengubah kontak Dina dengan nomor baru 0889999776")
kontak['Dina']='0889999776'
print("="*30)
print(" # Dina  |   ",kontak['Dina'])
print("="*30)
```

# hasil output nya
![kontak dina](https://user-images.githubusercontent.com/81457697/144693341-4da3fe97-0600-4173-b5f2-affa7695a8f2.png)

-Code dibawah untuk menampilkan semua nama yang ada dalam daftar kontak
```python
print("Menampilkan semua nama")
print("="*30)
print(kontak.keys())
print("="*30)
```

# hasil output nya
![Screenshot_3](https://user-images.githubusercontent.com/81457697/144693368-c1d1d55a-46be-49d5-abb1-713a55d44b76.png)

-Code berikut untuk menampilkan semua nomor yang ada dalam daftar kontak
```python
print("Menampilkan semua nomor")
print("="*30)
print(kontak.values())
print("="*30)
```

# hasil output nya
![menampilakan sebuah nomer](https://user-images.githubusercontent.com/81457697/144696692-04c0cb81-2248-4824-bbbe-9e34bbf551d9.png)

-Code berikut untuk menampilkan semua daftar kontak beserta nama dan nomornya
```python
print("Menampilkan daftar nama dan nomor")
print("="*30)
print(kontak.items())
print("="*30)
```

# hasil output nya
![menampilkan daftar nama dan nomor](https://user-images.githubusercontent.com/81457697/144696753-62e7842c-0641-4186-8dbe-770b626d4f75.png)

-Code dibawah untuk menghapus kontak Dina yang tersimpan dalam daftar kontak
```python
print("Hapus kontak Dina")
kontak.pop('Dina')
print("="*30)
print(kontak.items())
print("="*30)
```
# hasil output nya
![Screenshot_4](https://user-images.githubusercontent.com/81457697/144696783-4ff704f0-ad3b-45b8-88af-2c4e11146413.png)


