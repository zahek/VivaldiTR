![1.0.422.8](http://res.cloudinary.com/vivaldi/image/upload/v1458117490/ss104228_airfpr.png#full-width)

Bugünkü sürümde **Chromium 49** güncelleştirme sonrası ortaya çıkan bazı ciddi hatalar onarıldı. Özellikle **akıcı kaydırma ve her an karşınıza çıkan ölü kuşlar (dead birds) uyarı sayfasına** ilişkin onarımlar yapıldı. **Arama tavsiyelerinde ayrıca bir takım gelştirmeler yapıldı**. **Netflix** tekrar çalışır duruma getirildi. Bir diğer onarım ise **sayfa kaynağını görüntülerken klavye kısayollarının çalışmaması** konusunda yapıldı.

Hataların özellikle tarayıcı çekirdeği güncellemesi sonrası ve spesifik platform ve işletim sistemlerinde olması (ki bunların hiçbiri ne Oslo ne de Reykjavík'de kullandığımız sistemlerde mevcut değildi) nedeniyle sizlerden gelene bildirimler sonucu tanımlanarak onarıldı. Bu anlamda sizlere teşekkür ediyoruz.


#### Bilinen sorunlar

* Hızlı erişim ön izlemeleri yüklenemiyor.
* Türkçe dilde arama önerileri gelmiyor. Geçici olarak test etmek amacıyla aşağıdakileri uygulayabilirsiniz.
 * Ayarlar/Başlangıç/Dil ayarlarından tarayıcı dilini İngilizce olarak değiştirin ve sonrasında /Arama ayarları altındaki "Varsayılanlara Dön" düğmesini tıklayarak arama motorlarını sıfırlayın.

%%%%

#### İndirme Adresleri (1.0.422.8)

  Windows: [İndir 32bit](https://vivaldi.com/download/download.php?f=Vivaldi.1.0.422.8.exe) | [İndir 64bit](https://vivaldi.com/download/download.php?f=Vivaldi.1.0.422.8.x64.exe) (deneysel)

Mac (10.7+): [İndir](https://vivaldi.com/download/download.php?f=Vivaldi.1.0.422.8.dmg)

Linux Deb: [İndir 64bit](https://vivaldi.com/download/download.php?f=vivaldi-snapshot_1.0.422.8-1_amd64.deb) | [İndir 32bit](https://vivaldi.com/download/download.php?f=vivaldi-snapshot_1.0.422.8-1_i386.de)

Linux RPM: [İndir 64bit](https://vivaldi.com/download/download.php?f=vivaldi-snapshot-1.0.422.8-1.x86_64.rpm) | [İndir 32bit](https://vivaldi.com/download/download.php?f=vivaldi-snapshot-1.0.422.8-1.i386.rpm)




#### Değişiklikler

* Browser is very slow and very often dead bird shows up / HPET problems: This affected only certain OS and CPU combinations (VB-14036)
* Active tab does not have a minimum size (VB-13832)
* DuckDuckGo (d) and Bing (b) should show their own search suggest when actioned via the search letter/keyword
* Clicking Speed Dial lacks modifier (Ctrl, Shift) support seen in the bookmark menu (VB-11458)
* Need to fix tab stack selection and add Shift select
* [Linux] Support mouse handling and context menu on empty part of tab bar when native decorations are on (VB-14031)
* [Linux] [Windows] Vertical menu (Vivaldi menu) opens in Settings window (VB-14189)
* Moved Search Suggest after Search
* Netflix Streaming not working: due to Netflix blocking Vivaldi in User Agent (VB-13918)
* Open and save dialogs can block and operate on wrong window (VB-14025)
* [Regression] Text truncated ended with ellipsis when pasting to the URL field (VB-13206)
* Shortcuts doesn't work on the view source page (VB-13417)
* Tab styling changes, including selection styling
* The bookmark title expansion in the address bar doesn't reset and leaves the title (VB-13917)
* Tiling button states confused (VB-14191)
* Weird bookmarks focus issue (VB-10374)
* [Windows] Wrong color window controls on hover on Win10 (VB-14021)

Sürüm ile ilgili yayınlanan yazıya ve tüm değişiklik listesine **[buradan](https://vivaldi.net/en-US/teamblog/93-snapshot-1-0-422-8-quick-fixup-for-issues-in-the-previous-snapshot)** ulaşabilirsiniz.

**Not:** Bu sürümle ilgili tüm olumlu/olumsuz görüşlerinizi buradan yahut **[Vivaldi Türkçe Forumları](https://vivaldi.net/forum/turkish)** üzerinden bizlere iletebilirsiniz.
