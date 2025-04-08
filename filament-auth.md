### 1. Path/direktori class
Mas bisa sesuaikan direktori/folder dari penempatan class authenticate ini, defaultnya dari saya ada di `App\Filament\Middlewares\Authenticate::class`

![alt text](https://github.com/onecthree/notes/blob/master/img/filament-auth/11.jpg?raw=true)


### 2. Menambahkan resource yang ingin dibuat public
Secara fungsi dasar, untuk menambahkan class resource yang ingin dibuat publik; cukup tambahkan property `$allowPublicRoutes` aja mas

![alt text](https://github.com/onecthree/notes/blob/master/img/filament-auth/33.jpg?raw=true)

### 3. Menambahkan secara manual bedasarkan route/link
Bila ada page yang tidak pakai resource atau spesifik berbeda tapi masih 1 interface/router/auth dengan Filament; mas juga bisa manual tambahkan sendiri dalam daftar array; seperti contoh di bawah ini, `app/foo` `page/stock`, `about` atau bebas sesuai kebutuhan.

![alt text](https://github.com/onecthree/notes/blob/master/img/filament-auth/22.jpg?raw=true)
