# Travelogue theme for Hugo

A blog theme for Hugo which uses featured images in posts. These are displayed in lists, alternating left and right and at the top of the post on a single page. This creates a clean but fairly image-rich blog, which is particularly suitable for stories from your travels (hence the name of the theme), for reviews or even for things like short stories. I've tried to keep the code clean and well commented, and there are no scripts or tricks so it should be easy to adapt to your needs.

A summary of each blog post will appear on the home page, complete with a featured image if there is one. Posts without a featured image will be displayed in the centre of the home page, while those with images will be presented with the image on the left or right of the summary, alternately.

The home page is paginated and links to older or newer content will appear when required. There is a menu which links to each category of post (best to keep to 2 - 6 categories for this to make sense)

Pages (created in the pages directory in content) will be displayed at the bottom of the home page and any further pages listing posts. This is good for an "about" page, for example.

The styling is in two files. layout.css sets the positioning of the content on the page and in relation to other content while styling.css sets appearance. Two google webfonts are used and this can easily be changed in styling.css (you'll need some search and replace). Css variables are used for colours so these only need to be edited at the top of the styling.css files.

The theme was developed from scratch for my own site at [<http://www.oldmanexploring.com](http://oldmanexploring.com) and is shared under the MIT licence.

Get the theme

From the root of your Hugo site:

$ cd themes
$ git clone https://github.com/hivickylai/hugo-theme-introduction.git introduction
Configure your site

From the exampleSite, copy config.toml to the root folder of your Hugo site and change the fields as you like.

Start with:

Set your baseurl to your site's domain
Set your blog's title and your first name
Set your introduction header height (use "medium", "large", or "fullheight")
Choose "light" or "dark" theme
Set your avatar image
Set your timezone, if you choose to show it
Choose whether or not to show the Blog and Projects sections, and configure them to your liking
Input your social site urls and font-awesome icon names - use as many as you like
Create About and Contact pages


Preview your site locally

Use Hugo's built-in server to see your site in action as you make changes.

$ hugo serve -t introduction
Visit localhost:1313 in your browser to see a live preview of your site.

Blog posts

To create a new blog post, run:

$ hugo new blog/your-post-title.md
Projects

