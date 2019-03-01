# persian-dataset
This data set is collected by crawling the Young Journalist Club website(https://www.yjc.ir/) . This dataset has the following 9 categories:

1. Artistic culture
2. Communication
3. Thecnology
4. Economical
5. International(Political)
6. Political
7. Scientific and Medical
8. Social
9. Sport 

The data for each category is stored in files corresponding to the category name. Each line of the file contains the information of a news item such as text, category, date , ... . The format of each news as following:

```json
{
  "link": "/fa/news/6819277/آشنایی-با-مرتضی-علی-احمدی-شهید-حادثه-تروریستی-امروز-در-سیستان-و-بلوچستان\n",
  "title": "آشنایی با مرتضی علی احمدی شهید حادثه تروریستی امروز در سیستان و بلوچستان",
  "code_news": "کد خبر: ۶۸۱۹۲۷۷",
  "category": "سیاسی",
  "date": "تاریخ انتشار: ۱۳ بهمن ۱۳۹۷ - ۱۶:۴۴",
  "text": " به گزارش حوزه امنیتی دفاعی گروه سیاسی باشگاه خبرنگاران جوان به نقل از عصر هامون، شهید مرتضی علی احمدی در تیرماه ۱۳۹۵ به عنوان مسئول سازمان فضای مجازی بسیج شهرستان نیکشهر معرفی شد و مدت ٦ ماه با قرارگاه فضای مجازی بسیج استان سیستان و بلوچستان همکاری داشت. او در سال ۹۶ مسئولیت شباب این ناحیه را بر عهده گرفت و پس از آن به مجموعه فاوا پیوست. گفتنی است، این شهید بزرگوار متولد ۱۳۷۲ در زاهدان بود."
}
```
Download link for data is stored in `data.txt` file.

