pomf.rb
====================

## About
This is a simple Ruby library for uploading files to pomf.  
You can install this gem by either running `gem install pomf.rb` or adding `gem 'pomf.rb'` to your gemfile

Example of usage (Shown in pry)
```ruby
[1] pry(main)> require_relative 'pomf'
=> true
[2] pry(main)> Pomf.upload_file('test.txt')
=> "http://a.pomf.cat/ziizkv.txt"
[3] pry(main)> 
```

You can also specify upload and result urls in the argmuments.  
For example:
```ruby
[1] pry(main)> require_relative 'pomf'
=> true
[2] pry(main)> Pomf.upload_file('test.txt', 'https://i.fl0.co/upload.php', 'https://i.fl0.co/')
=> "https://i.fl0.co/i90hqs.txt"
```

More documentation will be added soon.

## TODO
- Verify support with other pomf clones.
- Tidy up code and fix few errors.

## Credits
- [euank](https://github.com/euank) for [simple-pomf-uploader](https://github.com/euank/simple-pomf-uploader)
