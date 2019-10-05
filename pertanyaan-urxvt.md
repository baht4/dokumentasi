1. Bagaimana caranya membersihkan layar menggunakan ctrl-l?
   Jawaban : - vim /etc/termcap 
   	     - (ganti)  vs|xterm|xterm-color|...
   	     - (dengan) vs|rxvt-unicode-256color|xterm|xterm-color|... 
   	     - (simpan, keluar dari vim. tutup dan jalankan kembali urxvt-nya)

2. Bagaimana membuat urxvt Transparan?
   Jawaban : - vim .Xresources
 	       URxvt*.transparent: true
	       URxvt*.shading: 40
	     - (simpan, keluar dari vim)
	     - xrdb .Xresources

3. Bagaimana membuat urxvt berwarna? 
   Jawaban : - vim .Xresources 
             - (gunakan http://www.terminal.sexy untuk generate warna)
	     - (copy paste ke .Xresources)

4. Bagaimana cara copy/paste di urxvt? 
   Jawaban : - ctrl+alt+c 
             - ctrl+alt+v
