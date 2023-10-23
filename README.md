# lab4web
## Membuat Box Element

![Screenshot (19)](https://github.com/muhamadabdulanas/lab4web/assets/115569493/983ce6a3-f9e7-49df-8b86-d777e29b9925)

### Mengatur clearfix element

![Screenshot (21)](https://github.com/muhamadabdulanas/lab4web/assets/115569493/25ebfc33-0c7c-49b2-a10b-3546aeaa0ff6)

## Membuat Layout Sederhana

![Screenshot (22)](https://github.com/muhamadabdulanas/lab4web/assets/115569493/74f880f0-db0d-42c2-977c-e0359f632d10)

## Membuat Navigasi

![Screenshot (24)](https://github.com/muhamadabdulanas/lab4web/assets/115569493/5f51c523-7304-4470-b4e9-26d32d0964fd)

## Membuat Hero Panel

![Screenshot (25)](https://github.com/muhamadabdulanas/lab4web/assets/115569493/e415f6d7-d356-4228-9d4e-f039be4145e7)

## Membuat Sidebar

![Screenshot (26)](https://github.com/muhamadabdulanas/lab4web/assets/115569493/ae3e5f1d-6771-4674-af8a-7425530729cf)
### Mengtaur foter
![Screenshot (27)](https://github.com/muhamadabdulanas/lab4web/assets/115569493/c15d2cb7-7d13-4833-99d8-87ee04ec6447)

#### Membuat poter

![Screenshot (30)](https://github.com/muhamadabdulanas/lab4web/assets/115569493/f06ac455-fd7a-4681-8eda-ad4051e81c3b)


## Menambahkan element lainnya pada main content

![Screenshot (28)](https://github.com/muhamadabdulanas/lab4web/assets/115569493/7a01925d-1669-4c85-b61d-f1340172e08a)

## Menambhkan content artikel

![Screenshot (29)](https://github.com/muhamadabdulanas/lab4web/assets/115569493/23276e28-2470-4b34-a1d8-1ccee1a9f8db)

## Pertanyaan dan tugas

### Tambahkan layout untuk menu about


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About</title>
</head>
<style>
*{
    padding: 0px;
    margin: 0px;
}
body{
    line-height:1;
    font-size:100%;
    font-family:'Open Sans', sans-serif;
    color:#6b6969;
}
#container {
    width: 600px;
    height: 600px;
    margin: 0 auto;
    box-shadow: 0 0 1em #cccccc;
}
#wrapper{
  margin: 0px;
}
.gambar img{
  width: 100px;
  height: 100px;
  border-radius: 50%;
  padding: 10px;
  margin: 0px auto;
  display: block;
}
.desc{
  box-shadow: 0 0 1em #cccccc;
  border-radius: 10px;
  width: 500px;
  margin: 0px auto;
  display: block;
}
.desc p{
  padding: 5px;
}
.button{
  padding: 10px;
}
.button button{
  margin: 0px auto;
  display: block;
}
button a{
  text-decoration: none;
  margin: 0px auto;
  display: block;
  padding: 10px;
}
</style>
<body>
  <div id="container">
    <section class="about">
      <h1 align="center">About Me</h1>
      <hr>
    </section>

    <section id="wrapper">
      <div class="gambar">
        <img src="gambar/saya.png" alt="me">
      </div>
      <h1 align="center">Muhamad Abdul Anas</h1><br>
      <div class="desc">
        <p>
          Saya, Muhamad Abdul Anas, merupakan salah satu mahasiswa Universitas Pelita Bangsa.
        </p>
        <p>
          Saat ini, saya sedang menempuh jenjang sarjana di bidang teknik informatika, dan kami sedang mempelajari cara membuat tata letak website.
        </p>
        <p>
          Tata letak website adalah komponen yang sangat penting dalam proses pembuatan website, terutama untuk pengembangan desain dan pengalaman pengguna.
        </p>
        <p>
          Selain itu, tata letak website juga berfungsi untuk mempermudah para pengembang web dalam proses pembuatan website secara keseluruhan
        </p>

      </div>
    </section>

    <div class="button">
      <button><a href="home.html">Back to Content</a></button>
    </div>

  </div>
</body>
</html>


#### Hasil

![Screenshot (31)](https://github.com/muhamadabdulanas/lab4web/assets/115569493/d8319b41-b2f0-4f21-bfa3-3559d605cfb1)

## Tambahkan layout untuk menu kontak


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form</title>
</head>
<style>
body{
    font-size:100%;
    font-family:'Open Sans', sans-serif;
}
.form{
    border: 2px solid #000;
    padding: 20px; 
    display: flex;
    flex-direction: column;
    max-width: 300px;
    margin: 0 auto;
    border-radius: 10px;
    background-color: aquamarine;
}
.title{
    border: 2px solid black;
    text-align: center;
    border-radius: 10px;
    display: flex;
    flex-direction: column;
    padding: 10px;
    box-shadow: 5px 10px black;
}
.title h1{
    font-size: 100%;
}
.button{
    column-gap: 10px;
    display: flex;
    margin: 0 auto;
}
</style>
<body>
   <div class="main">
        <form action="proses.php" method="post" class="form">
            <div class="title">
                <h1><b>Contact Me</b></h1>
            </div>
            <p>
                <label for="name">Nama:</label><br>
                <input type="text" id="name" name="name" placeholder="Masukkan Nama Anda">
            </p>
            <p>
                <label for="email">Email:</label><br>
                <input type="text" name="email" id="email" placeholder="Masukkan Email Anda">
            </p>
            <p>
                <label for="order">Pesan:</label><br>
                <textarea name="pesan" id="pesan" cols="30" rows="10" placeholder="Masukan Pesan Anda Disini"></textarea>
            </p>
            <div class="button">
                <p align = "center">
                    <button>
                        <a href="home.html" style="text-decoration: none;">Batal</a>
                    </button>
                <p align = "center">
                    <input type="submit" value="Kirim">
                </p>
            </div>
        </form>
   </div>
</body>
</html>

### Hasil

![Screenshot (32)](https://github.com/muhamadabdulanas/lab4web/assets/115569493/4e347852-6bd0-4e02-89ad-60381759902a)




