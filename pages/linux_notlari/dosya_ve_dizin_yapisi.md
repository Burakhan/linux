---
title: Dosya ve Dizin Yapısı
tags:
  - getting_started
keywords: "linux notlari, başlarken, linux dosya ve dizin yapısı, linux nedir"
last_updated: "November 11, 2017"
summary: "Bu safyada linux dosya ve klasörlerine dair kısa notlar bulunmaktadır."
published: true
sidebar: linux_notes_sidebar
permalink: dosya_ve_dizin_yapisi.html
folder: linux_notlari
---

Öncelikle

## /
root dizin. Tüm dosya ve klasörler bu dizin altında bulunmaktadır.

## /bin
Sistem genelinde kullanıcıların kullanabileceği komutlara ait program dosyalarının bulunduğu klasör

## /sbin
Sadece root kullanıcının kullanabileceği komutlara air dosyalar burada bulunur

## /boot
Sistemin açılışı sırasında kullanılan dosyalar bu dizin altında bulunur.

## /dev
Sistemdeki aygıtlar ve disk bölümlerine ait dosyalar bu dizin altındadır. Her bir aygıt yada donanım bu dizin altında bir dosya görüntüsü olarak bu dizin altında bulunur.

## /etc
Sistemle ilgili yapılandırma dosyaları bu dizinin altında bulunur. Sistemde çalışan servislerin konfigigürasyon dosyaları bu dizinde bulunur.

## /home
Sistemdeki kullanıcıların ev dizinidir. 

## /lib
Programlar tarafından ihtiyaç duyulan kütüphane dosyaları bu dizindedir.

## /lost+found
PC düzgün kapanmadığında açıldıktan sonra çalıştırılan fsck komutu tarama ve onarma işlemi sırasında bazı dosyaları buraya atar. Kayıp eşyaların tutulduğu yer gibi düşünebilirsiniz.

## /mnt
Otomatik olarak mount edilen aygıtlar ile ilgili dosyaların bulunduğu dizin

## /media
Bu dizin de mnt dizini gibidir. Sisteme bağlanan aygıt dosyaları buradadır.

## /opt
Sistem yöneticilerinin bazı uygulama programlarını yüklemeleri için tasarlanmıştır. Genellikle boştur.

## /proc
Sistemde çalışmakta olan süreçlerin bilgisinin bulunduğu sanal bir dosya sistemidir.

## /root
Sistemdeki en yetkili kullanıcı olan root kullanıcının kişisel dizinidir.

## /tmp
Herkesin kullanabileceği geçici dosyaların saklandığı dizindir.

## /usr
Uygulama programları ile ilgili dosyalar bu dizinde saklanır. /usr/local sistemdeki tüm kullanıcılara açık bir dizindir. Sisteme yeni bir program yüklenmek istendiğinde /usr/local/bin altına yüklenirse tüm kullanıcılar bundan faydalanabilir. /usr/sbin dizini ise sistem yöneticisinin kullanacağı komularla iligili dosyaların bulunduğu dizindir.

## /var
Log dosları ve web sunucu programına ait dosyalar bu dizin altında bulunur.