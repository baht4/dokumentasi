1. Bagaimana caranya pindah antara split (sp/vsp)?
   Jawaban : 
   - ctrl+w 
   - ctrl+w h/j/k/l
2. Cara copy paste dari browser ke vim ? 
   Jawaban : 
   - vim --version | grep clipboard (jika "-clipboard" yang muncul compile ulang https://blog.aktsbot.in/copy-paste-vim-slackware.html)
   - copy text dari luar vim kemudian tekan "+p (keterangan: "=mengakses register, +=clipboard, p=paste)
3. Cara copy text di vim ? 
   Jawaban : 
   - yy=copy in line
   - yiw=copy in word 
   - "ayy=copy ke register a (a bisa diganti dengan huruf lain untuk copy multi register)
4. Cara paste text di vim ?
   - ctrl+r <register>=untuk paste di INSERT MODE
   - p=paste diluar INSERT MODE 
