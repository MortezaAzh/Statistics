تمرین
تابع survival_chance را طوری تکمیل کنید که با گرفتن داده‌ی تایتانیک و یک بازه‌ی سنی (شامل سن ابتدا و انتهای بازه)، شانس زنده ماندن در آن بازه را به ازای جنسیت مرد و زن، به صورت یک دیکشنری گزارش کند. (تنها برای مسافرانی که عدد سن برای آن‌ها وجود دارد). سپس آن را در فایل functions.py اضافه کنید.

𝐴𝑔𝑒𝑠𝑡𝑎𝑟𝑡⩽𝐴𝑔𝑒⩽𝐴𝑔𝑒𝑒𝑛𝑑
در صورتی که در بازه‌ی داده شده، از یکی از (یا هردوی) جنسیت‌ها نمونه‌ای وجود نداشته‌ باشد، در خروجی برای آن جنسیت مقدار -1 در نظر بگیرید.
شانس زنده ماندن را تا ۳ رقم اعشار گرد کنید.
دیکشنری خروجی به شکل زیر خواهد بود.
{
  "male":chace_for_males,
  "female":chance_for_females
}
برای داشتن لیست اطلاعات ستون‌های مورد نظر می‌توانید خطوط کامنت شده در کد زیر را از حالت کامنت خارج کرده و بدون نیاز به دانش استفاده از لایبرری پانداس به حل سوال بپردازید