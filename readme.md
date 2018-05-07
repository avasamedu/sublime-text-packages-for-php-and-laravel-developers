
<div dir="rtl">


# لیست پکیج های مفید برای محیط توسعه ی sublime مخصوص برنامه نویسان پی اچ پی و لاراول

ممکنه محیط توسعه ی شما با اولین نصب خیلی ساده باشه و فایل های پی اچ پی و اچ تی ام ال و ... رو نشناسه و همشون رو به ایکون سفید نشون بده 
یا اینکه کدهای پی اچ پی و یا بلید لاراول و کدهای کلی لاراول و دستورات آرتیسان رو نتونید توی sublime اجرا کنید 
پکیج های زیر را نصب کنید تا مشکلتون حل شود . 

قبل از نصب کردن پکیج های زیر اگه sublime نسخه ی 3 استفاده میکنید کارهای زیر را برای پیاده سازی پکیج منیجر انجام دهید : 
1 مطمئن شوید نسخه ی sublime شما فعال شده باشد 
2 دکمه های ctrl + ` را هم زمان فشار دهید 
3 در پنجره ی باز شده کدهای زیر را کپی و اینتر بزنید : 

import urllib.request,os,hashlib; h = '6f4c264a24d933ce70df5dedcf1dcaee' + 'ebe013ee18cced0ef93d5f746d80ef60'; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); by = urllib.request.urlopen( 'http://packagecontrol.io/' + pf.replace(' ', '%20')).read(); dh = hashlib.sha256(by).hexdigest(); print('Error validating download (got %s instead of %s), please try manual install' % (dh, h)) if dh != h else open(os.path.join( ipp, pf), 'wb' ).write(by)

و بعدش به منوی prefrecens/Browse packages برید در پوشه ای که باز میشه مخزن های گیت هاب زیر را کلون کنید تا آن پکیج برای شما نصب شود . 

لینک مخزن | توضیحات
--- | ---
[API نمایش آیکون](http://packagemanager.com) | ممکنه آیکون فایل های php و  blade و css و .... در محیط شما نمایش داده نشه و نتونید فایل ها رو از هم تفکیک کنید این پکیج مشکل شما رو حل خواهد کرد . 


</div>
