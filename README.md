# antares-workshop-LoRaWAN

halo sobat antares, jadi ini merupakan repository untuk pembelajaran mengenai dashboard IOT menggunakan protokol loraWAN. disini teman-teman perlu melakukan beberapa hal ketika ingin menggunakan aplikasi ini.

## requirement
sebelum menjalankan aplikasi ini, teman-teman perlu melengkapi beberapa aplikasi berikut
1. git (optional)
2. node JS
3. VS Code (optional, bisa menggunakan IDE lain)

## guide
1. pertama teman-teman perlu clone repo ini
```bash
# script clone ketika sudah mempunyai git
git clone https://github.com/david-william19/workshop-unram-lorawan.git
```
atau teman-teman bisa langsung pilih button berwarna hijau yang bertuliskan 'Code', kemudian pilih download zip

2. ketika sudah mendownload atau clone, masuk kedalam folder 'workshop-unram-lorawan' menggunakan VS Code

3. setelah VS Code terbuka, buka terminal di VS Code (letak button terminal ada disebelah atas dan pilih 'new terminal')

4. ketik script berikut
```bash
npm install
```

5. kemudian setelah script diatas selesai, install nodemon (guna menjalankan aplikasi)
```bash
npm install --save-dev nodemon
```

6. kemudian duplicate env.example dan rename menjadi .env

7. lalu jalankan aplikasi lewat terminal dengan ketik
```bash
npm run dev
```
(aplikasi berjalan di port 4000, jadi ketik di browser localhost:4000)

## task
dalam aplikasi ini teman-teman perlu melengkapi beberapa code didalam file antaresAPI.js

1. lengkapi 3 fungi yang sudah diberikan mark (fill here) sesuai dengan materi yang disampaikan
