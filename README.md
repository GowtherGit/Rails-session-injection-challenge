How to:

First add the `mechanize` in Gemfile of the metasploit:

``` ruby
group :development, :test do
  # Other gems.........
  # Mechanize for exploit rails_csrf_token_bypass 
  gem 'mechanize'
end
```

execute in the root path Matasploit:
``` sh
$ bundle install
```
Copy the module for metasploit:
``` sh
$ sudo cp ./rails_csrf_token_bypass.rb path/to/metasploit/modules/auxiliary/admin/http/ 
```

And use:
#![Metasploit](/images/rails_csrf01.png)
#![Metasploit](/images/rails_csrf02.png)
#![Metasploit](/images/rails_csrf03.png)
#![Metasploit](/images/rails_csrf04.png)
#![Metasploit](/images/rails_csrf05.png)
#![Metasploit](/images/rails_csrf06.png)