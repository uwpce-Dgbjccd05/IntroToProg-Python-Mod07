## Welcome to My GitHub Page

Glenn B. Dacones  
May 24, 2022  
Foundation of Programming: Python  
Assignment 07  
[My Github Repository](https://github.com/uwpce-Dgbjccd05/IntroToProg-Python-Mod07)

<br/>
<h3 align = "center">Exception Handling & Pickling</h3>
<br/>

#### Introduction

This paper is a continuation of the to do list script from Assignment 05. In this assignment, using the template provided, I will create and execute a script using functions that are already pre-defined in the template. The codes that I have added are the text following the “TODO: Add Code Here!” comment in the template.

How to Save Data to a File
In this step of the script, the data is saved using the predefined function in the template. As mentioned earlier, the codes I have added are the text below the comment, “TODO: Add Code Here!” (Figure 6).
def write_data_to_file(file_name, list_of_rows):
    """ Writes data from a list of dictionary rows to a File

    :param file_name: (string) with name of file:
    :param list_of_rows: (list) you want filled with file data:
    :return: (list) of dictionary rows
    """
    # TODO: Add Code Here!
    file_obj = open(file_name, "w")
    for row in table_lst:
        file_obj.write(row["Task"] + "," + row["Priority"] + "\n")
    file_obj.close()
    return list_of_rows
Figure 6. An example of a function saving data to a file.
How to Exit the Program
In  this step of the script, the code has already been provided in template.
Below shows the script running in the command shell (Figure 7).
#### Exception Handling


#### Pickling
 
Figure 7.  A screenshot of the script running in the command shell.

Below shows the script running in PyCharm (Figure 8).

 
Figure 8.  A screenshot of the script running in PyCharm.

Below shows the tasks and priorities written to the ToDoList.text file (Figure 9).
 
Figure 9. Verifying that the file has data.
Summary
In this assignment, I was able to complete the assigned tasks. Using the provided template with predefined functions, it was confusing at first because the functions were divided  into two classes, 1) the processor, 2) the input and output. Also modifying an existing script is much harder than creating a new one. Nonetheless, with perseverance, I successfully completed this assignment.


You can use the [editor on GitHub](https://github.com/uwpce-Dgbjccd05/IntroToProg-Python-Mod07/edit/main/README.md) to maintain and preview the content for your website in Markdown files.

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

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/uwpce-Dgbjccd05/IntroToProg-Python-Mod07/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
