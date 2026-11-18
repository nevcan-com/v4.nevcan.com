# Restore report: nevcan.com v4 (2014) and /dalgic (2015)

Restored from the Internet Archive's Wayback Machine (web.archive.org) on 2026-11-18, from the
captures of 2014–2015. Files of older versions that were still on the server then (v1's Joomla
theme, v2 and v3) were moved to their own repositories.

## Changes made to the archived files

- `index.html`, `dalgic/index.html`: a noindex robots meta tag; Google Fonts, jQuery (Google CDN) and
  the Google Maps script load over https (browsers block http on an https page).
- `dalgic/images/neptun-icon-white.png`: was loaded from neptunsualti.com, restored from the
  archive (2015) and served locally.
- `robots.txt`: the archived one was an error page, replaced with one that disallows everything.
- Absolute nevcan.com links made root-relative, `?ver=` queries dropped.

## Known gaps

- `dalgic/favicon.ico` and Bootstrap's glyphicons fonts were never archived.
- The contact map on /dalgic uses Google Maps API v3.7 without a key, which no longer loads.

## Sources (73 files)

- `assets/about.png` ← 20141224113809 http://nevcan.com/assets/about.png
- `assets/contact-bg.jpg` ← 20150124080838 http://nevcan.com/assets/contact-bg.jpg
- `assets/favicon.ico` ← 20141224114543 http://nevcan.com/assets/favicon.ico
- `assets/header-bg.jpg` ← 20150124062507 http://nevcan.com/assets/header-bg.jpg
- `assets/loader.gif` ← 20150124075410 http://nevcan.com/assets/loader.gif
- `assets/logo.png` ← 20150124061413 http://nevcan.com/assets/logo.png
- `assets/projects/company-logo.png` ← 20141224153105 http://nevcan.com/assets/projects/company-logo.png
- `assets/projects/project-thumb-birayakkabi.png` ← 20141224104223 http://nevcan.com/assets/projects/project-thumb-birayakkabi.png
- `assets/projects/project-thumb-bonmed.png` ← 20140521094904 http://nevcan.com/assets/projects/project-thumb-bonmed.png
- `assets/projects/project-thumb-buba.png` ← 20141224115203 http://nevcan.com/assets/projects/project-thumb-buba.png
- `assets/projects/project-thumb-carrolboyes.png` ← 20141224153133 http://nevcan.com/assets/projects/project-thumb-carrolboyes.png
- `assets/projects/project-thumb-divebook.png` ← 20141224132623 http://nevcan.com/assets/projects/project-thumb-divebook.png
- `assets/projects/project-thumb-erdemkinay.png` ← 20141224113659 http://nevcan.com/assets/projects/project-thumb-erdemkinay.png
- `assets/projects/project-thumb-invent.png` ← 20141224095819 http://nevcan.com/assets/projects/project-thumb-invent.png
- `assets/projects/project-thumb-kapory.png` ← 20141224095607 http://nevcan.com/assets/projects/project-thumb-kapory.png
- `assets/projects/project-thumb-omu.png` ← 20141224114441 http://nevcan.com/assets/projects/project-thumb-omu.png
- `assets/projects/project-thumb-pinekleme.png` ← 20141224102435 http://nevcan.com/assets/projects/project-thumb-pinekleme.png
- `assets/projects/project-thumb-spalife.png` ← 20141224103231 http://nevcan.com/assets/projects/project-thumb-spalife.png
- `assets/projects/project-thumb-vacstudio.png` ← 20141224121809 http://nevcan.com/assets/projects/project-thumb-vacstudio.png
- `css/bootstrap.min.css` ← 20141224124246 http://nevcan.com/css/bootstrap.min.css
- `css/designr-theme-cyan.css` ← 20141224092843 http://nevcan.com/css/designr-theme-cyan.css
- `css/flexslider.css` ← 20141224111937 http://nevcan.com/css/flexslider.css
- `css/font-awesome.css` ← 20141224102358 http://nevcan.com/css/font-awesome.css
- `dalgic/color-picker/colpick.css` ← 20150827023918 http://nevcan.com/dalgic/color-picker/colpick.css
- `dalgic/color-picker/colpick.min.js` ← 20150827023920 http://nevcan.com/dalgic/color-picker/colpick.min.js
- `dalgic/css/style_l.css` ← 20150827023918 http://nevcan.com/dalgic/css/style_l.css
- `dalgic/css/user_config.css` ← 20150827023918 http://nevcan.com/dalgic/css/user_config.css
- `dalgic/font/iconfont.woff` ← 20150827023920 http://nevcan.com/dalgic/font/iconfont.woff
- `dalgic/images/logos/cmas.png` ← 20150827023925 http://nevcan.com/dalgic/images/logos/cmas.png
- `dalgic/images/logos/efr.png` ← 20150827023926 http://nevcan.com/dalgic/images/logos/efr.png
- `dalgic/images/logos/gue.png` ← 20150827023925 http://nevcan.com/dalgic/images/logos/gue.png
- `dalgic/images/logos/ils.png` ← 20150827023925 http://nevcan.com/dalgic/images/logos/ils.png
- `dalgic/images/logos/protec.png` ← 20150827023925 http://nevcan.com/dalgic/images/logos/protec.png
- `dalgic/images/logos/ssi-freediving.png` ← 20150827023926 http://nevcan.com/dalgic/images/logos/ssi-freediving.png
- `dalgic/images/logos/tssf.png` ← 20150827023925 http://nevcan.com/dalgic/images/logos/tssf.png
- `dalgic/images/logos/utd.png` ← 20150827023926 http://nevcan.com/dalgic/images/logos/utd.png
- `dalgic/images/portrait-gue.png` ← 20150827023922 http://nevcan.com/dalgic/images/portrait-gue.png
- `dalgic/images/sea.jpg` ← 20150827023922 http://nevcan.com/dalgic/images/sea.jpg
- `dalgic/images/sertifikalar/01.png` ← 20150827023926 http://nevcan.com/dalgic/images/sertifikalar/01.png
- `dalgic/images/sertifikalar/02.png` ← 20150827023927 http://nevcan.com/dalgic/images/sertifikalar/02.png
- `dalgic/images/sertifikalar/03.png` ← 20150827023936 http://nevcan.com/dalgic/images/sertifikalar/03.png
- `dalgic/images/sertifikalar/04.png` ← 20150827023927 http://nevcan.com/dalgic/images/sertifikalar/04.png
- `dalgic/images/sertifikalar/05.png` ← 20150827023932 http://nevcan.com/dalgic/images/sertifikalar/05.png
- `dalgic/images/sertifikalar/06.png` ← 20150827023929 http://nevcan.com/dalgic/images/sertifikalar/06.png
- `dalgic/images/sertifikalar/freediving1.jpg` ← 20150827023929 http://nevcan.com/dalgic/images/sertifikalar/freediving1.jpg
- `dalgic/images/sertifikalar/ssi_freediving1.png` ← 20150827023928 http://nevcan.com/dalgic/images/sertifikalar/ssi_freediving1.png
- `dalgic/images/sertifikalar/tssf_1egitmen.png` ← 20150827023926 http://nevcan.com/dalgic/images/sertifikalar/tssf_1egitmen.png
- `dalgic/images/sertifikalar/tssf_rehber.png` ← 20150827023926 http://nevcan.com/dalgic/images/sertifikalar/tssf_rehber.png
- `dalgic/images/sertifikalar/tssf_uzmanliklar.png` ← 20150827023927 http://nevcan.com/dalgic/images/sertifikalar/tssf_uzmanliklar.png
- `dalgic/index.html` ← 20150827023917 http://nevcan.com/dalgic/
- `dalgic/js/contact.js` ← 20150827023920 http://nevcan.com/dalgic/js/contact.js
- `dalgic/js/custom.js` ← 20150827023919 http://nevcan.com/dalgic/js/custom.js
- `dalgic/js/jquery.min.js` ← 20150827023919 http://nevcan.com/dalgic/js/jquery.min.js
- `dalgic/js/maplace.min.js` ← 20150827023919 http://nevcan.com/dalgic/js/maplace.min.js
- `dalgic/js/modernizr.min.js` ← 20150827023919 http://nevcan.com/dalgic/js/modernizr.min.js
- `dalgic/js/user_config.js` ← 20150827023919 http://nevcan.com/dalgic/js/user_config.js
- `font/fontawesome-webfont.eot` ← 20150124100104 http://nevcan.com/font/fontawesome-webfont.eot
- `font/fontawesome-webfont.svg` ← 20150124104019 http://nevcan.com/font/fontawesome-webfont.svg
- `font/fontawesome-webfont.ttf` ← 20150124105119 http://nevcan.com/font/fontawesome-webfont.ttf?v=3.2.1
- `font/fontawesome-webfont.woff` ← 20150124085032 http://nevcan.com/font/fontawesome-webfont.woff?v=3.2.1
- `index.html` ← 20141218044318 http://nevcan.com/
- `js/contact.js` ← 20141224114722 http://nevcan.com/js/contact.js
- `js/designr.js` ← 20141224131739 http://nevcan.com/js/designr.js
- `js/jquery.easypiechart.js` ← 20141224125159 http://nevcan.com/js/jquery.easypiechart.js
- `js/jquery.flexslider.min.js` ← 20141224125115 http://nevcan.com/js/jquery.flexslider.min.js
- `js/jquery.masonry.min.js` ← 20141224100955 http://nevcan.com/js/jquery.masonry.min.js
- `js/jquery.scrollto.js` ← 20141224092752 http://nevcan.com/js/jquery.scrollto.js
- `js/libs/bootstrap.min.js` ← 20140521092829 http://nevcan.com/js/libs/bootstrap.min.js
- `js/libs/modernizr.min.js` ← 20140521091839 http://nevcan.com/js/libs/modernizr.min.js
- `js/respond.min.js` ← 20141224101744 http://nevcan.com/js/respond.min.js
- `js/twitterFetcher_v10_min.js` ← 20141224110816 http://nevcan.com/js/twitterFetcher_v10_min.js
- `js/waypoints.min.js` ← 20141224120420 http://nevcan.com/js/waypoints.min.js
- `robots.txt` ← 20140521105300 http://nevcan.com/robots.txt
