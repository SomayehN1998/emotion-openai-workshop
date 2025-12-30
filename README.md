<svg width="800" height="120" xmlns="http://www.w3.org/2000/svg">
  <rect width="100%" height="100%" fill="#FF9500"/>
  <text x="50%" y="60%" font-family="Vazir, Tahoma, sans-serif" font-size="35" font-weight="bold" fill="white" text-anchor="middle" direction="rtl">
    طبقه‌بندی احساسات با مدل‌های زبانی بزرگ و دیتاست احساسات
  </text>
</svg>
![Uploading image.png…]()




# طبقه‌بندی احساسات با مدل‌های زبانی بزرگ و دیتاست احساسات
<div dir="rtl">
 
**طبقه‌بندی احساسات توییت‌های انگلیسی** با استفاده از:

- دیتاست `dair-ai/emotion` از HuggingFace  
- مدل‌های خانواده‌ی GPT از طریق **Responses API**  
- استراتژی‌های مختلف پرامپت (Zero-shot، Few-shot، Chain-of-Thought)  
- خروجی ساخت‌یافته با استفاده از **Pydantic** (دو حالت: فقط لیبل / توضیح + لیبل)  
- محاسبه‌ی شاخص‌های کمی مثل **Accuracy، Precision، Recall، F1** برای هر روش

ساختار نوت‌بوک:

0. راه‌اندازی اولیه (نصب، کلید، سلام دنیا)  
1. آشنایی با واسط پاسخ و نقش پیام‌ها  
2. آشنایی با دیتاست احساسات  
3. کار روی یک نمونه (سه استراتژی مختلف پرامپت)  
4. ارزیابی کمی استراتژی‌های پرامپت روی ۱۰۰ نمونه  
5. خروجی ساخت‌یافته با پای‌دان‌تیک (دو مدل) + ارزیابی کمی  

</div>
