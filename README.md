# lab5web

# Nama : Taufik Eka Albani
# Nim  : 312210347
# Kelas: TI.22.A3

1. Buat file baru dengan nama lab5_javasscript.html dan masukan coding berikut
```py
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Mengenal JavaScript</title>
</head>
<body>
    <h1>Pengenalan JavaScript</h1>
    <h3>Contoh document.write dan console.log</h3>
    <script>
        document.write("Hello World");
        console.log("Hello World");
    </script>
</body>
</html>
```
outputnya

![Screenshot 2023-10-29 182654](https://github.com/taufikalbani13/Lab1web/assets/115517181/b9a5c4ab-25c2-4658-85b8-f0b7a48f85f0)

2. Pemakaian Alert sebagai property window
```py
<html>
    <head>
        <title>alert box</title>
    </head>
    <body>
        <script language = "java script">
            <!--
            window.alert("ini merupakan pesan untuk anda");
            //-->
        </script>
    </body>
</html>
```
outputnya

![Screenshot 2023-10-30 003007](https://github.com/taufikalbani13/Lab1web/assets/115517181/664efd29-a6cd-4b47-81b2-ae2f353a99c1)

3. Pemakaian method dalam objek
```py
<html>
    <head>
        <title>skrip javascript</title>
    </head>
    <body>
        percobaan pemakaian javascript
        <script language = "javascript">
            <!--
            document.write("selamat mencoba java<br>");
            document.write("semoga sukses!")
            -->
        </script>
    </body>
</html>
```
outputnya

![Screenshot 2023-10-29 184327](https://github.com/taufikalbani13/Lab1web/assets/115517181/0c06296b-f1e2-4e83-b4af-80dc07df2bb0)

4. Pemakaian prompt
```py
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>pemasukan data</title>
    </head>
    <body>
        <script language = "javascript">
            <!--
            var nama = prompt("siapa nama anda?","masukan nama anda");
            document.write("hai, " + nama);
            -->
        </script>
    </body>
</html>
```
outputnya

![Screenshot 2023-10-29 183323](https://github.com/taufikalbani13/Lab1web/assets/115517181/9219d9b1-ffe7-43d3-b5d9-1644ae78c8e3)

5. Pembuatan fungsi dan cara memanggilnya
```py
<!DOCTYPE html>
<html lang="en">
	<head>
		<title>contoh program javascript</title>
		<script language = "javascript">
			function pesan(){
			    alert ("memanggil javascript lewat body onload")
			}
		</script>
	</head>
	<body onload=pesan()>
	</body>
</html>
```
outputnya

![Screenshot 2023-10-29 184624](https://github.com/taufikalbani13/Lab1web/assets/115517181/1b3b0c56-114f-4840-bf8b-02f3bc980300)

6. Operasi dasar aritmatika
```py
<!DOCTYPE html>
<html lang="en">
	<head>
		<title>operasi dasar aritmatika</title>
		<script>
			function test (val1,val2)
			{
			    document.write("<br>"+"perkalian : val1 * val2 "+"<br>")
			    document.write(val1*val2)
			    document.write("<br>"+"pembagian : val1 / val2 "+"<br>")
			    document.write(val1/val2)
			    document.write("<br>"+"penjumlahan : val1 + val2 "+"<br>")
			    document.write(val1+val2)
			    document.write("<br>"+"pengurangan : val1 - val2 "+"<br>")
			    document.write(val1-val2)
			    document.write("<br>"+"modulus : val1 % val2 "+"<br>")
			    document.write(val1%val2)
			}
		</script>
	</head>
	<body>
		<input type="button" name="button1" value="arithmetic" onclick=test(9,4)>
	</body>
</html>
```
outputnya

![Screenshot 2023-10-29 183704](https://github.com/taufikalbani13/Lab1web/assets/115517181/ab33f92a-dafd-4630-8f3b-9acfb2229445)

7. Seleksi Kondisi if-else
```py
<!DOCTYPE html>
<html lang="en">
	<head>
		<title>contoh if else</title>
	</head>
	<body>
		<script language = "javascript">
			<!--
			var nilai = prompt("nilai (0-100): ",0);
			var hasil = "";
			if (nilai >= 60)
			hasil = "lulus";
			else
			hasil = "tidak lulus";
			document.write("hasil: " + hasil);    
			//-->
		</script>
	</body>
</html>
```
outputnya

![Screenshot 2023-10-29 183523](https://github.com/taufikalbani13/Lab1web/assets/115517181/8c812b06-b18b-4f77-be88-ef762a1867c1)![Screenshot 2023-10-29 183523](https://github.com/taufikalbani13/Lab1web/assets/115517181/8c812b06-b18b-4f77-be88-ef762a1867c1)

8. Penggunaan Operator switch untuk seleksi kondisi
```py
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Mengenal JavaScript</title>
</head>
<body>
    <h1>Pengenalan JavaScript</h1>
    <h3>Contoh document.write dan console.log</h3>
    <script>
        document.write("Hello World");
        console.log("Hello World");
    </script>
</body>
</html>
```
outputnya

![Screenshot 2023-10-29 184231](https://github.com/taufikalbani13/Lab1web/assets/115517181/4a45f768-e783-4e7c-bfe9-f2c13acc3ba5)

9. Form Input
```py
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Mengenal JavaScript</title>
</head>
<body>
    <h1>Pengenalan JavaScript</h1>
    <h3>Contoh document.write dan console.log</h3>
    <script>
        document.write("Hello World");
        console.log("Hello World");
    </script>
</body>
</html>
```
outputnya

![Screenshot 2023-10-29 183913](https://github.com/taufikalbani13/Lab1web/assets/115517181/6e3f687b-0424-4bfb-a2e3-47895bb94c91)

10. Form Button
```py
<!DOCTYPE html>
<html lang="en">
	<head>
		<title>contoh if else</title>
	</head>
	<body>
		<script language = "javascript">
			<!--
			var nilai = prompt("nilai (0-100): ",0);
			var hasil = "";
			if (nilai >= 60)
			hasil = "lulus";
			else
			hasil = "tidak lulus";
			document.write("hasil: " + hasil);    
			//-->
		</script>
	</body>
</html>
```
outputnya

![Screenshot 2023-10-29 183624](https://github.com/taufikalbani13/Lab1web/assets/115517181/c0b9fdf4-4d77-4247-ae1d-538c29746a8f)

11. Pilihan menggunakan checkbox dengan perhitungan otomatis
```py
<!DOCTYPE html>
<html lang="en">
	<head>
		<title>Daftar Menu</title>
		<script language = "javascript">
			function hitung(ele) {
			    var total = document.getElementById('total').value;
			    total = (total ? parseInt(total) : 0);
			    var harga = 0;
			
			if (ele.checked) {
			    harga = ele.value;
			    total += parseInt(harga);
			} else {
			    harga = ele.value;
			    if (total > 0)
			    total -= parseInt(harga);
			}
			document.getElementById('total').value = total;
			}
		</script>
	</head>
	<body>
		<h1>Daftar Menu Makanan</h1>
		<label><input type="checkbox" value="5000" id="menu1" onclick="hitung(this);"> Ayam Goreng Rp. 5.000</label><br />
		<label><input type="checkbox" value="500" id="menu2" onclick="hitung(this);"> Tempe Goreng Rp. 500</label><br />
		<label><input type="checkbox" value="2500" id="menu3" onclick="hitung(this);"> Telur Dadar Rp. 2.500</label><br />
		<strong>Total Bayar: Rp. <input id="total" type="text"></strong>       
	</body>
</html>
```
outputnya

![Screenshot 2023-10-29 184029](https://github.com/taufikalbani13/Lab1web/assets/115517181/5376f95a-dd99-4625-8d5c-50546222f05d)

# Pertanyaan dan Tugas
1. Buat script untuk melakukan validasi pada isian form
```py
<!DOCTYPE html>
<html>
	<head>
		<title>Form Validasi JavaScript</title>
        <script type="text/javascript">
            function validasi() {
                var nama = document.getElementById("nama").value;
                var email = document.getElementById("email").value;
                var alamat = document.getElementById("alamat").value;
                if (nama != "" && email!="" && alamat !="") {
                    return true;
                }else{
                    alert('isi form pendaftaran dengan lengkap!');
                }
            }
        </script>
	</head>
	<body>
        <h1>Form Pendaftaran</h1>
			<form action="#" method="POST" onSubmit="validasi()">
				<div>
					<label>Nama Lengkap:</label>
					<input type="text" name="nama" id="nama" />
				</div>
				<div>
					<label>Email:</label>
					<input type="email" name="email" id="email" />
				</div>
				<div>
					<label>Alamat:</label>
					<textarea cols="40" rows="5" name="alamat" id="alamat"></textarea>
				</div>
				<div>
					<input type="submit" value="Daftar" class="tombol">
				</div>
			</form>
	</body>
</html>
```
outputnya

![Screenshot 2023-10-29 183624](https://github.com/taufikalbani13/Lab1web/assets/115517181/20b6f0ba-394e-43b9-9418-eb49fc29bdb5)
     
