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

## Pembagian IP 
| Subnet | Network ID        | Netmask           | Broadcast      | Range IP                       |
|--------|-------------------|-------------------|----------------|--------------------------------|
| A1     | 10.70.19.48/30   | 255.255.255.252   | 10.70.19.51    | 10.70.19.49 - 10.70.19.50     |
| A2     | 10.70.19.52/30   | 255.255.255.252   | 10.70.19.55    | 10.70.19.53 - 10.70.19.54     |
| A3     | 10.70.8.0/22     | 255.255.252.0     | 10.70.11.255   | 10.70.8.1 - 10.70.11.254      |
| A4     | 10.70.19.56/30   | 255.255.255.252   | 10.70.19.59    | 10.70.19.57 - 10.70.19.58     |
| A5     | 10.70.18.192/26  | 255.255.255.192   | 10.70.18.255   | 10.70.18.193 - 10.70.18.254   |
| A6     | 10.70.19.60/30   | 255.255.255.252   | 10.70.19.63    | 10.70.19.61 - 10.70.19.62     |
| A7     | 10.70.16.0/23    | 255.255.254.0     | 10.70.17.255   | 10.70.16.1 - 10.70.17.254     |
| A8     | 10.70.19.64/30   | 255.255.255.252   | 10.70.19.67    | 10.70.19.65 - 10.70.19.66     |
| A9     | 10.70.19.68/30   | 255.255.255.252   | 10.70.19.71    | 10.70.19.69 - 10.70.19.70     |
| A10    | 10.70.19.32/28   | 255.255.255.240   | 10.70.19.47    | 10.70.19.33 - 10.70.19.46     |
| A11    | 10.70.0.0/21     | 255.255.248.0     | 10.70.7.255    | 10.70.0.1 - 10.70.7.254       |
| A12    | 10.70.14.0/23    | 255.255.254.0     | 10.70.15.255   | 10.70.14.1 - 10.70.15.254     |
| A13    | 10.70.19.72/30   | 255.255.255.252   | 10.70.19.75    | 10.70.19.73 - 10.70.19.74     |
| A14    | 10.70.18.0/25    | 255.255.255.128   | 10.70.18.127   | 10.70.18.1 - 10.70.18.126     |
| A15    | 10.70.19.76/30   | 255.255.255.252   | 10.70.19.79    | 10.70.19.77 - 10.70.19.78     |
| A16    | 10.70.19.80/30   | 255.255.255.252   | 10.70.19.83    | 10.70.19.81 - 10.70.19.82     |
| A17    | 10.70.19.0/27    | 255.255.255.224   | 10.70.19.31    | 10.70.19.1 - 10.70.19.30      |
| A18    | 10.70.19.84/30   | 255.255.255.252   | 10.70.19.87    | 10.70.19.85 - 10.70.19.86     |
| A19    | 10.70.12.0/23    | 255.255.254.0     | 10.70.13.255   | 10.70.12.1 - 10.70.13.254     |
| A20    | 10.70.19.88/30   | 255.255.255.252   | 10.70.19.91    | 10.70.19.89 - 10.70.19.90     |
| A21    | 10.70.19.92/30   | 255.255.255.252   | 10.70.19.95    | 10.70.19.93 - 10.70.19.94     |
| A22    | 10.70.18.128/26  | 255.255.255.192   | 10.70.18.191   | 10.70.18.129 - 10.70.18.190   |

