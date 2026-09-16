# پنل نئون (NEON X PANEL)

<p align="center">
  <img src="./media/3x-ui-dark.png" alt="NEON X PANEL" width="100%">
</p>

<p align="center">
  <a href="https://github.com/ksgamer12/NEON-X-PANEL/releases"><img src="https://img.shields.io/github/v/release/ksgamer12/NEON-X-PANEL?color=a855f7&label=NEON%20RELEASE" alt="Release"></a>
  <a href="https://github.com/ksgamer12/NEON-X-PANEL/actions"><img src="https://img.shields.io/github/actions/workflow/status/ksgamer12/NEON-X-PANEL/release.yml.svg" alt="Build"></a>
  <a href="https://github.com/ksgamer12/NEON-X-PANEL/releases/latest"><img src="https://img.shields.io/github/downloads/ksgamer12/NEON-X-PANEL/total.svg" alt="Downloads"></a>
  <a href="https://www.gnu.org/licenses/gpl-3.0.en.html"><img src="https://img.shields.io/badge/license-GPL%20V3-purple.svg" alt="License"></a>
</p>

**نئون‌پنل (NEON X PANEL)** یک کنترل‌پنل پیشرفته، مستقل و بهینه‌سازی‌شده برای مدیریت سرورهای [Xray-core](https://github.com/XTLS/Xray-core) است. این پنل با تم جذاب **تیره نئون بنفش**، سیستم قدرتمند **چندادمین با نقش‌بندی RBAC** و همگام‌سازی فوق‌العاده سریع نودها توسعه یافته است.

---

## ⚡ قابلیت‌های انحصاری نئون

۱. **تم و برندینگ اختصاصی نئون**
   - صفحه لاگین با گرادیان نئونی بنفش/سیان (`LoginPage.css`) و استایل سراسری نئون (`neon-panel.css`).
   - انیمیشن‌های درخشان (Shine) روی آیتم‌های سایدبار و پشتیبانی کامل از منوی همبرگری کشویی در تمامی صفحات ادمین.

۲. **مدیریت چندادمین و RBAC (کنترل دسترسی مبتنی بر نقش)**
   - مدیریت کامل ادمین‌ها (`AdminsPage`) و نقش‌ها (`AdminRolesPage`).
   - تفکیک کامل مشتریان هر ادمین (هر ادمین فقط مشتریان ساخته‌شده توسط خودش را می‌بیند: `CreatedBy == self`).
   - نقش‌های پیش‌فرض آماده با ساختار تمیز و واکنش‌گرا.

۳. **پچ زرد آپدیت و ریلیزهای پایدار خودکار**
   - اعلان خودکار در پنل هنگام انتشار نسخه پایدار جدید (`latest` غیر pre-release) روی گیت‌هاب.
   - ساخت خودکار ۱۶ باینری برای معماری‌های مختلف در هر انتشار ریلیز.

۴. **بهبودهای هسته 3.8.5**
   - اصلاحات AmneziaWG (پورت‌های رلی و فوروارد پیر).
   - همگام‌سازی پرسرعت نودها (تا ۳۲ نود همزمان) با مصرف حافظه کمتر.
   - ارتقای امنیت URLهای اشتراک (Subscription) و سازمان‌دهی داکس API.

---

## 🚀 نصب تک‌خطی

```bash
bash <(curl -Ls https://raw.githubusercontent.com/ksgamer12/NEON-X-PANEL/main/install.sh)
```

---

## 🛠️ راهنمای بخش ادمین و RBAC

- **مدیریت ادمین‌ها**: در سایدبار پنل به بخش **Admins** بروید تا ادمین جدید بسازید، نقش به او اختصاص دهید و دسترسی‌ها را محدود کنید.
- **نقش‌های ادمین**: از طریق **Admin Roles** می‌توانید سطح دسترسی‌ها (مشاهده، ویرایش، ساخت کلاینت و آمار) را سفارشی‌سازی کنید.

---

## 📄 لایسنس

GPL-3.0 License © 2026 Neon X Panel Team.
