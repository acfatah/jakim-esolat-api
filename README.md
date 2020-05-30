# Panduan API eSolat Jabatan Kemajuan Islam Malaysia (JAKIM)

> Perhatian! Pihak JAKIM boleh mengubah _api endpoint_ pada **bila-bila masa** tanpa sebarang notis. Hak cipta sepenuhnya Jabatan Kemajuan Islam Malaysia. Penggunaan API ini adalah dibawah tanggungan sendiri.

# API Endpoint

_API endpoint_ eSolat JAKIM adalah seperti berikut,

```
https://www.e-solat.gov.my/index.php?r=esolatApi/takwimsolat
```

# Query Parameters

## `zone` (wajib)

Kod kawasan adalah wajib. Format kod kawasan adalah `[A-Z]{3}0[1-9]`.

Senarai zon yang sah bagi setiap negeri adalah seperti di bawah. Untuk senarai penuh dalam format `json` boleh rujuk [sini](data/zone/groups.json).

* Johor

  * `JHR01` - Pulau Aur dan Pulau Pemanggil
  * `JHR02` - Johor Bahru, Kota Tinggi, Mersing
  * `JHR03` - Kluang, Pontian
  * `JHR04` - Batu Pahat, Muar, Segamat, Gemas Johor

* Kedah

  * `KDH01` - Kota Setar, Kubang Pasu, Pokok Sena (Daerah Kecil)
  * `KDH02` - Kuala Muda, Yan, Pendang
  * `KDH03` - Padang Terap, Sik
  * `KDH04` - Baling
  * `KDH05` - Bandar Baharu, Kulim
  * `KDH06` - Langkawi
  * `KDH07` - Puncak Gunung Jerai

* Kelantan

  * `KTN01` - Bachok, Kota Bharu, Machang, Pasir Mas, Pasir Puteh,
    Tanah Merah, Tumpat, Kuala Krai, Mukim Chiku
  * `KTN03` - Gua Musang (Daerah Galas Dan Bertam), Jeli

* Melaka

  * `MLK01` - Seluruh Negeri Melaka

* Negeri Sembilan

  * `NGS01` - Tampin, Jempol
  * `NGS02` - Jelebu, Kuala Pilah, Port Dickson, Rembau, Seremban

* Pahang

  * `PHG01` - Pulau Tioman
  * `PHG02` - Kuantan, Pekan, Rompin, Muadzam Shah
  * `PHG03` - Jerantut, Temerloh, Maran, Bera, Chenor, Jengka
  * `PHG04` - Bentong, Lipis, Raub
  * `PHG05` - Genting Sempah, Janda Baik, Bukit Tinggi
  * `PHG06` - Cameron Highlands, Genting Higlands, Bukit Fraser

* Perlis

  * `PLS01` - Kangar, Padang Besar, Arau

* Pulau Pinang

  * `PNG01` - Seluruh Negeri Pulau Pinang

* Perak

  * `PRK01` - Tapah, Slim River, Tanjung Malim
  * `PRK02` - Kuala Kangsar, Sg. Siput (Daerah Kecil), Ipoh, Batu Gajah, Kampar
  * `PRK03` - Lenggong, Pengkalan Hulu, Grik
  * `PRK04` - Temengor, Belum
  * `PRK05` - Kg Gajah, Teluk Intan, Bagan Datuk, Seri Iskandar, Beruas,
    Parit, Lumut, Sitiawan, Pulau Pangkor
  * `PRK06` - Selama, Taiping, Bagan Serai, Parit Buntar
  * `PRK07` - Bukit Larut

* Sabah

  * `SBH01` - Bahagian Sandakan (Timur), Bukit Garam, Semawang,
    Temanggong, Tambisan, Bandar Sandakan, Sukau
  * `SBH02` - Beluran, Telupid, Pinangah, Terusan, Kuamut, Bahagian Sandakan (Barat)
  * `SBH03` - Lahad Datu, Silabukan, Kunak, Sahabat, Semporna, Tungku, Bahagian Tawau (Timur)
  * `SBH04` - Bandar Tawau, Balong, Merotai, Kalabakan, Bahagian Tawau (Barat)
  * `SBH05` - Kudat, Kota Marudu, Pitas, Pulau Banggi, Bahagian Kudat
  * `SBH06` - Gunung Kinabalu
  * `SBH07` - Kota Kinabalu, Ranau, Kota Belud, Tuaran, Penampang, Papar, Putatan, Bahagian Pantai Barat
  * `SBH08` - Pensiangan, Keningau, Tambunan, Nabawan, Bahagian Pendalaman (Atas)
  * `SBH09` - Beaufort, Kuala Penyu, Sipitang, Tenom, Long Pa Sia, Membakut, Weston, Bahagian Pendalaman (Bawah)

* Selangor

  * `SGR01` - Gombak, Petaling, Sepang, Hulu Langat, Hulu Selangor, S.Alam
  * `SGR02` - Kuala Selangor, Sabak Bernam
  * `SGR03` - Klang, Kuala Langat

* Sarawak

  * `SWK01` - Limbang, Lawas, Sundar, Trusan
  * `SWK02` - Miri, Niah, Bekenu, Sibuti, Marudi
  * `SWK03` - Pandan, Belaga, Suai, Tatau, Sebauh, Bintulu
  * `SWK04` - Sibu, Mukah, Dalat, Song, Igan, Oya, Balingian, Kanowit, Kapit
  * `SWK05` - Sarikei, Matu, Julau, Rajang, Daro, Bintangor, Belawai
  * `SWK06` - Lubok Antu, Sri Aman, Roban, Debak, Kabong, Lingga, Engkelili, Betong, Spaoh, Pusa, Saratok
  * `SWK07` - Serian, Simunjan, Samarahan, Sebuyau, Meludam
  * `SWK08` - Kuching, Bau, Lundu, Sematan
  * `SWK09` - Zon Khas (Kampung Patarikan)

* Terengganu

  * `TRG01` - Kuala Terengganu, Marang, Kuala Nerus
  * `TRG02` - Besut, Setiu
  * `TRG03` - Hulu Terengganu
  * `TRG04` - Dungun, Kemaman

* Wilayah Persekutuan

  * `WLY01` - Kuala Lumpur, Putrajaya
  * `WLY02` - Labuan

## `period` (wajib)

Period adalah wajib. Nilai-nilai yang sah untuk `period` adalah,

* `today`
* `week`
* `month`
* `year`
* `duration` (`POST` request, `application/x-www-form-urlencoded`)

  Untuk menggunakan durasi, request perlu menggunakan `XMLHttpRequest` atau method `POST` dengan header `Content-Type: application/x-www-form-urlencoded` yang mengandungi data seperti berikut,

  * `datestart`

    Format nilai `datestart` adalah `YYYY-MM-DD`. Contoh: `2019-11-11`.

  * `dateend`

    Format nilai `dateend` adalah `YYYY-MM-DD`. Contoh: `2019-11-12`.

Contoh body: `datestart=2019-11-11&dateend=2019-11-12`

# Contoh Request

Request untuk `today`, `week`, `month`, dan `year` menggunakan `GET` atau `POST` method.

```
https://www.e-solat.gov.my/index.php?r=esolatApi/takwimsolat&zone=PHG03&period=today
```


Request untuk `duration`, perlu menggunakan header `Content-Type: application/x-www-form-urlencoded` untuk menghantar POST data yang mengandungi `datestart` dan `dateend`.

```
> POST /index.php?r=esolatApi/takwimsolat&zone=PHG03&period=duration HTTP/1.1
> Host: www.e-solat.gov.my
> User-Agent: curl/7.63.0
> Accept: */*
> Content-Length: 39
> Content-Type: application/x-www-form-urlencoded

| datestart=2019-11-11&dateend=2019-11-12
```

# Contoh Source Code

* Contoh request menggunakan javascript di [codepen.io](https://codepen.io/acfatah/pen/RwwByzM?editors=1010)
* Contoh request menggunakan vue di [codepen.io](https://codepen.io/acfatah/pen/rNOXMYa)

# API Response

Contoh API response untuk period `today`,

```json
{
  "prayerTime": [
    {
      "hijri": "1441-03-14",
      "date": "11-Nov-2019",
      "day": "Monday",
      "imsak": "05:26:00",
      "fajr": "05:36:00",
      "syuruk": "06:56:00",
      "dhuhr": "12:57:00",
      "asr": "16:18:00",
      "maghrib": "18:55:00",
      "isha": "20:07:00"
    }
  ],
  "status": "OK!",
  "serverTime": "2019-11-11 21:23:15",
  "periodType": "today",
  "lang": "ms_my",
  "zone": "PHG03",
  "bearing": "292&#176; 19&#8242; 16&#8243;"
}
```

Contoh API response untuk period `duration` dengan `Content-Type: application/x-www-form-urlencoded` mengandungi `datestart=2019-11-11` dan `dateend=2019-11-12`,

```json
{
  "prayerTime": [
    {
      "hijri": "1441-03-14",
      "date": "11-Nov-2019",
      "day": "Monday",
      "imsak": "05:26:00",
      "fajr": "05:36:00",
      "syuruk": "06:56:00",
      "dhuhr": "12:57:00",
      "asr": "16:18:00",
      "maghrib": "18:55:00",
      "isha": "20:07:00"
    },
    {
      "hijri": "1441-03-15",
      "date": "12-Nov-2019",
      "day": "Tuesday",
      "imsak": "05:26:00",
      "fajr": "05:36:00",
      "syuruk": "06:56:00",
      "dhuhr": "12:57:00",
      "asr": "16:18:00",
      "maghrib": "18:55:00",
      "isha": "20:07:00"
    }
  ],
  "status": "OK!",
  "serverTime": "2019-11-11 21:47:22",
  "periodType": "duration",
  "lang": "ms_my",
  "zone": "PHG03"
}

```
