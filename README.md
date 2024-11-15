# Jarkom-Modul-4-IT13-2024

## Anggota Kelompok IT 13

| Nama Lengkap          | NRP        |
| --------------------- | ---------- |
| Muhammad Dzaky Ahnaf  | 5027231039 |
| Muhammad Nafi Firdaus | 5027231045 |

## Topologi CPT 

![alt text](Topo_CPT.png)

## Topologi GNS 

![alt text](GNS_A.png)

## CIDR
### Definisi 
CIDR (Classless Inter-Domain Routing) adalah metode dalam jaringan komputer untuk mengalokasikan alamat IP dan mengatur rute IP dengan lebih efisien. Berbeda dengan sistem subnetting berbasis classful (di mana jaringan dibagi dalam kelas-kelas A, B, dan C dengan ukuran subnet yang sudah tetap), CIDR memperkenalkan fleksibilitas dengan menggunakan notasi prefix untuk menunjukkan panjang subnet mask. Hal ini memungkinkan pembagian alamat IP sesuai kebutuhan, tanpa harus bergantung pada batasan kelas.

## Pembagian Subnet 

![alt text](CIDR_A.png)

## Tabel Routing 
| Nama Subnet          | Rute       | Jumlah IP       | Netmask      | 
| -- | ---------- | ---------- | ---------- |
| A1  | Hololive -> HoloID | 2 | /30 | 
| A2 | Hololive -> HoloID -> AREA-15 | 2 | /30 | 
| A3  |Hololive -> HoloID -> AREA-15 -> Switch6 -> Moona -> Switch6 -> Risu -> Switch -> Lofi | 661 | /22 | 
| A4 | Hololive -> HoloID -> holoro | 2 | /30 | 
| A5  | Hololive -> HoloID -> holoro -> Switch7 -> Ollie -> Switch7 -> Anya -> Switch7 -> Reine | 34 | /26 | 
| A6 | Hololive -> HoloID -> holoh3ro | 2 | /30 | 
| A7  | Hololive -> HoloID -> holoh3ro -> Switch8 -> Zeta -> Switch8 -> Kaela -> Switch8 -> Kobo | 29 | /33 | 
| A8 | Hololive -> HoloJP | 2 | /30 | 
| A9  |Hololive -> HoloJP -> Switch1 -> DEV_IS -> Switch1 -> GEN:0 | 3 | /29 | 
| A10 |Hololive -> HoloJP -> Switch1 -> DEV_IS -> Re:Gloss -> Ririka_Raden -> Re:Gloss -> Ao -> Re:Gloss-> Hajime_Kanade | 14 | /28 | 
| A11  | Hololive -> HoloJP -> Switch1 -> GEN:0 -> Switch3 -> MiComet -> Switch3 -> Sora_Robo_AZK -> Switch3 -> GEN:1 | 2045 | /21 | 
| A12 | Hololive -> HoloJP -> Switch1 -> GEN:0 -> Switch3 -> GEN:1 -> Member -> FBK_Matsuri -> Member -> Aki_Hachama | 470 | /23 | 
| A13  | Hololive -> HoloJP -> Switch1 -> GEN:0 -> Switch3 -> GEN:1 -> GAMERS | 2 | /30 | 
| A14 | Hololive > HoloJP > Switch1 > GEN:0 > Switch3 > GEN:1 > GAMERS > Fubuki > Korone -> Fubuki -> Okayu -> Fubuki -> Mio | 120 | /25 | 
| A15  | Hololive -> HoloEN | 2 | /30 | 
| A16 | Hololive -> HoloEN -> HoloAdvent | 2 | /30 | 
| A17  | Hololive > HoloEN > HoloAdvent > Switch0 > FuwaMoco -> Switch0 -> Shiori_Nerissa -> Switch0 -> Biboo | 28 | /27 | 
| A18 | Hololive -> HoloEN -> Holo-Myth | 2 | /30 | 
| A19  | Hololive -> HoloEN -> Holo-Myth -> Switch2 -> Gura_Ame_Ina -> Switch2 -> Kiara_Calli | 509 | /23 | 
| A20 | Hololive -> HoloEN -> Holo-Myth -> HoloPromise -> Project-Hope -> HoloPromise -> Holo_Council | 3 | /29 | 
| A21  | Hololive -> HoloEN -> Holo-Myth -> HoloPromise -> Project-Hope -> Irys | 3 | /29 | 
| A22 | Hololive -> HoloEN -> Holo-Myth -> HoloPromise -> Holo-Council -> Switch4 -> Kronii_Mumei -> Switch4 -> Bae_Fauna | 62 | /26 | 
| Total |  | 4263 | /19 | 
