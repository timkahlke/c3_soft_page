# How to collaborate.

- Clone the repo (`git clone https://github.com/uts-c3/c3_soft_page`)
- Make the changes you want (Usually create a new md file in the portfolio folder)
- Make a pull reques.

Some usefull links:

- Page made with [hugo](https://gohugo.io/)
- Markdown format [cheatsheet] (https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)


# How to update the site:


- Use hugo to generate the new `Public` folder (`hugo -t academic`)

and then:

```bash
cd public
git add .
git commit -m "Update the page"
git push
```

Then tell your main project to track the updated version:

```bash
cd ..
git add .
git commit -m "updated my submodule"
git push
```
