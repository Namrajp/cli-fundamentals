#Sed command is used to edit text files, according to `info sed` page,'sed' is a stream editor.  A stream editor is used to perform basic text

The following commands are
equivalent:

    ```bash
     sed 's/hello/world/' input.txt > output.txt
     sed 's/hello/world/' < input.txt > output.txt
     cat input.txt | sed 's/hello/world/' - > output.txt
     ```

-g flag means global, -i means in place if editing a file, i means edit in place. 

[Cli fundamentals](https://github.com/Namrajp/cli-fundamentals)
