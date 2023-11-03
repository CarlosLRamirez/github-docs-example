# Writing Good Documentation

GitHub Flavored Markdown (GFM)[^1] is a variant of the Markdown markup language designed for use on the GitHub platform. Markdown is a lightweight and easy-to-read plain text format that allows you to format text using a simple and intuitive syntax[^2] . 

You can use GFM to write a good documentation for your software projects or any type of projects.

## Step 1 - Using Codeblocks.

Codeblocks in mardkdown allow us to **copy, plaste and share core**. A goog Cloud Engineer uses Codeblocks whenever possible.

Because it allows others to copy and paste their code to replicate or research issues.

- In order to create codeblocks in markdown you need to use three backticks (`), you can find it [here](/assets/IMG_3019.jpg) in the keyboard, also [here](/assets/IMG_3020.jpg)
- Not to be confused with quotation (')

```
#include <iostream>

int main() {
    std::cout << "Hello, World!" << std::endl;
    return 0;
}
```

- When you can you should attempt to apply syntax highlighting to your codeblocks

```go
#include <iostream>

int main() {
    std::cout << "Hello, World!" << std::endl;
    return 0;
}
```

- Make note of where the backtick keyboard key is located
- It should appear above the tab key, but it may vary based on your keyboard:

- This is an example for a Spanish Windows Keyboard 

![Backticks key in Windows Keyboard](/assets/IMG_3019.jpg "Backticks key in Windows Keyboard")

- This is an example for a English Macbook Keyboard

![Backticks key in Windows Keyboard](/assets/IMG_3020.jpg "Backticks key in Windows Keyboard")

Good Cloud Engineers use codebocks for both Code and Errors that appear in the console.

```bash
Hello, World
panic: runtime error: integer divide by zero

goroutine 1 [running]:
main.main()
        /path/to/your/go/file.go:8 +0x44
exit status 2
```

> Here is an example of using a codeblock for an error that appears in bash

When you can always provide a codeblock instead of a screenshot.

If you need to take a screenshot make sure is not a photo from you phone

> There are certain cases where its okay to take photo with your phone, This is when you are showing something like a keyboard, which dows not appear on a computer screen. If it render on your computer screen it should be a screenshot.

## Step 2 - How to take screenshots

- A screenshot is when you capture a part of your screen from your laptop, desktop or phone.
- This is not to be confused with take a photo with your phone.

**DON'T DO THIS**

![A photo with your phone](/assets/phone_photo.jpg)

**DO THIS INSTEAD**

![A proper screenshoot](/assets/Screenshot.jpg)

## Step 3 - Use Github Flavored Markdown Task Lists

Github extends Markdown to have a list where you can check off items[^3].

- [x] Finish Step 1
- [ ] Finish Step 2
- [ ] Finish Step 3

## Step 4 - Use Emojis (Optional)

GitHub Flavored Markdown supports emoji shurtcuts[^4]. Here are some examples:

| Name | Shortcut | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | :cloud: |
| Cloud with Lightning | `:cloud_with_lightning:` | :cloud_with_lightning: |
| Fire | `:fire:` | :fire: |

## Step 5 - How to Create a Table

You can use the following markdown format to create table:

```md
| Name | Shortcut | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | :cloud: |
| Cloud with Lightning | `:cloud_with_lightning:` | :cloud_with_lightning: |
| Fire | `:fire:` | :fire: |
```

Github extends the functionality of Markdown tables to provide more alignment and table cell formatting options [^5]:

- Make note of where the pipe keyboard key is located
- It should appear above the return or enter key , but it may vary based on your keyboard:

![Keyboard Key](/assets/IMG_3263.jpg)

## External References

[^1]: [GitHub Flavored Markdown Spec](https://github.github.com/gfm/)

[^2]: [Basic writing and formatting syntax (Github Flavored Markdown)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

[^3]: [GFM - Task List](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists)

[^4]: [GFM - Emoji CheatSheet](https://github.com/ikatyang/emoji-cheat-sheet)

[^5]: [GFM - Tables (with extensions)](https://github.github.com/gfm/#tables-extension-)