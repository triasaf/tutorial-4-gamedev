### Tutorial 4 - Level Design - Trias 2106633645

### Level Design
- Memberi constraint ke diri sendiri agar tidak mengubah movement dari player, jadi design level atas dasar tersebut.
- Memberi beberapa kemungkinan yang bisa dicoba player, harus trial and error
- Terdapat shortcut yang bisa diambil player jika observasi dengan baik

### Objective
- Terdapat objective berupa bintang-bintang yang tersebar pada level. 2 bintang bisa didapatkan jika melakukan observasi yang baik ketika melakukan level dengan normal. Tetapi terdapat 3 bintang yang didapatkan jika menemukan shortcut
- Diimplementasikan seperti ObjectiveArea, namun ditambahkan logic akan menghilang jika diambil, dan jumlahnya di-track secara global untuk ditampilkan di akhir

### Obstacle
- Challenge utama ingin ditekankan pada level design dan lompatan-lompatan ketat. Sehingga obstacle tidak dibuat terlalu banyak.
- Diimplementasikan dengan cara yang sama dengan ikan
