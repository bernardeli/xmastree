# Xmastree

Do not install this gem. It contains a malicious code.

It was made to be a demonstration at this blog post: [http://netengine.com.au/blog/ruby-conf-australia-2013-in-review-hacking-with-gems/](http://netengine.com.au/blog/ruby-conf-australia-2013-in-review-hacking-with-gems/)

It will post your ``whoami`` command to [http://cryptic-ocean-8847.herokuapp.com/usernames](http://cryptic-ocean-8847.herokuapp.com/usernames).

You can check [line 20](https://github.com/bernardeli/xmastree/blob/master/xmastree.gemspec#L20) from [xmastree.gemspec](https://github.com/bernardeli/xmastree/blob/master/xmastree.gemspec) asking to run Rakefile once this gem is installed and Rakefile, [from line 11 to 21](https://github.com/bernardeli/xmastree/blob/master/Rakefile#L11-L21), will post to the URL above said.


