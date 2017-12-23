# cs-haifa-website
[This is](http://cs-haifa.wzmn.net/) a static mirror copy of the students website of the computer science department in Haifa university.

The original website was originally hosted on [http://cs.haifa.ac.il/students](http://cs.haifa.ac.il/students), but was taken off around 2015.
It was created on December 13, 2006 and was based on an [earlier version](http://cs-haifa.wzmn.net/v1) created on April 19, 2005.

Steps taken to create this copy -
1. Hosted a live copy of the website locally.
2. Generated a static copy with [wget](https://www.gnu.org/software/wget/) using
`wget --mirror --page-requisites --convert-links -E --wait=0 --tries=1 --waitretry=0 --progress=dot http://localhost/students/`
3. Converted files and db tables encoding to utf-8

Also, the forums were dropped for now.

