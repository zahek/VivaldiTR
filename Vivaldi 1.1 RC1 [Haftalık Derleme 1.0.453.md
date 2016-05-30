**Vivaldi 1.1 karalı sürüm güncellemesine yaklaşırken ilk RC sürümünü yayınlıyor. Eğer çok büyük bir hata ortaya çıkmaz ise bu sürüm sonrası kararlı sürüm olarak yayına alınacak.**

Geçtiğimiz haftaya şöyle bir baktığımızda aşağıdaki başlıkların öne çıktığını söyleyebiliriz. Tabii ki tüm değişikleri aşağıda görebilirsiniz ayrıca.

##### Yeni Sekme Kapatma Davranış Seçeneklerinden

![Sekme Kapatma Seçenekleri](https://vivaldi.net/images/tab-closing.gif#full-width)

Yeni eklenen ayarlar ile artık sekmeleri kapattığınızda **sol yada sağ taraftaki** sekmeye geçiş yapmayı sağlayabilirsiniz.

##### Eski İşletim Sistemleri Desteği

Vivaldi 1.1 sürümle beraber artık eski işletim sistemlerine (Windows XP, Vista ve OSX 10.9 öncesi sürümler) destek vermeyecek. Bunu ana nedeni Microsft ve Apple'ın bu sistemeleri güncellemeyecek olmasından ötürü, Chromium projesinin artık bu eski sürümlere destek vermeyecek olması.

Eğer sistemlerinizi güncelleyebilirseniz yeni Vivaldi özelliklerini deneyebilirsiniz, aksi taktirde Vivaldi 1.0 sürümünü kullanmaya devam edebilirsiniz.

Bunun yanı sıra 1.1 sürümle beraber artık NPAPı eklenti desteği de olmayacak. Gelecek için PPAPI eklentisi ve yeni HTML5 teknolojileri ile ilerlemeye devam edeceğiz.


Bir diğer önemli değişiklik ise **[Chromium 50](http://googlechromereleases.blogspot.com.tr/2016/04/stable-channel-update_13.html) güncellemesi** elbette...



%%%%

#### İndirme Adresleri (1.0.453.36)

Windows: [İndir 32bit - Win7+ ](https://vivaldi.com/download/download.php?f=Vivaldi.1.0.453.36.exe) | [İndir 64bit-Win7+](https://vivaldi.com/download/download.php?f=Vivaldi.1.0.453.36.x64.exe) (deneysel)

Mac (10.9+): [İndir](https://vivaldi.com/download/download.php?f=Vivaldi.1.0.453.36.dmg)

Linux Deb: [İndir 64bit](https://vivaldi.com/download/download.php?f=vivaldi-snapshot_1.0.453.36-1_amd64.deb) | [İndir 32bit](https://vivaldi.com/download/download.php?f=vivaldi-snapshot_1.0.453.36-1_i386.de)

Linux RPM: [İndir 64bit](https://vivaldi.com/download/download.php?f=vivaldi-snapshot-1.0.453.36-1.x86_64.rpm) | [İndir 32bit](https://vivaldi.com/download/download.php?f=vivaldi-snapshot-1.0.453.36-1.i386.rpm)


#### Değişiklikler

##### [1.0.453.36](https://vivaldi.net/en-US/teamblog/107-snapshot-1-1-453-36-vivaldi-1-1rc1)
* [Regression] POST to new window results in second GET request to same URL (VB-16295)
* [Regression] Characters lost in URL field (VB-16268)
* [Regression] Cannot create a new bookmarks folder (VB-16165)
* [Regression] Use of Find In Page makes tabs unresponsive (VB-16332)
* [Linux] HTML5 proprietary media does not work in Vivaldi 1.1 under Ubuntu with chromium-codecs-ffmpeg-extra 49.0.2623.X (VB-16300)
* [Linux] Possible crash under 32bit (VB-16270)
* Disable all but Ctrl+t,n,w keyboard shortcuts when plugins are focussed: Workaround for clashes e.g. backspace in Flash or PDF forms. A few more may be enabled before the 1.1 final (VB-15312)

##### [1.0.435.30](https://vivaldi.net/en-US/teamblog/106-snapshot-1-1-453-30-more-fixes-as-we-close-in-on-the-1-1-stable-update)
* [Regression] Ctrl or Shift Click on Speed Dial entry opens blank tab (VB-16199)
* [Regression] Fast forward button is not activated sometimes (VB-15979)
* [Regression] Title completion in bookmarks is not working (VB-16202)
* [Regression] Items for Mail and Contact panels show up View menu on all builds (VB-16194)
* [Regression] Installer mentions Chrome in an error message (VB-14837)
* Translation updates

##### [1.0.453.6](https://vivaldi.net/en-US/teamblog/105-snapshot-1-1-453-6-further-tab-closing-options-improved-dark-ui-and-more-import-options)
* [Regression] [Windows] Vivaldi steals focus (VB-14708)
* [Linux][Mac] Add missing setting to switch the Vivaldi UI language (as on Windows) (VB-15885)
* Added setting to disable the URL Dropdown
* Add "Right of current tab" in tab settings for a Close tab (VB-12674)
* Arrow symbol in bookmarks bar does not work properly (VB-4479)
* Better transition for Ctrl+Enter (www.<input>.com) in URL field
* Bookmarks bar list under chevron icon displays wrong items (VB-15831)
* Bookmarks bar is mssing New Folder context menu option (VB-15501)
* Browser closes when using the Pocket extension (VB-14498)
* Can not move a bookmark item to the end of list on the bookmark toolbar (VB-15975)
* Close Other Tab Doesn't deal with stacks (VB-15916)
* Close other tabs when ALT-clicking tab close button: now possible to assign keyboard shortcut and accessible in Quick Commands (VB-15157)
* Cutting from start in URL field clears URL field (VB-15350)
* Dark scrollbars in panels and bookmarks when Dark UI is set (VB-15901)
* Dropping a bookmark bar item on the bookmark bar creates a new item (VB-15907)
* Faster Tab Stack Creation
* Forward and back mouse buttons operate on wrong window (VB-14952)
* Going to the wrong site on autocomplete (VB-15301)
* Group similar tabs to stack can group very different sites (VB-10110)
* Hibernate tab stack (VB-13209)
* Hide tooltip when searchfield or URL field gets focused or updates
* Improve automatic underscoring in menus (VB-15349)
* JavaScript "window.open" causes 2 HTTP requests: Lastpass showed a blank page when opening Secure Note (VB-13931)
* Menu key activates wrong context menu for Spatial Navigation highlighted links on windows (VB-9169)
* Move to New Window option should not be in tabs in Private windows (VB-15179)
* Not Possible to Hibernate/Close Tab Selection (VB-15037)
* Page can override Spatial Navigation indicator (e.g. cnn.com) (VB-15735)
* Per tab zoom does not activate immediately but only after browser restart (VB-13959)
* Radio button in toggle image menu squeezed (VB-15013)
* Renaming items on the bookmark tool bar is confusing with Title sorting enabled (VB-15711)
* Reset fast forward earlier on navigation and load when idle
* Saving changes to bookmark using enter/return (VB-15740)
* Some URLs are searched instead of followed (VB-14729)
* Speed dial not imported from Opera 12 (VB-15036)
* Speed dial sorting follows bookmarks manager sorting (VB-14418)
* Tabs cloned from stack appears to the right of the stack (VB-11055)
* Tab Tiling is Cleared when Stacked (VB-15277)
* Use input case when autocomplete on URL
* Vivaldi Missing Title Case in Translation (VB-15342)
* Upgraded to Chromium 50.0.2661.75: With this we drop support for Windows XP, Vista and versions of MacOSX below 10.9. In addition we have disabled NPAPI plugins


**Not:** Bu sürümle ilgili tüm olumlu/olumsuz görüşlerinizi buradan yahut **[Vivaldi Türkçe Forumları](https://vivaldi.net/forum/turkish)** üzerinden bizlere iletebilirsiniz.
