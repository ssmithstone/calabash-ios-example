This project is testing out calabash-ios on Xcode 5.0.1 with latest calabash-cucumber

I build the app with the calabash target 

setup the APP_BUNDLE_PATH

run DEVICE=simulator calabash-ios console

inside irb

i run start_test_server_in_background which start the sim and the application but when I do 

touch("view marked:'Do Something Button'")

I receive this error 


TypeError: exception class/object expected
    from /Users/ssmithstone/.rvm/gems/ruby-2.0.0-p247@ios-calabash/gems/calabash-cucumber-0.9.160/lib/calabash-cucumber/uia.rb:122:in `raise'
    from /Users/ssmithstone/.rvm/gems/ruby-2.0.0-p247@ios-calabash/gems/calabash-cucumber-0.9.160/lib/calabash-cucumber/uia.rb:122:in `uia_handle_command'
    from /Users/ssmithstone/.rvm/gems/ruby-2.0.0-p247@ios-calabash/gems/calabash-cucumber-0.9.160/lib/calabash-cucumber/uia.rb:36:in `uia_tap_offset'
    from /Users/ssmithstone/.rvm/gems/ruby-2.0.0-p247@ios-calabash/gems/calabash-cucumber-0.9.160/lib/calabash-cucumber/ios7_operations.rb:19:in `touch_ios7'
    from /Users/ssmithstone/.rvm/gems/ruby-2.0.0-p247@ios-calabash/gems/calabash-cucumber-0.9.160/lib/calabash-cucumber/core.rb:94:in `do_touch'
    from /Users/ssmithstone/.rvm/gems/ruby-2.0.0-p247@ios-calabash/gems/calabash-cucumber-0.9.160/lib/calabash-cucumber/core.rb:85:in `touch'
    from /Users/ssmithstone/.rvm/gems/ruby-2.0.0-p247@ios-calabash/gems/calabash-cucumber-0.9.160/lib/calabash-cucumber/core.rb:81:in `touch'
    from /Users/ssmithstone/.rvm/gems/ruby-2.0.0-p247@ios-calabash/gems/calabash-cucumber-0.9.160/lib/calabash-cucumber/ios7_operations.rb:24:in `touch_ios7'
    from /Users/ssmithstone/.rvm/gems/ruby-2.0.0-p247@ios-calabash/gems/calabash-cucumber-0.9.160/lib/calabash-cucumber/core.rb:94:in `do_touch'
    from /Users/ssmithstone/.rvm/gems/ruby-2.0.0-p247@ios-calabash/gems/calabash-cucumber-0.9.160/lib/calabash-cucumber/core.rb:85:in `touch'
    from (irb):2
    from /Users/ssmithstone/.rvm/rubies/ruby-2.0.0-p247/bin/irb:12:in `<main>'
