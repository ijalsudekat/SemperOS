# SemperOS
SemperOS is Linux OS based from Ubuntu for programming
# Langkah – Langkah Remastering OS Linux 
1.	Instalasi Aplikasi Bertema Programming
a.	Sublime Text
Untuk menginstall sublime gunakan command di bawah ini :

$ wget -qO - https://download.sublimetext.com/sublimehq-pub.gpg | sudo apt-key add -
$ echo "deb https://download.sublimetext.com/ apt/stable/" | sudo tee /etc/apt/sources.list.d/sublime-text.list
$ sudo apt-get update
$ sudo apt-get install sublime-text
 
 
b.	Visual Studio Code
Untuk menginstall Visual Studio Code siapkan file deb yang di download dari situs resmi nya.
Kemudian jalankan command di bawah ini : 

 
c.	XAMPP
Untuk menginstall XAMPP siapkan file .run yang bisa didownload di situs XAMPP. Kemudian install dengan command di bawah ini :
 


d.	MonoDevelop
Untuk menginstall MonoDevelop gunakan command di bawah ini :

$ sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys 3FA7E0328081BFF6A14DA29AA6A19B38D3D831EF
$ sudo apt install apt-transport-https
$ echo "deb https://download.mono-project.com/repo/ubuntu vs-trusty main" | sudo tee /etc/apt/sources.list.d/mono-official-vs.list
$ sudo apt update
 
 
 
 
e.	VIM
Untuk menginstall VIM bisa dengan command di bawah ini :
 
f.	ATOM
Untuk menginstall ATOM  bisa dengan command di bawah ini :
 
g.	 FileZilla
Untuk menginstall FileZilla bisa dengan command di bawah ini :
 
h.	Putty
Untuk menginstall Putty bisa dengan command di bawah ini :
 
i.	Python IDLE
Untuk menginstall Python IDLE bisa dengan command di bawah ini :
 


2.	Mengedit Tampilan OS
•	Menginstall Unity Tweak Tool
 
a.	Mengganti Tema
Install paper theme untuk Unity Tweak Tool :
$ sudo add-apt-repository ppa:snwh/pulp
$ sudo apt-get update
$ sudo apt-get install paper-gtk-theme paper-icon-theme
 
 

Kemudian ganti tema dengan paper theme yang sudah diinstall tadi
 
b.	Mengganti Nama Ubuntu menjadi Nama OS sendiri
 
 
 
Hasilnya pada panel desktop akan berubah sesuai dengan yang kita tulis tadi
 
c.	Mengganti Detail OS
 
Ganti file UbuntuLogo.png yang berada di direktori /usr/share/unity-control-center-ui dengan logo OS yang ingin di remaster
 

Hasil dari tahap di atas akan menjadi seperti berikut ini 
d.	Mengganti Detail OS di lsb-realease
 
e.	Mengganti issue.net
 
f.	Mengganti icon start
Untuk mengganti icon launcher edit gambar launcher_bfb.png yang berada di direktori /usr/share/unity/icons
 

g.	Mengganti Logo Login 
Untuk mengganti logo pada login screen edit gambar logo.png yang ada di /usr/share/unity-greeter
 
3.	Proses Remaster
Install remastersys dengan cara download file yang dibutuhkan
Kemudian install semua file deb dengan command di bawah
 
Tampilan awal Remastersys adalah seperti ini
 
•	Backup : Melakukan proses Remastering secara keseluruhan, termasuk data– data yang tersimpan di dalamnya.
•	Dist : Melakukan proses Remastering hanya pada customisasi yang berubah, misal : Theme, Icon, Aplikasi.
•	Distcdfs : Melakukan proses Remastering hanya pada perubahan File System.
•	Distiso : Melakukan proses Remastering hanya untuk membuat file ISO saja. Bukan pada file systemnya.
 
