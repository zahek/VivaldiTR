Bugünkü sürüm hatırı sayılır sayıda (70 civarı) hata düzeltimi ve geliştirme içermekle beraber **WebRTC için yeni gizlilik ayarı, Linux kullanıcıları için sekmeleri arka planda uyutma ve yeni fare hareketleri** içermekte...

%%%%

###Gizlilik ve WebRTC###

![webrtc](//res.cloudinary.com/vivaldi/image/upload/v1468305227/webrtc_o7d5rr.png#full-width)

[WebRTC](https://en.wikipedia.org/wiki/WebRTC) (Web üzerinden gerçek zamanlı iletişim) kullanıcılara web üzerinde ek bir uygulamaya gerek duymaksızın gerçek zamanlı iletişim kurma olanağı sağlayan bir HTML teknolojisidir. Tarayıcı(lar) üzerinde kolayca **ses, video ve dosya paylaşımı uygulamaları** kullanabilirsiniz. Pratikte oldukça güzel bir teknoloji olsa da web sitelerinin sizi kolayca izlemesine de olanak sağlamaktadır aynı zamanda.

Eğer gezinirken arkanızda bir üçüncü gözün olmasını istemiyorsanız ayarlar bölümünden bu ayarı kapatabilirsiniz.

**_Ayarlar => Gizlilik => WebRTC IP yönetimi_**

Fakat bu servisleri kullanan bir web sayfasını (**Google Hangouts, Appear.in gibi**) kullanacaksanız bu ayarı tekrar aktifleştirmeniz gerekecektir.

###Yeni fare hareketleri###

![webrtc](//res.cloudinary.com/vivaldi/image/upload/v1468305227/fare_akmcyc.png#full-width)

Bu sürümde tarayıcıyı daha fazla kontrol edebilmeniz için yeni bazı fare hareketleri ekledik. Bunlar sayfada hızlıca aşağı yukarı hareket etmenizi sağlayacak komutlardır. Ayarlar sayfasından yeni komutları deneyebilirsiniz. Eklenilen yeni hareketler: **Scroll Top, Scroll Bottom, Scroll Page Up ve Scroll Page Down**

###Linux için arka plan sekmeleri uyku modu desteği###

Bir diğer değişiklik ise Linux kullanıcıları için eklendi. Bildiğiniz gibi kullanılmayan arka plan sekmelerinin kaynak kullanımını azaltmak için arka plan sekmelerini uyutma özelliği mevcut. Fakat bu özellik Linux sürümlere eklenememişti. Bu sürümle beraber artık Linux sürümlerinde de bu özelliği kullanabilirsiniz. Sekme üzerinde sağ klik menüsünü kullanarak kullanmadığınız sekmeyi ya da tüm arka plan sekmelerini uyku moduna alabilirsiniz.

Belki bazılarınız fark etmişsinizdir, varsayılan arama motoru şu an Yahoo olarak gelmekte. Halen arama motorları konusunda bir takım testler yapmaktayız ve sizlerden geri bildirimler topluyoruz. Fakat halen bu seçenek özelleştirilebilir durumda ve istediğiniz zaman arama motorunu değiştirebilirsiniz.

Keyifli testler dileriz...

#### İndirme Adresleri (1.3.534.3)

* Windows 7+: [İndir 32bit](https://downloads.vivaldi.com/snapshot/Vivaldi.1.3.534.3.exe) (Tavsiye edilen sürüm) | [İndir 64bit](https://downloads.vivaldi.com/snapshot/Vivaldi.1.3.534.3.x64.exe)
* Mac (10.9+): [İndir](https://downloads.vivaldi.com/snapshot/Vivaldi.1.3.534.3.dmg)
* Linux Deb: [İndir 64bit](https://downloads.vivaldi.com/snapshot/vivaldi-snapshot_1.3.534.3-1_amd64.deb) (Tavsiye edilen sürüm) | [İndir 32bit](https://downloads.vivaldi.com/snapshot/vivaldi-snapshot_1.3.534.3-1_i386.deb)
* Linux RPM: [İndir 64bit](https://downloads.vivaldi.com/snapshot/vivaldi-snapshot-1.3.534.3-1.x86_64.rpm) (Tavsiye edilen sürüm) | [İndir 32bit](https://downloads.vivaldi.com/snapshot/vivaldi-snapshot-1.3.534.3-1.i386.rpm)


#### Değişiklikler
* [Regression] Buttons of address bar extensions hardly visible (VB-19136)
* [Regression] Home page is loaded in new tab (VB-19249)
* [Regression] Minimise instead of closing pinned tabs (VB-19411)
* [Regression] Paste & Go not working with unfocused address bar in website (VB-19150)
* [Regression] Selection not always persisted in URL field
* [Regression] [Mac] Pinch zoom is not working correctly in Vivaldi 1.2 (VB-18043)
* [Regression][Windows10][Themes] Window close button is the wrong colour in some themes (VB-19439)
* [Windows][Installer] Changing from all user install to standalone install after selecting a new install dir, changes the install dir back to default (VB-18965)
* [Windows][Installer] Previous destination folder in installer to show when opening the "Browse" (VB-19103)
* [Linux] Enable support for tab hibernation (VB-19406)
* [Mac] Page is zoomed at the same time it is scrolled (VB-19308)
* [Bookmarks] Icons without title on bookmark bar are not centered (VB-10236)
* [Bookmarks] Import bookmark from Vivaldi doesn’t import nicknames (VB-17454)
* [Themes][Bookmarks] White text on white background in add bookmark dialog in private mode (VB-19410)
* [Themes] Add Olive theme (VB-19238)
* [Themes] Tab load indicator in dark theme is dark (VB-19483)
* [Themes][URL] No option to color progress bar and URL bar (VB-14158)
* [URL] Address field steals focus (VB-19250)
* [URL] A setting so that search suggestions work only when using search engine nickname (VB-19129)
* [URL] Selection undex of autocomplete should be at cursor position (VB-3562)
* [URL] Does not restore on reload after being deleted (VB-19275)
* [URL] Drop downs should close when opening quick command (VB-19104)
* [URL] Drop down does not disappear when pressing Tab (VB-19164)
* [Search field] Paste and go does not work in search field (VB-19202)
* [Search field] Pressing Esc in search field doesn’t move focus to web view (VB-19198)
* [Search field] Dropdown close when window loose focus (VB-19210)
* [Search field] Typed history does not appear when suggest URL blank (VB-19182)
* [Search field] Shows suggest results after loosing focus (VB-19211)
* [Search field] Typed history does not show up (VB-19201)
* [Web panels] Adding/removing webpanel opens it also in other windows (VB-14452)
* [Gestures] Adding to list of mouse gestures commands: Scroll Top, Scroll Bottom, Scroll Page Up, Scroll Page Down (VB-18639)
* [Gestures] Saving a blank gesture still possible - after moving out of draw area (VB-18422)
* [IME] Focus gets lost from input fields after pressing Enter while typing Japanese (VB-19108)
* Audio icon keeps firing after tab has been closed: caused performance issues (VB-19344)
* Change Bing favicon to comply with MS guideline (VB-19006)
* Clicking search suggest or item in typed history doesn’t search (VB-19208)
* Close the last tab didn’t close the window. (VB-17707)
* Deactivate Search Suggestions in Private Windows (VB-19271)
* Default themes possible to be deleted without possibility to restore them (VB-19058)
* Disable Tab Bar resizing with Tab Thumbnail mode OFF (VB-16326)
* Escape does not cancel JavavScript dialogs (VB-12353)
* Expand panel to a tab (VB-18773)
* Extra indent in webpage focus settings (VB-19268)
* Handle middle-clicks on panel buttons (VB-12632)
* Hyperlinks spanning multiple lines are not marked with spatial navigation (VB-18999)
* Implement Yahoo! search as default search engine for testing (VB-19122)
* Improvement of New Tab Page options (VB-17410)
* In default keyboard commands "Detach tab" and "Downloads panel" are the same (Ctrl+Shift+D): detach is unmapped now but still mapable (VB-19394)
* In Web Panel with Extensions page added, clicking Options crashes Vivaldi (VB-13933)
* IP broadcasting setting for WebRTC does not change appearance on click (VB-19001)
* Nested checkbox should align with parent (VB-19470)
* Opening "Privacy" and "Display all" causing lag / freeze on a slow pc (VB-18953)
* Private window with corner rounding looks broken. (VB-18667)
* Remove option to close pinned tab through context menu, with don’t close pinned tab enabled (VB-19035)
* Right clicking on speed dial items initiates page load (VB-19100)
* Selecting tabs in stack is difficult because of menu bar taking focus (VB-10501)
* Tab tile widget in status bar can be behind tabs (VB-19310)
* Unable to find thumbnail settings (VB-15073)
* Updating thumbnail notification icon looks irregular (VB-18566)
* Vertical tabs covered by scrollbar (VB-19338)
* With dark theme, the cookie list ends up as both black and white. (VB-18958)
* Wrong focus and text styling in Import Bookmarks dialog (VB-19415)
* Zoom slider and number do not highlight when hovered (VB-19119)
* Upgraded to Chromium 52

**Not:** Bu sürümle ilgili tüm olumlu/olumsuz görüşlerinizi buradan yahut **[Vivaldi Türkçe Forumları](https://vivaldi.net/forum/turkish)** üzerinden bizlere iletebilirsiniz.
