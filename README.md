

# Squadra Labs Blog



## Directory explained

``📂_authors``
- Description of all the authors of the blog.

``📂_data``
- Well-formatted site data should be placed here. The Jekyll engine will autoload all data files (using either the ``.yml``, ``.yaml``, ``.json``, ``.csv`` or ``.tsv`` formats and extensions) in this directory, and they will be accessible via `site.data`. If there's a file ``members.yml`` under the directory, then you can access contents of the file through ``site.data.members``.

``📂_drafts``
- Drafts for unpublished posts (Format of these files is without a date)

``📂_includes``
- These are partials elements that can be mixed and matched by your **layouts** to facilitate reuse using the liquid tag ``{% include file.ext %}``
  
``📂_layouts``
- These are the templates that wrap pages

``📂_pages``
- Here are the main pages of the web (added in ``_config.yaml``)

``📂_posts``
- The folders with the final posts. The naming convention must follow the format: ``YEAR-MONTH-DAY-title.md``.

``📂assets``
- ...

``📜_config.yaml``
- This config file is meant for settings that affect your whole blog, values which you are expected to set up once and rarely edit after that. For technical reasons, this file is *NOT* reloaded automatically when you use `bundle exec jekyll serve`. If you change this file, please restart the server process.

``📜Gemfile``
- This is where you manage which Jekyll version is used to run. When you want to use a different version, change it below, save the file and run `bundle install`. Run Jekyll with `bundle exec`, like so: ``bundle exec jekyll serve``

--- 

``_sass ``
- These are sass partials that can be imported into your ``main.scss`` which will then be processed into a single stylesheet ``main.css`` that defines the styles to be used by your site. 

``_site``
- This is where the generated site will be placed (by default) once
          Jekyll is done transforming it. It’s probably a good idea to add this
          to your ``.gitignore`` file.

``.jekyll-cache``
- Keeps a copy of the generated pages and markup (e.g.: markdown) for
          faster serving. Created when using e.g.: ``jekyll serve``.
          Can be disabled with
          <a href="/docs/configuration/options/">an option and/or flag</a>.
          This directory will not be included in the generated site. It’s
          probably a good idea to add this to your ``.gitignore``
          file
Other Files/Folders
- Except for the special cases listed above, every other directory and 
          file—such as ``css`` and ``images`` folders,
          ``favicon.ico`` files, and so forth—will be copied verbatim
          to the generated site. There are plenty of <a href="/showcase/">sites
          already using Jekyll</a> if you’re curious to see how they’re laid
          out.

### Gemfile and Gemfile.lock
Bundler installs the gems and creates a ``Gemfile.lock`` which locks the current gem versions for a future ``bundle install``. If you ever want to update your gem versions you can run ``bundle update``.


## Jekyll Tutorial
- Step by Step Tutorial: https://jekyllrb.com/docs/step-by-step/01-setup/
- Github actions: https://jekyllrb.com/docs/continuous-integration/github-actions/
  
