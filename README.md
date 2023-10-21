# lab-3_new

`<!DOCTYPE html>`

`<html lang="en">`

`<head>`

    `<meta charset="UTF-8">`
    
    `<meta name="viewport" content="width=device-width, initial-scale=1.0">`
   
   `<title>Document</title>`
</head>
<body>
    <ul type="none" > <!-- Ordered List  -->
        <li>Jaringan Komputer</li>
        <li>Sistem Multimedia</li>
        <li>Basis Data</li>
        <li>Sistem Operasi</li> 
        <!-- Ordered List adalah list yang terurut -->
        <!-- "a" untuk membuat daftar dengan urutan abjad alfabet kecil
         "B" untuk membuat daftar dengan urutan abjad alfabet Besar
         "I" untuk membuat daftar dengan urutan angka romawi
         "i" untuk membuat daftar dengan urusan angka romawi kecil  -->
         <!-- "square" untuk simbol persegi -->
         <!-- "disc" (default) untuk simbol lingkaran disc-->
        <!-- "none" tidak memakai simbol -->
        <!-- "circle" untuk simbol lingkaran -->
              
    </ul>

    <ol type="A" start="D">
        <!-- unordered List  -->
        <li>Pemrograman Web</li>
        <li>Sistem Informasi</li>
        <li>Rekayasa Perangkat Lunak</li>
        <!-- digunakan untuk membuat daftar dimana tiap bagiannya memiliki nomor secara terurut.
        Unordered list dibuat dengan tag <ul> dan untuk item-nya dibuat juga dengan tag <li>. -->    
    </ol>

    <dl>
        <!-- Descriptio list  -->
        <dt>Mata Kuliah</dt>
        <dd>Pemrograman Web</dd>
        <dd>Sistem Informasi</dd>
        <dd>Rekayasa Perangkat Lunak</dd>
        <!-- <dl> (description list) tag untuk memulai description list-->
        <!-- <dt> (description term) tag untuk membuat kata yang akan dideskripsikan-->
        <!-- <dd> (description description) tag untuk membuat penjelasan dari kata.  -->
    </dl>

    <!-- modul praktikum pemrograman web -->

   <ul>
        <li>makanan</li>
            <ol>
                <dt>nasi padang</dt>
                <dt>ayam bakar</dt>
            </ol>
        <li>minuman</li>
        <ol>
            <dt>Jus Mangga</dt>
            <dt>Es Teh</dt>

        </ol>

   </ul>

    <!-- membuat table -->
    <!-- " <table> </table> "membuat table  -->
    <!-- "<tr> </tr>" membuat baris -->
    <!-- "<td> </td>" kolom -->
    <!-- "colspan" untuk menggabungkan dua atau sel yang horizontal atau kolom -->
    <!-- "rowspan" untuk menggabungkan dua buah sel yang vertikal atau baris -->

    <table border="1" cellspacing="0" cellpadding="1" >
        <tr>
            <td> baris 1 kolom 1 </td>
            <td> baris 1 kolom 2 </td>
        </tr>
        <tr>
            <td> baris 2 kolom 2 </td>
            <td> baris 2 kolom 2 </td>
        </tr>
    </table>

    <body>
        next memakai rowspan dan colspan
    </body>

    <!-- next memakai rowspan dan colspan -->

    <table border="1" cellspacing="0" cellpadding="10">
        <tr>
            <td rowspan="3"> rowspan </td>
            <td colspan = "2"> colspan </td>
            
        </tr>
        <tr>
            
            <td> baris 2 kolom 2 </td>
            <td> baris 2 kolom 3 </td>
           
        </tr>
        <tr>
            
            <td> baris 3 kolom 2 </td>
            <td> baris 3 kolom 3 </td>
          
        </tr>
    </table>

    <table border="1" cellspacing="0" cellpadding="1">
        <tr>
            <td colspan="2"> baris 1 dan kolom 1 </td>
            
        </tr>

        <tr>
            <td> baris 2 kolom 1 </td>
            <td> baris 2 kolom 2 </td>
        </tr>

        <tr>
            <td> baris 3 kolom 1 </td>
            <td> baris 3 kolom 2 </td>
        </tr>

        <tr>
            <td rowspan="2"> baris 4 kolom 1 </td>
            <td> baris 4 kolom 2 </td>
        </tr>

        <tr>
            
            <td> baris 5 kolom 2 </td>
        
        </tr>

        <form 
            action="action" method="post"> 
            <!-- form -->
            <!-- <form> untuk membuat form. -->
            <!-- Atribut action untuk menentukan aksi yang akan digunakan pada saat form dikirim. -->
            <!-- Dan method adalah untuk menentukan metode yang digunakan dalam mengirimkan data -->
            <!--  GET: Data dikirimkan bersama URL. -->
            <!-- POST: Data dikirimkan terpisah dari URL. -->
        </form>

    </table>
    
    <body> 
        
        <head lang="en" dir="1tr" >
            <body>
               <div class="wrapper">
                <div class="title">
                    form login
                </div>
                <form action="#">
                    <div class="field">
                        <input type="text" required>
                        <label>masukan email</label>
                    </div>
                    <div class="field">
                        <input type="password" required>
                        <label>masukan password</label>
                    </div>
                    <div class="content">
                        <div class="chekbox">
                            <input type="checkbox" id="ingatkan saya">
                            <label for="ingatkan saya"></label>
                        </div>
                        <div class="pass link">
                            <a href="#"> lupa password?</a>
                        </div>
                    </div>
                    <div class="field">
                        <input type="submit" value="login">
                    </div>
                    <div class="sigup-link">
                        belum menjadi anggota <a href="#"> Daftar Sekarang </a>
                    </div>
                </form>
               </div> 
                
            </body>
        </head>
    </body>

    


</body>
</html>
