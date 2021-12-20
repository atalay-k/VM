## TUBITAK 4005 BUYUK VERI ANALITIGI 


# VERI MANIPULASYONU 


--
title: "TUBITAK 4005 R ile Buyuk Veri Analitiği"
subtitle: "Veri Manipulasyonu"
date: "16/12/2021"
output: 
  html_document:
    toc: true
    toc_depth: 3
    toc_float: 
      collapsed: false
      smooth_scroll: false
    theme:  default
    highlight: null
    css: styles.css
---



## Gun Boyunca 

### Sunumlar

0. [Giriş ve Kurulum](sunum/00.html)  
<br>

1. [dplyr paketi giris](sunum/01.html)
 
   - dplyr paket tanıtımı
   - Veri yapısını anlama
   - pipe **%>%** operatoru
   - **select()**, **filter()** ve **arrange()** fonksiyonlar <br>
<br>

2. [Veriyi üst duzeyde toplama](sunum/02.html)

   - **count()** fonksiyonu
   - **grup_by()** ve **summarize()**
   - **summarize_all()** ve **summarize_if()** ve **summarize_at()**
   - **top_n()** 
   - **DataEditR** 
   <br>
<br>

3. [Seçme ve Dönüştürme](sunum/03.html)

   - **select()** fonksiyonu
   - **select()** fonksiyonu içinde çalışan fonksiyonlar
   - **rename()** fonksiyonu
   - **mutate()** ve **transmute()** fonksiyonları <br>
<br>

4. [Veri Setlerini Birleştirme](sunum/04.html)

   - **join()** fonksiyonlari
   - **left_join()**, **right_join()**
   - **full_join()**,**inner_join()**
   - **semi_join()**,**anti_join()**
   - **intersect()**,**union()**,**setdiff()**
   <br>
   
<br>

5. [Veri Formatı Degiştirme](sunum/05.html)

   - Veri formatı değiştirme
   - **tiydr** paketi
   - **gather()**
   - **separete()**
   - **spread()**
   - **unite()** <br>
<br>
   
6. [Uygulama](sunum/06.html)

   - Veri Seti İnceleme <br>
<br>
  


### Veri Setleri


- Türkiye Uluslararası Eğitim Verisi **(tuev)** geniş kapsamlı uluslararası başarı değerlendirme programlarından **PISA** ve **TIMSS** Türkiye verilerini depolayan bir R kütüphanesidir. 

- Bu eğitimde 
  - **PISA 2018** (OECD, 2019) <br>      
  - **TIMSS 2019** (Mullis, Martin, Foy, Kelly, & Fishbein; 2020) <br>  
veri setleri kullanılacaktır. 

-- 
- PISA 2018 Bu verilerin toplandığı ankterler

   - [Ogrenci Anketi](PISA_anketler/Turkish (Turkey) For Student_Questionnaire_Booklet_2018.pdf)
   - [Okul Anketi](PISA_anketler/Turkish (Turkey) For School_Questionnaire_2018.pdf)

TIMSS 2019 Grade4 Bu verilerin toplandığı ankterler

   - [T19_G4_CurriculumQ](TIMSS_anketler/questionnaires_4/T19_G4_CurriculumQ.pdf)
   - [T19_SchQ_4](TIMSS_anketler/questionnaires_4/T19_SchQ_4.pdf)
   - [T19_TQ_4](TIMSS_anketler/questionnaires_4/T19_TQ_4.pdf)
   - [eT19_StuQ_4](TIMSS_anketler/questionnaires_4/eT19_StuQ_4.pdf)
   - [T19_HQ_4](TIMSS_anketler/questionnaires_4/T19_HQ_4.pdf)
   - [T19_StuQ_4](TIMSS_anketler/questionnaires_4/T19_StuQ_4.pdf)


TIMSS 2019 Grade8 Bu verilerin toplandığı ankterler

   - [T19_G8_CurriculumQ](TIMSS_anketler/questionnaires_8/T19_G8_CurriculumQ.pdf)
   - [T19_SchQ_8](TIMSS_anketler/questionnaires_4/T19_SchQ_8.pdf)
   - [T19_TQS_8](TIMSS_anketler/questionnaires_4/T19_TQS_8.pdf)
   - [T19_TQM_8](TIMSS_anketler/questionnaires_4/T19_TQM_8.pdf)
   - [eT19_StuQ_8](TIMSS_anketler/questionnaires_4/eT19_StuQ_8.pdf)
   - [T19_StuQ_SepSc_8](TIMSS_anketler/questionnaires_4/T19_StuQ_SepSc_8.pdf)
   - [T19_StuQ_IntSc_8](TIMSS_anketler/questionnaires_4/T19_StuQ_IntSc_8.pdf)

## R'da devam etmek için

- Katılabilirsiniz [R for Data Science Learning Community](https://www.rfordatasci.com/).

## Eğitmen

Kubra Atalay Kabasakal, Hacettepe Üniversitesi, Eğitim Fakültesi, [Öğretim Üyesi](https://avesis.hacettepe.edu.tr/katalay)
<br>

[R notları](http://www.rpubs.com/kkatalayders)   


## Kodlar
Eğitimin tum materyallerine [bura](https://github.com/atalay-k/veri_duzenleme.git) 
dan ulaşabilirsiniz.



## Gün Planı

09:00 - 09:15 Kurulumlar 
<br>
09:15 - 09:45  dplyr paketine giris
<br>
09:45 - 10:30 Uluslararası eğitim araştırmaları
<br> 
10:45 - 12:15 Veriyi ust duzeyde toplama
<br>
13:00 - 14:00 Seçme ve Dönüştürme
<br>
13:30 - 14:15 Veri Setlerini Birleştirme
<br>
14:30 - 15:30 Veri Isleme
<br>
15:45 - 16:30 Uygulama
<br>
16:30 - 17:00 Günü özetleme ve değerlendirme
<br>



