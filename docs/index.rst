Pelican |release|
=================


.. ifconfig:: release.endswith('.dev')

    .. 警告::

        This documentation is for the version of Pelican currently under development.
        Were you looking for version |last_stable| documentation?


Pelican is a static site generator, written in Python_. Highlights include:

* Write your content directly with your editor of choice
  in reStructuredText_ or Markdown_ formats
* Includes a simple CLI tool to (re)generate your site
* Easy to interface with distributed version control systems and web hooks
* Completely static output is easy to host anywhere

迫不及待想要开始使用了吗? Check out the :doc:`Quickstart<quickstart>` guide.

Features
--------

Pelican |version| currently supports:

* Articles (e.g., blog posts) and pages (e.g., "About", "Projects", "Contact")
* Comments, via an external service (Disqus). If you prefer to have more
  control over your comment data, self-hosted comments are another option.
  Check out the `Pelican Plugins`_ repository for more details.
* Theming support (themes are created using Jinja2_ templates)
* Publication of articles in multiple languages
* Atom/RSS feeds
* Code syntax highlighting
* Import from WordPress, Dotclear, or RSS feeds
* Integration with external tools: Twitter, Google Analytics, etc. (optional)
* Fast rebuild times thanks to content caching and selective output writing

为什么命名为 "Pelican"?
-----------------------

"Pelican" is an anagram for *calepin*, which means "notebook" in French. ;)

源代码
-----------

你可以获得源文件从这个网址: https://github.com/getpelican/pelican

如何获取帮助, contribute, or provide feedback
------------------------------------------------

See our :doc:`feedback and contribution submission guidelines <contribute>`.

文档
-------------

.. toctree::
   :maxdepth: 2

   quickstart
   install
   content
   publish
   settings
   themes
   plugins
   pelican-themes
   importer
   faq
   tips
   contribute
   internals
   report
   changelog

.. 连接

.. _Python: http://www.python.org/
.. _reStructuredText: http://docutils.sourceforge.net/rst.html
.. _Markdown: http://daringfireball.net/projects/markdown/
.. _Jinja2: http://jinja.pocoo.org/
.. _`Pelican 文档`: http://docs.getpelican.com/latest/
.. _`Pelican's internals`: http://docs.getpelican.com/en/latest/internals.html
.. _`Pelican 插件`: https://github.com/getpelican/pelican-plugins
