#ayuk main game !
print("Halo teman-teman, yuk kita main game singkat buatan Ian Hendrawan ehehe.")
print("Pertama-tama, isi nama dulu yuk !")
nama_karakter = input("Nama anda adalah : ")
print("Baik, saya mengerti. Jadi nama anda adalah " + nama_karakter + " ya ?")
pertanyaan_nama_karakter = input ("Apakah anda sudah yakin dengan nama anda ? : A) Ya. B) Tidak. [A/B] : ")
if pertanyaan_nama_karakter == "A":
    print("Bukan ! Nama anda yang sebenarnya adalah Yusuf, kan !?")
if pertanyaan_nama_karakter == "B":
    print("Ah, masa ? Jadi buat apa anda isi nama ? ehehehe.")
def skill_karakter(fskill):
    for x in fskill:
        print(x)

cinta = ["Attack +5", "Defense -1", "Speed +7", "Health +50"]
senyum = ["Attack +7", "Defense -7", "Speed +10", "Health +30"]
bijak = ["Attack +2", "Defense 0", "Speed +3", "Health +100"]

skill = input ("Becanda ya, bro atau sis ! Oke, sekarang lanjut ke bagian berikutnya. Kalau misalkan bisa milih di antara dua skill berikut, maka anda mau pilih yang mana : A) Cinta B) Senyum C) Bijak [A/B/C] : ")
if skill == "A":
       skill_karakter(cinta)
       print("Selamat " + nama_karakter + " ! Anda sudah memilih skill yang tepat ! Berarti anda memang tipe suami atau istri yang loveable banget nih ya !")
       print("Karena anda sudah memilih cinta, maka sekarang bayangkan seorang musuh di depan anda yang memiliki skill \"Kepahitan\" !")
       battle = input ("Kira-kira apa yang anda akan lakukan : A) Lawan atau B) Kabur [A/B] : ")
       if battle == "A":
          print("Baik, keputusan mu sudah benar. \"Kepahitan\" adalah musuh yang sangat kuat. Satu kali serangannya bisa membunuh mu dengan mudah ! Maka itu, untuk membunuhnya, aku membutuhkan jawaban mu, " + nama_karakter + ".")
       pertanyaan_susah_satu = input ("Siapa nama sutradara favorit dari Ian Hendrawan ? : A) Guillermo Del Toro B) Christoper Nolan : ")
       if pertanyaan_susah_satu == "A":
          print("Selamat ! Anda sudah mengalahkan musuh terbesar anda !")
       if pertanyaan_susah_satu == "B":
          print("Salah ! Coba ulang dari awal dan temukan jawaban yang benar !")
       if battle == "B":
          print("Anda telah kalah sebelum berperang...selamat tinggal, pejuang !")
if skill == "B":
       skill_karakter(senyum)
       print("Selamat " + nama_karakter + " ! Anda sudah memilih skill yang tepat ! Berarti anda itu orangnya murah senyum ya aslinya ! ehehehe")
       print("Karena anda sudah memilih senyum, maka sekarang bayangkan seorang musuh di depan anda yang memiliki skill \"kesedihan\" !")
       battle_satu = input ("Kira-kira apa yang anda akan lakukan : A) Pergi ke Grand Canyon B) Mengurung Diri Seharian di Rumah : ")
       if battle_satu == "A":
          print("Baik, pilihan mu sudah sangat benar ! Kalau begitu, bersiaplah untuk menjawab pertanyaan berat musuh !")
          print("5 \n4 \n3 \n2 \n1 \nMusuh telah datang !")
       pertanyaan_susah_dua = input ("Mengapa manusia bisa merasakan kesedihan : A) Tuhan B) Dosa C) Manusia : ")
       if pertanyaan_susah_dua == "A":
          print("Jawaban mu benar, tapi kurang tepat. Jadi kamu harus ulang dari awal lagi ya.")
       if pertanyaan_susah_dua == "B":
          print("Jawaban mu ada benarnya, tapi kamu kok sotoy banget ya kesannya. Jadi kamu mending ulang dari awal lagi dan renungkan baik-baik.")
       if pertanyaan_susah_dua == "C":
          print ("Bagus ! Sanking benarnya pilihan yang kamu ambil, sampai-sampai musuh mu ga kuat dan langsung secara otomatis kembali ke neraka !")
if skill == "C":
        skill_karakter(bijak)
        print("Selamat " + nama_karakter + " ! Anda sudah memilih skill yang paling tepat ! Kalau ditanya paling tepatnya karena apa, yah mana saya tahu alasannya ! Mikir dong ! Jangan malas !")
        print("Tapi lupakan saja ! Sekarang waktunya bersiap-siap untuk melawan musuh ! \nMusuh kali ini memiliki skill 'Labil' ! Dan untungnya, Kamu hanya perlu menjawab pertanyaan dengan benar untuk bisa mengalahkannya !")
        pertanyaan_susah_tiga = input ("Mengapa rasis itu ada ? Pilihan = A) Faktor Manusia. B) Faktor Alam : ")
        if pertanyaan_susah_tiga == "A":
           print(nama_karakter + " sotoy banget nih :p")
        if pertanyaan_susah_tiga == "B":
           print(nama_karakter + " sotoy banget dan udah tahu jawabannya salah, tapi masih aja dipilih :p")
