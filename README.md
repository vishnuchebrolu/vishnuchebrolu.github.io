# vishnuchebrolu.github.io

1. kernel-doc is use to generate .rst file from source code
2. sphinx can translate .rst file to .html file.

3. Then github provide you some method to publish your .html file
4. maybe we need to file a tool which could translate .md to html

5. for github, you have 3 ways to publish your document
    master branch, master/docs, and gh-pages branch(best)
6. add index.html and .jekyll to the gh-pages branch.. then try github.io.. see if you can access index.html
7. after that, you need a doc/ directory in your master branch and a script to call sphinx to generate your website
8. then an other script to publish the website generate by Sphinx to gh-pages
