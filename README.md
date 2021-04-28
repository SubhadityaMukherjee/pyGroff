# pyGroff

- A wrapper for groff using python to have a nicer syntax for groff documents
- [DOCUMENTATION](https://subhadityamukherjee.github.io/pyGroff/)
- Very similar to markdown. So if you know what that is. You will love this :)
- We hate word -.-
- Editing pdfs is a pain and please we are lazy
- We love markdown. But we need pdfs and docx. So why not 
- LaTEX is amazing but it is tooo much work for small things.
- Vim is love. What can we do without keyboard shortcuts ):

## What can you do
- Write in a text file
- Get a cover page as well :)
- You can get a word document too (you do need libreoffice for it)
- Get auto generated, beautifully formatted pdfs and docs instantly
- Not cry because you moved an image and now your document is in hieroglyphics
- (You can also write in groff syntax in the file. It will work as well. Just in case you need something extra)


## Syntax
- p runner.py -f "demo.txt" -o "syntax.pdf"  (most basic)
- p runner.py -f "demo.txt" -o "syntax.pdf" -c True -n "Subhaditya Mukherjee" -t "pyGroff" (with cover page)
- Check syntax.pdf and demo.txt for an example
- Refer to syntax.pdf for new, easier syntax :)
- This was also generated by the program hehe

## FAQ
- I dont like the cover page
        - If you know a bit of groff (check the links below), you can use "-d False" and then edit whatever you want using groff itself.
        - Then run "groff -ms {infile} -Tpdf > {outfile}" replacing the infile and outfile respectively.

## Requirements
- Almost every unix system has groff preinstalled
- Which means no windows. (Unless you are using WSL. In which case its coool)
- You need python of course
- If you want to convert to word, you need libreoffice.

## Contribution guidelines
- Can I contribute?
        - YES
- What to do?
        - Check todo.md
- Restrictions?
        - File an issue first, if it looks useful. Go for it
- Spelling mistakes?
        - I mean sure why not xD

## References
- [Markdown syntax](https://www.markdownguide.org/basic-syntax/)
- [My groff tutorial](https://github.com/SubhadityaMukherjee/groffTutorial)
- [More syntax](https://opensource.com/article/18/2/how-format-academic-papers-linux-groff-me)
