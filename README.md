# Markdown CSS for Droplr

This is the CSS for styling [Markdown](http://daringfireball.net/projects/markdown/) drops in [Droplr](http://droplr.com).

Take a look at a [live drop page](http://d.pr/n/1ltOk) or the [demo page](http://nrbernard.com/droplr-markdown-css/) you can view locally.

## Usage

The stylesheet is written in [SASS](http://sass-lang.com/), but generating a new CSS file is simple. Assuming you already have [Ruby](https://www.ruby-lang.org/en/) installed, first install the Sass gem:

`gem install sass`

Then, after you've cloned this repository, `cd` into the directory and run Sass to convert `markdown.sass`:

`sass markdown.sass markdown.css`

Now, you can open `index.html` in your browser and see the updated styles.

To use the stylesheet in your own project, just add a `markdown` class to the container of your rendered Markdown.

Read the [Sass documentation](http://sass-lang.com/documentation/file.SASS_REFERENCE.html#using_sass) for other ways of working with Sass.

## Contribute

Go wild. Edit and add to the Sass file or demo page and submit a pull request. All updates will be reflected in Droplr's production [Markdown drop pages](http://d.pr/n/1ltOk).

## License

[MIT](https://github.com/nrbernard/droplr-markdown-css/blob/master/LICENSE)
