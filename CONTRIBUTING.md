## Writing a blog post for LambdaLadies.com

The Lambda Ladies website is hosted on GitHub pages and the source is on [GitHub](https://github.com/lambdaladies/lambdaladies.github.io).

To add a blog post, you will need to add a markdown file to the website source. To do this, you should [fork this repository](https://help.github.com/articles/fork-a-repo/) and send a pull request with your changes.

Once you have forked the repo and cloned it to your local machine, you are ready to add some new content. 

### Check Out Branch

The site source is on a branch called `source`. Make sure you have the correct branch checked out:

    git checkout source

### Adding Markdown

The source for the site's blog posts is in the `_posts` directory. 

You need to add a file in this directory with the same format as the others there, with the date you want on the post forming part of the filename (YYYY-MM-DD). It's easiest just to copy and modify one of the existing ones.

### Adding Metadata

Update the metadata at the top of your blog post, giving it a title and the same date that you put in the filename. Add some tags if you like, and write a short excerpt.

Fill out the author section with the details you would like presented. You can omit sections if you wish.

### Adding Author Photo

The author section of the post includes a reference to an image for the author. If you would like to add yours, put the image file in the `images` directory in the repository. Please keep it low resolution with a reasonably small file size. You can reference your image in the metadata section of the blog post with its filename only (no filepath required).

### Add Content

Add the text of your blog post after the `---`. You can use markdown, or snippets of HTML if you need them. Any images you would like to include should be added to the `images` directory as explained in the previous section. Please take care to avoid unusual characters; keep it to plain text, or use HTML escape characters.

### Build Site (Optional)

If you want to build the site locally to check how your changes look, please follow [these instructions](https://github.com/lambdaladies/lambdaladies.github.io#testing-locally). Don't worry if you are unable to do this; we will check to make sure your post looks right.

### Submit Pull Request

Add and commit your changes the repository and send us a pull request. If everything looks good, we will add your blog post to the site. We may make minor edits for clarity, style, and readability.


