# rails-console-pry

Run Rails 3 console using [pry][] without adding it to Gemfile.

Use `-r` to add global gems before loading `Bundler`, e.g., run it in Rails root directory:

    rails-console-pry -r pry-doc -r awesome_print

Or using production environment:

    rails-console-pry production -r pry-doc -r awesome_print

See usage by `rails-console-pry -h`.

It is recommended to add an alias to load your favorite pry plugins:

    alias rpry="rails-console-pry -r pry-doc -r awesome_print"

== Contributing to rails-console-pry
 
* Check out the latest master to make sure the feature hasn't been implemented or the bug hasn't been fixed yet.
* Check out the issue tracker to make sure someone already hasn't requested it and/or contributed it.
* Fork the project.
* Start a feature/bugfix branch.
* Commit and push until you are happy with your contribution.
* Make sure to add tests for it. This is important so I don't break it in a future version unintentionally.
* Please try not to mess with the Rakefile, version, or history. If you want to have your own version, or is otherwise necessary, that is fine, but please isolate to its own commit so I can cherry-pick around it.

== Copyright

Copyright (c) 2012 Ian Yang. See LICENSE.txt for
further details.

[pry]: http://pry.github.com/
