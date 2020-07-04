# Melakukan-Penyesuaian-Domain-Selesai-Transfer-pada-Portal-WHMCS
Hal ini dilakukan jika layanan domain telah berhasil ditransfer ke Registrar dari CloudKilat yaitu Registrar Kilat Domain

# Penyesuaian Domain dari sisi WHMCS CloudKilat
1. Cek **Email Approved domain**

![Title](https://obiedata1.s3-id-jkt-1.kilatstorage.id/Gambar%201.png)

2. Pastikan status **WHOIS** tidak **Pending Transfer**

*$ whois paradigma.id*
*Domain ID: PANDI-DO1516026*
*Domain Name:paradigma.id*
*Created On:2019-07-19 02:32:26*
*Last Updated On:2020-06-28 05:38:10*
*Expiration Date:2021-07-19 23:59:59*
*Status:serverTransferProhibited*
*Status:clientTransferProhibited*

3. Login WHMCS CloudKilat

![Title](http://obiedata1.s3-id-jkt-1.kilatstorage.id/login%20whmcs%20CK.png)

4. Cari nama domain dengan menggunakan kolom pencarian

![Title](https://obiedata1.s3-id-jkt-1.kilatstorage.id/Pending%20Transfer.png)

5. Apabila nama domain ditemukan selanjutnya pilih nama domain yang ingin disesuikan
6. Setelah masuk profile sesuaikan domain selesai transfer dengan cara manual yaitu dengan menyesuaikan Statusnya menjadi **Active** dan Ubah **Due Date** / **Expire Date** sesuai dengan data whois 

![Title](https://obiedata1.s3-id-jkt-1.kilatstorage.id/gambar%202.png)

7. Klik Save Changes

![Title](https://obiedata1.s3-id-jkt-1.kilatstorage.id/Save%20Changes.png)

<br>
<br>
<br>

# Penyesuaian Domain dari sisi WHMCS KilatDomain
1. Ikuti langkah 1 dan 2 pada Penyesuaian Domain dari sisi WHMCS CloudKilat
2. Login WHMCS Kilat Domain

![Title](https://tes.s3-id-jkt-1.kilatstorage.id/PO%20KD/kd01.png)

3. Cari nama domain dengan menggunakan kolom pencarian

![Title](http://obiedata1.s3-id-jkt-1.kilatstorage.id/search.png)

4. Apabila nama domain ditemukan selanjutnya pilih nama domain yang ingin disesuikan
5. Setelah masuk profile domain nantinya ada dua cara dalam menyesuaikan layanan domain dan berikut langkahnya.
A. Penyesuaian domain setelah transfer dengan cara manual yaitu sesuaikan Statusnya menjadi **Active** dan Ubah **Due Date** kemudian Save Change
B. Penyesuaian domain setelah transfer dengan cara Post Proses Transfer yaitu dengan menekan tombol **Post Proses Transfer**

![Title](https://obiedata1.s3-id-jkt-1.kilatstorage.id/kb2.jpg)

6. Selesai
