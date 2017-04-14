Шаблоны для R Markdown от Стивена Миллера (с минимальными изменениями для поддержки русского языка)
============================

Репозиторий содержит шаблоны, позволяющие создавать HTML и PDF версии разных академических текстов из документов .Rmd в RStudio. Единственное отличие от оригинального [репозитория](https://github.com/svmiller/svm-r-markdown-templates) Стивена Миллера - добавление в заголовок .Rmd документов ссылки на библиотеку, позволяющую отрисовывать в PDF кириллические буквы, а также правка ссылок на tex-шаблоны, поэтому достаточно открыть Rmd-документ в RStudio, нажать "Knit PDF" и вы сразу получите на выходе PDF-файл.

Единственный нерабочий шаблон - силлабус (программа учебного курса) по причине большого количества зависимостей от файлов данных и сторонних библиотек.

Для использования желательно установить [MiKTeX](https://miktex.org/) или [TeXLive](https://www.tug.org/texlive/).
Также не забудьте установить все библиотеки для R, используемые в шаблонах, иначе конвертация закончится с ошибкой.

Алексей Кнорре


I love R Markdown and effectively abandoned LaTeX for it. I have a suite of R Markdown templates for 1) academic manuscripts, 2) Beamer presentations, and 3) academic syllabi. You can find them here.
 
## Related Reading

- [Automatically Do (Just About) Everything in Your Syllabus with R Markdown](http://svmiller.com/blog/2016/07/r-markdown-syllabus/)
- [Make Your Academic CV Look Pretty in R Markdown](http://svmiller.com/blog/2016/03/svm-r-markdown-cv/)
- [An R Markdown Template for Academic Manuscripts](http://svmiller.com/blog/2016/02/svm-r-markdown-manuscript/)
- [Moving from Beamer to R Markdown](http://svmiller.com/blog/2015/02/moving-from-beamer-to-r-markdown/) (see Github repo for current theme/tweaks)

