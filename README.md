This is a responsive Jekyll theme using Bootstrap.  It uses a collection named `webpages`.  The documents in the collection are displayed as pages.  Set `title` variable in front matter of a document for the page name.  If you want to display an image with a page, set `image_url` variable in front matter to the URL of the image.  Please feel free to modify this theme to suit your own needs.

If you like to use this theme with GitHub Pages, download the theme from [Jekyll Theme Collection](https://emrickj.github.io/jekyll-themes) and use it as a page layout in the `_layouts` directory, or you can simply fork this repository and add and modify the contents in it.  Please visit [https://jekyllrb.com/docs/collections/](https://jekyllrb.com/docs/collections/) for information on how to set up a collection.  It is also a good idea to flatten the first page (pull it out of the `webpages` subfolder) when your site builds so that your site can be accessed without having to specify additional directories or filenames in the URL.  You do this by adding `permalink: index.html` to the front matter of the first page.
