# [Example 1](test1.qmd): Using pointblank output

In the rendered HTML, the markdown formatting does not get pushed into HTML formatting:
![image](https://github.com/user-attachments/assets/3a1ce725-3795-4a70-a41c-f511ccc2a5a2)

# [Example 2](test2.qmd): Using pointblank output with `gt::fmt_markdown()`

After passing the output GT table to `fmt_markdown()`, the markdown formatting is now fixed. However, duplicates of some rows are displayed:
![image](https://github.com/user-attachments/assets/ca1fd1a8-647e-4261-a6a2-9ed0d9279fcb)

# [Example 3](test3.qmd): Using pointblank output with `gt::fmt_markdown()` & `html-table-processing: none` Quarto HTML formatting option

After passing the output GT table to `fmt_markdown()`, while using the `html-table-processing: none` formatting option, the markdown formatting is now fixed along with the duplicates.
![image](https://github.com/user-attachments/assets/ad0ea80c-8881-4437-9b3b-52e0427ce727)


