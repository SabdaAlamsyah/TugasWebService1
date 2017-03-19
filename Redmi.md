# TugasWebService1

<?xml version="1.0"?>
<!DOCTYPE Biodata "biodata.dtd" [                           => mendefinisikan bahwa elemen root dari dokumen ini adalah biodata
<!ELEMENT Biodata (Nama,Tanggal Lahir,Hobi)>                => mendefinisikan bahwa elemen catatan berisi empat unsur(Nama,Tgl_lahir,Hobi,Status)
<!ELEMENT Nama (#PCDATA)>                                   => mendefinisikan untuk elemen untuk menjadi tipe "# PCDATA"
<!ELEMENT Tanggal Lahir (#PCDATA)>                          => mendefinisikan untuk elemen untuk menjadi tipe "# PCDATA"
<!ELEMENT Hobi (#PCDATA)>                                   => mendefinisikan untuk elemen untuk menjadi tipe "# PCDATA"
]>                                                          => #PCDATA yaitu sebuah konten dalam element sebuah text,meskipun berbentuk angka konten itu tetap akan berubah menjadi tex  
<Biodata>
<Nama>
<Nama Depan>Sabda Alamsyah</Nama>
</Nama>
<Tanggal Lahir>
<Tanggal Lahir>Tasikmalaya 13 Desemeber 1996</Tanggal Lahir>
</Tanggal Lahir>
<Hobi>
<Hobi>Sepak Bola</Hobi>
</Hobi>
<Status>
<Status>Lajang</Lajang>
</Lajang>
</Biodata>
