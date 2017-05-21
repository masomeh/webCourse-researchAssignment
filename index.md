## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/masomeh/webCourse-researchAssignment/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/masomeh/webCourse-researchAssignment/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.



به نام خدا
تحقیق درس برنامه نویسی وب
معصومه سلیمانی ۹۲۱۰۶۴۶۴
موضوع: Offline First – A better HTML5 User Experience 
 
offline بودن یک برنامه که به معنی اینست که وقتی به اینترنت دسترسی نداریم (برخط نیستیم) نیز بتوانیم از آن استفاده کنیم و پس از اتصال به اینترنت بتوانیم آن را همگام کنیم، یک ویژگی اساسی آن برنامه است که ضروریست از ابتدای نوشتن آن در نظر گرفته شود و در ادامه نیز این قابلیت را پیاده کرد.
برای این کار راهنمایی های زیر می تواند راهگشا باشد:
۱- جدا ساختن برنامه خودمان از سرور: که برای این کار کل کدهای برنامه را به سمت کدهای client یا همان برنامه خودمان می بریم و سرور را به عنوان API یی در نظر می گیریم که منطق زیادی ندارند و سبک است و فقط بعضی مواقع از طریق JSON با آن ارتباط هایی برقرار می کند.
۲- ساخت API wrapper object در سمت سرور: ساختن این شی در سمت کلاینت علاوه بر سمت سرور که یک API دارد و مشابه سمت سرور عمل میکند، باعث می شود که امکان unit test و mock کردن داده هاقبل از آمده شدن سرور فراهم شود.
۳- جدا ساختن به روز رساتی داده ها از انبار (storage) داده: یک proxy object ای را در نظر میگیریم که به عنوان واسط بین API و بقیه برنامه عمل می کند و درخواست ها را میفرستد.

