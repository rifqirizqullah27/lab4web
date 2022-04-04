# Tugas LAB 4 Web
## Profil
| # | Biodata |
| -------- | --- |
| *Nama* | Muhammad rifqi Rizqullah |
| *NIM* | 312010263 |
| *Kelas* | TI.20.A.2 |
| *Mata Kuliah* | Pemrograman Web |
## 1. Membuat Dokumen BOX
* Buka VS Code dan buat file HTML baru. Setelah itu buat struktur HTML 

```
    <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Box</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="div1">div1</div>
    <div class="div2">div2</div>
    <div class="div3">div3</div>
</body>
</html>

```

* Maka hasilnya akan seperti berikut.
![struktur](img/box%20element%203.png)
## 2. Membuat Layout 
* kemudian Membuat header Sederhana
<!-- Ini adalah paragraf pertama -->
```
    <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <link rel="stylesheet" href="style.css">
    <title>lab4 web</title>
</head>
<body>
    <div id="container">
        <header><h1>Layout Sederhana</h1></header>
        <nav>
            <a href="home" class="active">home</a>
            <a href="artikel">artikel</a>
            <a href="about">about</a>
            <a href="kontak">kontak</a>
        </nav>
```

* model header dan nav pemrograman web Maka hasilnya akan seperti berikut.
![internal](img/layout%201.png)

## 3. Membuat Layout Lanjutan
* selanjutnya membuat nav dan hero wrapper Html Lanjutan 
```
body {
    line-height: 1;
    font-size: 100%;
    font-family: 'Open Sans' sans-serif;
    color: #5a5a5a;
}
#container {
    width: 980px;
    margin: 0 auto;
    box-shadow: 0 0 1em #5a5a5a;
}

```
* model nav pemrograman web Maka hasilnya akan seperti berikut.
![internal](img/layout%203.png)
## 3. Membuat Layout Lanjutan
* selanjutnya membuat nav dan hero wrapper Html Lanjutan 
```
<div id="container">
        <header><h1>Layout Sederhana</h1></header>
        <nav>
            <a href="home" class="active">home</a>
            <a href="artikel">artikel</a>
            <a href="about">about</a>
            <a href="kontak">kontak</a>
        </nav>
        <section id="hero">
            <h1>Hello World</h1>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Itaque animi reiciendis nostrum doloribus cupiditate architecto soluta, atque non sint maiores sunt, quisquam fugiat at exercitationem in tempora necessitatibus velit ab.</p>
            <a href="home.html" class="btn btn-large">Selanjutnya</a>
        </section>
```
* model nav pemrograman web Maka hasilnya akan seperti berikut.
![internal](img/layout%204.png)

## 4. Membuat Layout Lanjutan
* selanjutnya membuat nav dan hero wrapper Html Lanjutan 
```
<div id="container">
        <header><h1>Layout Sederhana</h1></header>
        <nav>
            <a href="home" class="active">home</a>
            <a href="artikel">artikel</a>
            <a href="about">about</a>
            <a href="kontak">kontak</a>
        </nav>
        <section id="hero">
            <h1>Hello World</h1>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Itaque animi reiciendis nostrum doloribus cupiditate architecto soluta, atque non sint maiores sunt, quisquam fugiat at exercitationem in tempora necessitatibus velit ab.</p>
            <a href="home.html" class="btn btn-large">Selanjutnya</a>
        </section>
```
* model nav pemrograman web Maka hasilnya akan seperti berikut.
![internal](img/layout%203.png)

## 4. Membuat Layout Lanjutan
* selanjutnya membuat widget Html Lanjutan 
```
<aside id="sidebar">
                <div class="widget-box">
                    <h3 class="title">Widget Header</h3>
                    <ul>
                        <li><a href="#">Widget Link</a></li>
                        <li><a href="#">Widget Link</a></li>
                        <li><a href="#">Widget Link</a></li>
                        <li><a href="#">Widget Link</a></li>
                        <li><a href="#">Widget Link</a></li>
                    </ul>
                </div>
                <div class="widget-box">
                    <h3 class="title">Widget Text</h3>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Atque accusamus incidunt vitae alias, unde doloremque animi, fuga iusto, dolor voluptate facere. Ipsa, odio quae? Magnam, eveniet enim. Esse, sint sequi.</p>
                </div>
            </aside>
```
* model nav pemrograman web Maka hasilnya akan seperti berikut.
![internal](img/layout%206.png)

## 5. Membuat Layout Lanjutan
* selanjutnya membuat circle Html Lanjutan 
```
<img src="https://dummyimage.com/120/dbb7d25/fff.png" alt="" class="image-circle">
                            <h3>heading</h3>
                            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quibusdam mollitia fuga veritatis nesciunt quas asperiores numquam, reprehenderit doloribus officiis earum repellendus, accusantium ea officia illum sint rem blanditiis doloremque eaque.</p>
                               <a href="#" class="btn btn-default">View detail</a> 
                        </div>
                        <div class="box">
                            <img src="https://dummyimage.com/120/3e73e6/fff.png" alt="" class="image-circle">
                                <h3>heading</h3>
                                <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quibusdam mollitia fuga veritatis nesciunt quas asperiores numquam, reprehenderit doloribus officiis earum repellendus, accusantium ea officia illum sint rem blanditiis doloremque eaque.</p>
                                   <a href="#" class="btn btn-default">View detail</a> 
                            </div>
                            <div class="box">
                                <img src="https://dummyimage.com/120/71e6d4/fff.png" alt="" class="image-circle">
                                    <h3>heading</h3>
                                    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quibusdam mollitia fuga veritatis nesciunt quas asperiores numquam, reprehenderit doloribus officiis earum repellendus, accusantium ea officia illum sint rem blanditiis doloremque eaque.</p>
                                       <a href="#" class="btn btn-default">View detail</a> 
                            </div>
```
* model memakai css
```
    .box img {
    border: 0;
    vertical-align: middle;
}

.image-circle {
    border-radius: 50%;
}

.row {
    margin: 0 -10px;
    box-sizing: border-box;
    -moz-box-sizing: border-box;
    -webkit-box-sizing: border-box;
}
```
.
* model nav pemrograman web Maka hasilnya akan seperti berikut.
![internal](img/layout%207.png)
## 6. Membuat Layout Lanjutan
* selanjutnya membuat feature heading Html Lanjutan 
```
  <hr class="divider">
                    <article class="entry">
                            <h2>First Feature heading.</h2>
                            <img src="https://dummyimage.com/150/7b8a70/fff.png" alt="">
                            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Itaque, aut! Aut voluptatem hic soluta rem, facilis excepturi dignissimos repudiandae incidunt in delectus libero velit consectetur. Quo aperiam consequuntur quasi modi.</p>
                            </article>
                            <hr class="divider">
                            <article class="entry">
                            <h2>First featurete Heading </h2>
                            <img src="https://dummyimage.com/150/7b8a70/fff.png" alt="" class="right-img">                                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quia repe
                          llat voluptatum, dignissimos animi cupiditate provident ad cumque, tenetur debitis, deleniti placeat voluptates at! Eius eos dignissimos quos accusantium, quia cum.</p>
                    </article>
```
* model divider pemrograman web Maka hasilnya akan seperti berikut.
![internal](img/layout%208.png)

## 4. Hasil Layout
* maka hasil nya sebagai berikut
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <link rel="stylesheet" href="style.css">
    <title>lab4 web</title>
</head>
<body>
    <div id="container">
        <header><h1>Layout Sederhana</h1></header>
        <nav>
            <a href="home" class="active">home</a>
            <a href="artikel">artikel</a>
            <a href="about">about</a>
            <a href="kontak">kontak</a>
        </nav>
        <section id="hero">
            <h1>Hello World</h1>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Itaque animi reiciendis nostrum doloribus cupiditate architecto soluta, atque non sint maiores sunt, quisquam fugiat at exercitationem in tempora necessitatibus velit ab.</p>
            <a href="home.html" class="btn btn-large">Selanjutnya</a>
        </section>
        <section id="wrapper">
            <section id="main">
                <div class="row">
                    <div class="box">
                        <img src="https://dummyimage.com/120/dbb7d25/fff.png" alt="" class="image-circle">
                            <h3>heading</h3>
                            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quibusdam mollitia fuga veritatis nesciunt quas asperiores numquam, reprehenderit doloribus officiis earum repellendus, accusantium ea officia illum sint rem blanditiis doloremque eaque.</p>
                               <a href="#" class="btn btn-default">View detail</a> 
                        </div>
                        <div class="box">
                            <img src="https://dummyimage.com/120/3e73e6/fff.png" alt="" class="image-circle">
                                <h3>heading</h3>
                                <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quibusdam mollitia fuga veritatis nesciunt quas asperiores numquam, reprehenderit doloribus officiis earum repellendus, accusantium ea officia illum sint rem blanditiis doloremque eaque.</p>
                                   <a href="#" class="btn btn-default">View detail</a> 
                            </div>
                            <div class="box">
                                <img src="https://dummyimage.com/120/71e6d4/fff.png" alt="" class="image-circle">
                                    <h3>heading</h3>
                                    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quibusdam mollitia fuga veritatis nesciunt quas asperiores numquam, reprehenderit doloribus officiis earum repellendus, accusantium ea officia illum sint rem blanditiis doloremque eaque.</p>
                                       <a href="#" class="btn btn-default">View detail</a> 
                            </div>

                            <hr class="divider">
                            <article class="entry">
                                <h2>First Feature heading.</h2>
                                <img src="https://dummyimage.com/150/7b8a70/fff.png" alt="">
                                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Itaque, aut! Aut voluptatem hic soluta rem, facilis excepturi dignissimos repudiandae incidunt in delectus libero velit consectetur. Quo aperiam consequuntur quasi modi.</p>
                            </article>
                            <hr class="divider">
                            <article class="entry">
                                <h2>First featurete Heading </h2>
                                <img src="https://dummyimage.com/150/7b8a70/fff.png" alt="" class="right-img">
                                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quia repe
                                    llat voluptatum, dignissimos animi cupiditate provident ad cumque, tenetur debitis, deleniti placeat voluptates at! Eius eo
                                    s dignissimos quos accusantium, quia cum.</p>
                            </article>
                        </div>
            </section>
            <aside id="sidebar">
                <div class="widget-box">
                    <h3 class="title">Widget Header</h3>
                    <ul>
                        <li><a href="#">Widget Link</a></li>
                        <li><a href="#">Widget Link</a></li>
                        <li><a href="#">Widget Link</a></li>
                        <li><a href="#">Widget Link</a></li>
                        <li><a href="#">Widget Link</a></li>
                    </ul>
                </div>
                <div class="widget-box">
                    <h3 class="title">Widget Text</h3>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Atque accusamus incidunt vitae alias, unde doloremque animi, fuga iusto, dolor voluptate facere. Ipsa, odio quae? Magnam, eveniet enim. Esse, sint sequi.</p>
                </div>
            </aside>
        </section>
        <footer>&copy; 2021 Universitas Pelita Bangsa</footer>
    </div>
</body>
</html>
```
* hasil nya ini.
![internal](img/layout%208.png)













