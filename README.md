# kasakun

Personal website of myself. We will have blogs, bookstore, demo, photo, etc.
The site is available: http://czy-kasakun.com

For the blog part, articles on this site is different with blog.czy-kasakun.com
which are diary or words besides coding rather than pure technical review. Yes,
this site is designed for life and experience.

Currently I am not going to merge these two sites. This sounds wired but I will
try to find a better way to fix it.

## About static resource

All the static resource is stored at http://static.czy-kasakun.com/kasakun
The reason is that I feel really painful to apply Django's static setting.
Now all the resources are collected and deployed at the cloud.

The static directory in each app is just for local test.

## TO DO

1. ~~Tag System.~~ **Done**
2. ~~The style. I admit the template is good. But I am really tired to with 
the scalability. Yes, they are awful. And I decide to use bootswatch.
Design the site myself.~~ **Done**
3. Other site info : if not complete, should show "not complete".
4. ~~About me~~ **Done**
5. ~~Deploy with only blog version~~ **Done**
6. Book: No plan recently to do the categories. The first thing is to make
the cards view to show the pic and description.
7. Besides Book, other part can use the same structure of the Book?
Maybe Game need categories
8. Tiny fix: clear the non-related link on the page.
9. Add ssl
10. Multi-Language support.
11. Instagram support: Sync with my instagram's posts.

## Config

### pip Packkage

```
sudo pip3 install Django
sudo pip3 install markdown2
```

### MySQL setting

## Bugs

00000001 ~~Markdown cannot use h1 header.~~  **Fixed**

00000002 If items are not enough the pagination will go wrong.
(i.e. 4 pages items, click page 5 will route to a wrong page.)
*Actually I am not sure I should fix it since the pages will grow and cover it*

00000002 ~~Time Zone error.~~  **Fixed**

00000003 ~~Admin change charset utf8 error.~~  **Fixed**