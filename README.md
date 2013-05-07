Filterrific
===========

Filterrific makes it easy to let your app's users filter ActiveRecord lists:

* Allows your app's users to search, filter and sort lists of ActiveRecord objects.
* Integrates with pagination.
* Persists filter parameters in the session or database (for saved searches).
* Configurable default filter settings.


<div style="margin: 3em 0;">
  <blockquote>
    <p>
      I couldn't live without Filterrific. It makes it super easy to add
      user configurable reporting to my client projects.
    </p>
    <small>Jeff Ward, Animikii</small>
  </blockquote>
</div>


### Example app 1

---

<img src="http://filterrific.clearcove.ca/images/screenshot_c.png" alt="Filterrific in action"/>
<em>
  Example app 1: Filtering a list of members, with saved searches,
  pagination and filter reset. List at the left, filters to the right.
</em>

---

### Example app 2

---

<img src="http://filterrific.clearcove.ca/images/screenshot_q.png" alt="Filterrific in action"/>
<em>
  Example app 2: Filtering a list of questions. Filters above, list below.
</em>

---

### Details

* Filterrific takes care of shuttling filter settings from your view
  to ActiveRecord queries, and of returning matching records back to the view.
  You are responsible to implement the aspects that are specific
  to your application:
    * define the required scopes
    * style your filter form and record lists
* You use 3 APIs to integrate Filterrific into your app: Model, View and Controller.

Make sure to go to the fantastic [Filterrific documentation](http://filterrific.clearcove.ca)
to find out more!



### Dependencies

* Rails and ActiveRecord 3.x and 4
* PostgreSQL or MySQL
* Ruby 1.8.7 or greater



### Installation

`gem install filterrific`

or with bundler in your Gemfile:

`gem 'filterrific'`



### Resources

* [Documentation](http://filterrific.clearcove.ca)
* [Changelog](https://github.com/jhund/filterrific/blob/master/CHANGELOG.md)
* [Source code (github)](https://github.com/jhund/filterrific)
* [Issues](https://github.com/jhund/filterrific/issues)
* [Rubygems.org](http://rubygems.org/gems/filterrific)



### License

[MIT licensed](https://github.com/jhund/filterrific/blob/master/MIT-LICENSE).



### Note on Patches/Pull Requests

* Fork the project.
* Make your feature addition or bug fix.
* Add tests for it. This is important so I don't break it in a future version unintentionally.
* Commit, do not mess with rakefile, version, or history.
  (if you want to have your own version, that is fine but bump version in a commit by itself I can ignore when I pull)
* Send me a pull request. Bonus points for topic branches.



### Copyright

Copyright (c) 2010 - 2013 Jo Hund. See [(MIT) LICENSE](https://github.com/jhund/filterrific/blob/master/MIT-LICENSE) for details.
