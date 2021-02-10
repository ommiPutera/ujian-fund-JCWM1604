![purwadhika](https://dm2302files.storage.live.com/y4mXzhUZVMNL_p9tVgW1HqlEUJa6ppyVCfKnxxFC4x5nfuSs_-NnMTSOFdPq6MIGrxKEZW8uGWVreQ9awWZboO6NydIZpac87UZ48QL0Y40HZv-uJOAAqVADo9m_ZBZ5ThfKAaFnCabsFufrOnkmjwdWVsaFcPVmaha7sQOlW0jmQwbbEGmbVih8UC2ouXKKdRs?width=256&height=39&cropmode=none)

---
Sebelum anda mengerjakan soal ujian, pastikan anda memiliki akun **GitHub** dan ***software git*** sudah terinstall dilaptop. Anda dapat memastikan bahwa **git** sudah terinstall dilaptop anda dengan menjalankan perintah berikut ini diterminal atau ***cmd*** : ``` git --version ```. Jika muncul *versi git* maka komputer anda sudah terinstal *git*.

Soal ujian dapat anda temukan didalam repositori ini atau anda dapat melihatnya melalui :
- link : https://drive.google.com/file/d/1gpN9J19SrIpVeNIKlUpChR5pT7PrZZX6/view?usp=sharing

Sebelum mengerjakan ujian, bacalah dengan seksama aturan serta panduan dalam mengerjakan soal-soal ujian berikut ini.

## A. Terms & Conditions
- ujian akan dilaksanakan selama 3 jam 20 menit
    - 10 menit untuk *setup*
    - 3 jam mengerjakan soal
    - 10 menit *pull request*
- repositori ini akan di-***public*** 5 menit sebelum ujian dimulai dan akan kembali di-***private*** setelah 5 menit ujian selesai
- selama mengerjakan ujian, siswa wajib **men-share seluruh screen** di **zoom** (khusus untuk kelas online) sampai ujian selesai
- dilarang bekerjasama dalam mengerjakan soal ujian
- dilarang memberikan jawaban atau meminta jawaban dari teman atau pihak lain termasuk memberikan *link* repositori hasil ***forked*** selama ujian berlangsung
- jika ada pertanyaan mengenai ujian dan soal, langsung tanyakan kepada operasional selaku pengawas ujian atau *lecturer* yang mengawasi
- siswa boleh membuka *website* dan referensi lainnya selama ujian sesuai ketentuan yang berlaku
- jawaban soal akan dikumpulkan di dalam repositori ini dengan sistem ***pull request*** dan siswa wajib mengirim ***link*** dari ***forked repositoy*** (repositori hasil *fork* di GitHub anda) ke alamat email berikut ini :<br>

    to : operational_jkt@purwadhika.com <br>
    subject : FUNDAMENTAL-JCWM-1604-JKT

## B. Exam Setup
- sebelum mengerjakan soal, lakukan ***fork*** untuk repositori ini
    ![guide_1](https://dm2302files.storage.live.com/y4mPM_i6lwI5k82Ir4gCZ_iG2pyP67UhSVdVDnXxY7pavQzUXOFoRhblnD7tH4UyyvIdMs5jKUeX04maDpMg8lm2xVybajcR4oKSo13SyRlQoizTsMIaBj1oRcS1X3hOXahuJ0S9RM64NNzskC016XEiY8SVoAORMWYw9twz0MNgzgebD8G-fqIiwFdk4n8KSky?width=597&height=341&cropmode=none)

- kemudian *clone* repositori hasil *forked* ke komputer kalian dengan cara *copy link forked respository* anda
    ![guide_2](https://dm2302files.storage.live.com/y4mngi9W5v2f4ScC1evMNDI3tFsCyCX8K0iDIiSiu2oEHRKrnqWoI2CBenLO05Gy5f2hv6JAfld8WBEFvECxOnJHnwTF26ZPQxvAtK8SIql7a7epnZqko-6c0oHyiZcT3wYkwzTwSLe_urvTzbP2LPa6qDF7E_lbo7yadTwbF0YDxdtYJIohYDPvTdMAdbm0N1u?width=637&height=410&cropmode=none)

- buka terminal atau *cmd* dengan mengarah pada folder tempat anda akan menyimpan hasil *clone* dari repositori yang sudah anda *forked*, kemudian jalankan perintah ```git clone``` dan *paste link forked repository* anda

    ``` C:\data\alee> git clone http://github.com/alee/...```

- pindah ke direktori atau folder hasil ```git clone``` dengan cara

    ``` C:\data\alee> cd ujian-fund-JCWM1604 ``` 

- buatlah sebuah folder baru dengan nama : NAMA-ANDA-PROGRAM, e.x. ALEE-JCWM1602 pada direktori tersebut<br>
    ![guide_3](https://dm2302files.storage.live.com/y4m49ID-GiHSE5XEg-XDwRQulMNbf7KgpyWNhQJzz5mo1bEwOha4Th1F2Br0IEwFZxFMUaptrukLuk5h9_IjACr2cQ2b6LerYi4vAVxmjqRYQ53B0JQCPhblF0ELGd2mI2EYkdsGyJHghHn1fMvANorMCwAehsPIANv_6i_yZjt8MGOZtgedlgbGPSmBpXnOJ0g?width=431&height=245&cropmode=none)

- silahkan kerjakan soal yang telah diberikan, dan masukan jawaban anda ke folder yang baru anda buat 
- teknis pengumpulan soal akan menggunakan sistem *pull request*

## C. Pull Request
- sebelum anda melakukan *pull request* ke repositori pusat (respositori asal), **PASTIKAN!** bahwa semua file atau jawaban yang anda buat sudah disimpan dalam **SATU FOLDER** (NAMA-ANDA-PROGRAM) e.x. ALEE-JCWM15
- simpan perubahan yang terjadi di *git* dengan cara : ```git add nama-file``` atau ```git add .``` untuk menyimpan semua perubahan yang terjadi sekaligus
    
    ``` C:\data\alee\ujian-fund-JCWM1604> git add . ```

- kemudian lakukan ```commit``` : ```git commit -m "masukan pesan commit"```, e.x. "alee : ujian fundamental JCWM15"

    ``` C:\data\alee\ujian-fund-JCWM1604> git commit -m "remidial fundamental alee" ```

- *push branch* tempat anda mengerjakan soal : ``` git push origin nama-branch ```

    ``` C:\data\alee\ujian-fund-JCWM1604> git push origin master ```

- buka GitHub anda dan lihat repositori hasil *forked* anda. **PASTIKAN!** bahwa jawaban ada sudah dalam satu folder dan sudah ada di GitHub
- jika sudah ada, maka akan ada *warning* untuk melakukan ```compare & pull request``` <br>
    ![guide_4](https://dm2302files.storage.live.com/y4m2dJ8J89jraiM5iS4AVm6zxO-1O8bguKNRCbN6kGKePSTXMZuYC4PXE1YsIp2U0JwhSi_6d0jwLlh5s_EZRLuVfhd760uHVJROJsryPGn-6WcWrto3BwJu31tm4Tb3pA69WOPJ_b5jgiEgNncUE1VLbOUWDx4LNHheVlUlcWloQgv5dqBhBkjabdBHlV9Eu21?width=910&height=87&cropmode=none)

- lakukan *pull request* dan pastikan bahwa
    1. **HEAD repository** berasal dari repositori kalian dan **compare branch** berasal dari *branch* tempat anda mengerjakan soal (**master**), **BASE respository** menuju repositori asal dan *base branch* : **master**
    2. beri informasi *pull request* berupa : nama-program
    <br>e.x. : alee-JCWM1602
    
    ![guide_5](https://dm2302files.storage.live.com/y4mB5vT1TOj86BTO9XcBFVofhU0RPOD56p7apP9nrUNFf0pGAENB1twOWXhEQhHsRiBj_sI_b0ds9iONJsYKJ9tAn_WqdG7dnFzSeLSge1VVUWosdVfb5FCRfqWLMCcGk4MJyAKV0rmv6c-2FPyMU5rhIq-gkO6cVZRVdZDUmnMIkTOW_N6N68mxvVHC3_p5OxP?width=960&height=631&cropmode=none)

- jika *pull request* berhasil dan tidak terjadi konflik maka akan muncul info berikut ini
    ![gudie_6](https://dm2302files.storage.live.com/y4m6d20-8wJHrBabe5o3boRoyLEkWPCmcvaz6z2nMFp8Qu4gVx9DBkXabQhTI8kDRAiaVshkOKYW5hX67J2SJuzwkD10vvnMPEw36Hb0c4f-sKPyNlpes8wKlB0Rqp6_-Ky1HGsw-rwuxGs-EN0x_50XsI2_ypPTpoaIZiduU-g8LAQS5OeUCdg_xVas0Fen4GY?width=939&height=138&cropmode=none)

## Selamat Mengerjakan Ujian ☺
