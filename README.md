Opencart Auto Keywords
======================

Auto adding SEO keywords in products, articles and categories.

Installing
--------------------------

Just upload xml file into your vqmod/xml folder. That's all.

How it works
--------------------------

Plugin modified four files: header.tpl, product_form.tpl, category_form.tpl and information_form.tpl.
In the header.tpl will be added JS code for transliterate items name to SEO keyword on english. I use fantastic 
[django-urlify](https://github.com/olebedev/django-urlify) wrapper for this.
Please, check django-urlify docs for additional info.
