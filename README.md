# html.tag


# نمونه تگ‌های HTML و کاربرد آنها

| توضیح | کد HTML |
|-------|---------|
| تگ `<h1>` به عنوان تیتر بالای صفحه برای شروع یک پاراگراف به‌کار می‌رود. | `<h1>عنوان اول</h1>` |
| تگ‌های `<h2>` تا `<h6>` برای سرفصل‌های کوچک‌تر | `<h2>عنوان دوم</h2><br/><h3>عنوان سوم</h3><br/><h4>عنوان چهارم</h4><br/><h5>عنوان پنجم</h5><br/><h6>عنوان ششم</h6>` |
| تگ `<p>` برای ایجاد پاراگراف استفاده می‌شود. | `<p>این یک پاراگراف نمونه است.</p>` |
| تگ `<br>` برای رفتن به خط بعد و `<hr>` برای خط افقی | `متن اول<br>متن دوم<br><hr>` |
| تگ `<a>` برای لینک | `<a href="https://example.com">انتقال به سایت</a>` |
| لیست مرتب و نامرتب | `<ol type="I"><li>آیتم 1</li><li>آیتم 2</li></ol><br/><ul type="square"><li>آیتم 1</li><li>آیتم 2</li></ul>` |
| تگ `<div>` برای گروه‌بندی محتوا | `<div>محتوا</div>` |
| تگ `<img>` برای درج تصویر | `<img src="image.jpg" alt="توضیح تصویر" width="500" height="300">` |
| تگ `<video>` برای نمایش ویدیو | `<video controls width="600"><source src="movie.mp4" type="video/mp4"><track src="subtitles_en.vtt" kind="subtitles" srclang="en" label="English"></video>` |
| تگ `<audio>` برای پخش صدا | `<audio controls src="audio.mp3">صدای شما پخش نشد</audio>` |
| لیست تعریفی: `<dl>`, `<dt>`, `<dd>` | `<dl><dt>HTML</dt><dd>زبان نشانه‌گذاری صفحات وب</dd></dl>` |
| ورودی متنی: `<input>` | `<input type="text" placeholder="متن ورودی">` |
| ورودی چندخطی: `<textarea>` | `<textarea rows="4" cols="50">متن اولیه</textarea>` |
| دکمه: `<button>` | `<button type="submit">ارسال</button>` |
| منوی کشویی: `<select>` | `<select><option value="1">گزینه ۱</option></select>` |
| گروه‌بندی ورودی‌ها: `<fieldset>`, `<legend>` | `<fieldset><legend>عنوان گروه</legend><input type="text"></fieldset>` |
| برچسب ورودی: `<label>` | `<label for="id1">نام:</label><input id="id1" type="text">` |
| لیست پیشنهادها: `<datalist>` | `<input list="browsers"><datalist id="browsers"><option value="Chrome"></datalist>` |
| فرم ارسال: `<form>` | `<form action="submit.php" method="post"><input type="text"><button type="submit">ارسال</button></form>` |
| جدول ساده: `<table>`, `<tr>`, `<td>`, `<th>` | `<table><tr><th>عنوان</th></tr><tr><td>داده</td></tr></table>` |
| سلول‌های ادغام‌شده: `colspan`, `rowspan` | `<table border="1"><tr><td rowspan="2">سلول rowspan</td><td>سلول معمولی</td></tr><tr><td colspan="2">سلول colspan</td></tr></table>` |
| ساختار جدول: `<caption>`, `<thead>`, `<tbody>`, `<tfoot>` | `<table><caption>عنوان جدول</caption><thead><tr><th>عنوان</th></tr></thead><tbody><tr><td>داده</td></tr></tbody><tfoot><tr><td>پاورقی</td></tr></tfoot></table>` |
