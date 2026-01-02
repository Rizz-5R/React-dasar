Belajar React -dasar/fundamental-
KOMPONEN untuk detailnya silahkan mampir => https://id.legacy.reactjs.org/docs/components-and-props.html

Contoh studi kasus => DisplayCounter. Silahkan cek file-nya.

Memahami konsep State & Hook, mampir juga di => https://www.youtube.com/watch?v=kcnwI_5nKyA&list=PLFIM0718LjIUu3X2zYNqomEWs3sYd-fV1
Elemen pertama dalam array adalah nilai statenya => const [like, ....] = React.useState();
Elemen kedua merupakan fungsi untuk merubah nilainya => const [..., setLike] = React.useState(); Hasil => const [like, setLike] = React.useState();
Untuk elemen kedua bebas, asalkan diawali dengan set => const [gas, setGas] = React.useState();
Memberi nilai awal / default pd state-nya dengan mengisi argumen => React.useState(0);
