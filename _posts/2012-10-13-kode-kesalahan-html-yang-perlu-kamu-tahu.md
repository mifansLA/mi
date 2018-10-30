---
title: Daftar kode status HTTP
excerpt: 
---
Daftar kode status HTTP terdiri dari lima (5) bagian berikut:

{% include toc %}

### Kode 1xx Informasi

Permintaan didapat, melanjutkan proses. Pada kelas ini, hanya digunakan untuk status saja. kode-kode ini diantaranya:

- 100 Melanjutkan
- 101 Memilih Protokol
- 102 Memproses

## Kode 2xx Sukses

Pada kelas ini, server memberikan status suksesnya diterima, dipahami, disetujui, dan diproses. Berikut ini daftar kode tanggapan dari server tersebut:

- 200 OK
- 201 Request Berhasil dibuat
- 202 Request berhasil diterima
- 203 Non-Authoritative Information (since HTTP/1.1)
- 204 Tanpa Konten
- 205 Reset Content
- 206 Partial Content
- 207 Multi-Status (WebDAV; RFC 4918)
- 208 Already Reported (WebDAV; RFC 5842)
- 226 IM Used [RFC 3229](https://tools.ietf.org/html/rfc3229){: rel="external nofollow"}

## Kode 3xx Pengalihan

Untuk balasan tipe ini artinya ada pengalihan alamat, berikut arti kode-kode pengalihan HTML tersebut:

- 300 Multiple Choices
- 301 Dipindah Permanen
- 302 Ditemukan
- 303 Lihat Lainnya
- 304 Not Modified
- 305 Use Proxy (since HTTP/1.1)
- 306 Switch Proxy
- 307 Temporary Redirect (since HTTP/1.1)
- 308 Permanent Redirect (Experimental RFC; RFC 7238)

## Kode 4xx Kesalahan Klien

Pada kelas ini, klien memberikan status kesalahan dalam memproses permintaan. Artinya ada kesalahan dari pihak klien seperti ada persyaratan tertentu yang tidak dipenuhi oleh klien. Yang paling umum ditemukan adalah kode 404. Secara keseluruhan, berikut ini daftar arti kode kesalahan HTML tersebut:

- 400 Permintaan Tak Layak
- 401 Unauthorized
- 402 Payment Required
- 403 Terlarang
- 404 Tidak Ditemukan
- 405 Method Not Allowed
- 406 Not Acceptable
- 407 Proxy Authentication Required
- 408 Request Timeout
- 409 Conflict
- 410 Tidak tersedia
- 411 Length Required
- 412 Precondition Failed
- 413 Request Entity Too Large414 Request-URI Too Long
- 415 Unsupported Media Type
- 416 Requested Range Not Satisfiable
- 417 Expectation Failed
- 419 Authentication Timeout (not in RFC 2616)
- 420 Method Failure (Spring Framework)

## Kode 5xx Kesalahan Server

Nah, jika kode 4xx merupakan kesalahan dari klien, maka kode 5xx merupakan kesalah dari pihak server. Berikut daftar kode kesalahan HTML dari server:

- 500 Internal Server Error
- 501 Not Implemented
- 502 Bad Gateway
- 503 Service Unavailable
- 504 Gateway Timeout
- 505 HTTP Version Not Supported
- 506 Variant Also Negotiates (RFC 2295)
- 507 Insufficient Storage (WebDAV; RFC 4918)
- 508 Loop Detected (WebDAV; RFC 5842)
- 509 Bandwidth Limit Exceeded (Apache bw/limited extension)510 Not Extended (RFC 2774)
- 511 Network Authentication Required (RFC 6585)
- 520 Origin Error (CloudFlare)
- 521 Web server is down (CloudFlare)
- 522 Connection timed out (CloudFlare)
- 523 Proxy Declined Request (CloudFlare)
- 524 A timeout occurred (CloudFlare)
- 598 Network read timeout error (Unknown)
- 599 Network connect timeout error (Unknown)

Demikian tadi arti-arti dari kode-kode kesalahan HTMl yang sering muncul di web browser atau saat melakukan http request untuk halam tertentu dari sebuah website yang perlu kamu tahu.
