sublime-configurations
======================

My Configuration files

## Files Included

* Default (OSX).sublime-keymap
* Preferences.sublime-settings
* standard-comment.sublime-snippet
* coffeescript
  * coffee-method.sublime-snippet
* rails
  * rails-logger.sublime-snippet
  * rails-method.sublime-snippet
* sass
  * bgattr.sublime-snippet

## rails-logger.sublime-snippet
trigger: 'log', tab

produces:
<pre>
  Rails.logger.info "==== label: #{to_log.inspect} ===="
</pre>


## rails-method.sublime-snippet
trigger: 'def', tab

produces:
<pre>
  # Description
  #
  # ==== Parameters:
  # param:: Class
  #
  # ==== Returns:
  # returns
  def method_name arguments
    # code here
  end
</pre>


## bgattr.sublime-snippet
trigger: 'bgattr', tab

produces:
<pre>
  background-image: url(/images/*.png);
  background-repeat: no-repeat;
  background-position: center center;
</pre>

## standard-comment.sublime-snippet
trigger: 'comment', tab

works with:

* PHP
* JavaScript
* ActionScript
* JAVA

produces:
<pre>
  /* Description
   *
   * ==== Parameters:
   * param:: Class
   *
   * ==== Returns:
   */ returns
</pre>

## coffee-method.sublime-snippet
trigger: 'c-', tab

produces:
<pre>
  # Description
  #
  # ==== Parameters:
  # param:: Class
  #
  # ==== Returns:
  # returns
  method_name = (arguments) ->
    # code here
</pre>

## Packages

* Alignment
* Better CoffeeScript
* BufferScroll
* CJSX Syntax
* Emmet
* File Rename
* JSX
* MarkdownEditing
* MarkdownPreview
* Pretty JSON
* Rails Migration List
* Sass
* Vintage Surround
