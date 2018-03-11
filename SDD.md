Software Design Document (SDD)

Versi 01

08 Maret 2018

Disusun Oleh :

Eko Prastyo 		 (1603096)

Syahrul Gunawan 	 (1603113)

Tuti Nurafni Amalia  (1603116)

Wulan Diani			 (1603118)

JURUSAN TEKNIK INFORMATIKA

POLITEKNIK NEGRI INDRAMAYU

BAB 1

PENDAHULUAN 

	1.1 Tujuan
 
Dokumen Software Design Document (SDD) merupakkan dokumen spesifikasi perangkat lunak 
untuk membangun "Aplikasi Pemesanan Lapangan Futsal". Dokumen ini dibangun untuk memudahkan Prima  Fusal dan Sintia Sinta Futsal .Dalam melakukan proses pemesanan lapanganfutsal yang dilakukan oleh penyewa lapangan. Sehingga dokumen ini dapat dijadikan acuan teknis untuk membangun perangkat lunak "S'Sal" Aplikasi Pemesanan Lapangan Futsal.

	1.2  Lingkup proyek

S'sal merupakan aplikasi untuk pengguna kalangan umum untuk pemesanan dan penjadwalan penggunaan lapangan futsal, serta dapat memberikan informasi pemesanan lapangan dan penjadwalan futsal. dan mempermudah pelanggan untuk pemesanan lapangan futsal.

	1.3  Definsi,akronim,singkatan

| Istilah | Arti                                             |
| ------- | ------------------------------------------------ |
| SDD     | *Software Design Document*                       |
| IEEE    | Institute of Electrical and Electronics Engineer |

BAB 2 Referensi

[1]IEEE Software Engineering Standards Committee, IEEE Std 830-1998, IEEERecommended
[2]https://en.wikipedia.org/wiki/SDD

BAB 3 DFD 

3.1 Diagram konteks
![diagramkonteks](https://lh3.googleusercontent.com/mHHjundGMn0fuQbVAEQOlrkB15DZm27ZZlO-zhoxQFCdkpW1co7l87V3-br-q721SAyxaovE2NC1CNrRBANp6tLMaRkyU6gmZlGQ1DouIvw3OH00w0uBxYcEfyB3Hk-ivBTmJEeDGe_SrvU0_DrLY7-qOn4fucCfD2nF2AX0Svr5ZAQKpdohZrPuHLKG_7ZmMVbB94U04xYLcOt6Z432Eddj3PZrHJWmai5DS8YXKJetdQIrRAT0FPUJYju8_xay1ehGUEcBHdgSInv4Mf0AmKdxY1PswLhJZ1hSZwedpa2edRBWRoYxJebaJ33DLQ3SGUo92KEs-LaSMjITowKs9g6xRbrrQ22JchGcuvvM566PGdpHC7h93lHmNRxNk-Cgjxz0NtoKtYXb2r79ZehvoOwUvdXxLc_NBP9SxXnyX1jWSOevBB6S5hren0pDTPDbdaNUk88rHbIJJ8piYq7k_Gye6anY4vE_M5eWxwQobKzeShYBmguauyciFKP3RoG9mlQcbippxxwBagb_LpMB2te-kxIuNxh71Ex-yF17-gl0kAfTNcxL1URyMkpJeACD6cP2AcpnYusIzMaUK-VDPBtSNZP33zeMVEdhm9A=w339-h220-no)        

3.2 Diagram level 0
![level0](https://lh3.googleusercontent.com/Y_0xXrMHZzirTCXIgTl0uSsc_QesnYpfAPk8nreFcirfsBB6cFsIbweKVPVPTLTacI5f401dYWFREiHSTz6dACQ7OZjS39lMqRD44inyaNPQYxnpe3d6bjbMeQJMGzIqJcFlK5X1pAHhxt5aNbHYVc1V-irnTemQLsJOCwZsNgPq2--x5NfNXBhoHHv3fYNsqgTf2RVsGfZxJqJhKlxUmH3cXVXgIEJ4my-H1WChh8TWHK5oGytpml-WaXO7GTWcur0AUB-TeowTlnDkicK6QKBv2AD0-Twfkq_u30CIl4wIkUKJ0NeiobVCl-_WBBXfvCzri_Zo0aXQSHfLVTzGNuDc4KYxd1I4M9lE3b_UimnViOZxDAaQ72Wi9yTxtTg9z5GT5a0Ln0EBcslOSoF_6QOtbLNurZEoa62KuXUkL0vVfcoKrzJVgkeVwqXjo6hTrosl6DH-UtWXdnh9QrgVr9G8tOmkwJTGg6gs_4OspevopDeK9YVTwA5gwR379eWfjcPTnwZmrD-BZyZjsiu1k0fDL5IALCViPAAZ8baTCup1Kzgpm25dePwCI2CDFbiu1Z_rxFiCtGlVKR_ZLk74LVQON4twDyNoVnml1ew=w589-h449-no)
3.3 Diagram level 1
![level1](https://lh3.googleusercontent.com/X7HtnrLlk_HOzLk-IKIIdrEm5XQqYzrHkpza3QWu_EwXpQdK5Ly2_LTV-JZBGjlQJKM6lxpclz52cAKUgPdhhfQ7_spLKX9Pwx_Rh5u0uer579qu3zi4NvDJp8InpuybxycGITqfV5NTwYcJklnZmE8IFdTNC2n-lJcOsc8m_vp3Id3KO7pGhobVe2uN2EGzgRMdzy0uBlUfeVMOW6YpMEyz4nUccWZCxHW6jl1JxYyicvKJhA7GUZlM0tzmSJbT6RJkge1gcE96WJEgZyJnw-ip7qIeZ3keKGupkdJ7fh3_ntaXnsMvC3DAfNBkzW8H0JlHdmQIbhzBQbMprvfR2uIa2GSlm67JgwRekeiNoPo-18zdMvPV6ydhgRfM-JToOmtHP95nO93XPjMjV90IyI95N_1fAG47zkn_OZyQ4gc93pSe7523XvAu7ZAP_cDwFRc48ax37L8hbraE9POcYDHccNB9dTQ5qex1HpuLfzihdg_qxGh0_T7CqAJaXqRCRVFVI1k4azOg9k7Zgb6XxeZ_m8-EH5GaPtfikZ9aTVeOrQaNZ2khmlUQCp1EwRKDW-0DDFDVb7ziH-Zh-kaImAWhCOWt2ARGlSioDh8=w849-h451-no)

3.4 Diagram level 2
![level2](https://lh3.googleusercontent.com/kK24ZUbtG9ncHRcQ33wodBrqGRWdIYvddH0SkL-go3dCdya6Aw2PytaTybnuJ9HHqbGCap2ApT2CkZfN7k3pw9n-YXy88XC4qwMR-GMfGiIcDtfT5oen1eCWRZA0KRrd8pbrGAXko4WXiIgX2YErpHIIZHJcb9MNqowazxs58_a4KxU-vCQioNAohwWvLeA1wan-F0OYMT_IuLRKornvkKPcwyT5NoYRC-8ZKBYyLjO3wyxb6Hq2o0-2DvCQX7s-khuiwk25aaWQFt6BEXPrkahUV1FD7CE6N5WcD-08OfjJTA2BQWtjwS6A3MBuggSmTc5kHp76mh96HBK7tmU_nfienQer5bmA1dTXUIIDb9oXU-mnlRATB1VGaI4HxOGzao8bZvS3CAQr2ABmpqHWOzRziQRJODK8i3xD6kdUG9peQFXJ_DNXjpIVIveUbiN3f8vc3Ia0yVm9jPC-2WAvKjstsbi1RALD1NzpQQhPWB8ND1pJjELxpOIGF4n0CaxCqMFSKDRC34bq25PXysRKAQXRj0OWna_rBRDt6ryegB8IC9kdUxjdG4pZU2BjLjdg_OBurWeraFUrwR7TNZvl9bkXrJ2wL3BGR8Y3dQM=w714-h450-no)

3.5 Diagram level 3
![level3](https://lh3.googleusercontent.com/Vdm96YqBQ3-Vof4WJ7h_GXwpmXtWi-qmfbDEARG52cCtDL3uKmd3aSiTfkaJfkjJnmT2U0CyFnCxem26Qmp5A95lNxKbeg9W2DKuLFNyH-mr0h9vNkYD5sTtQeND2u_HKwokD0HI--aiuUA-NNVmA7SAxYbs3oBXQsShNPzUlOzascJWcl6nsfi4L78lHBxKBMNzg1mU8Q2UeMMC2sBmCtyrEwfmPFezcHTRL3HYGHdXcl5HhHxSdd9LOPoQwHydAHUo74DNCZsPNYQzH8uyMMGLoBqNIQrViAve6YpbZkFFhDf-tOcN0fqwhasOYAz6WDaxUE9F1i7C_17ODr99uduegl_F4RY1Rfk_sqg35WTdoQIZwLINS-_u9DOX71vld0zTMG3dkBqOIgbPURAy4I8MDl-_gKhxKdisHtDEAfKY00u-hXc1nORzfxJ3o9wri43ncfyubervhyoS--0OCcM3_7iI3UZ-pBxtRhtdt0SgbC9HQ7TC3FDbdajPNd-lzYw_P9ko26pmEJv1cstxaZovb3q-63NKL2CjBHIwMWblPDe1Qx4ccOsISRfj2B6VkGRzDm7kn5uHuWEBETp5iuIn5QUrWX5YPs_M2F8=w692-h392-no)



