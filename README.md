# inquisitive

This app constantly inquires about users' changing details and whereabouts. It  helps in ensuring physical security for it's users. If inquisitive detects abnormal behaviour from its user, it passes the information to the registered concerned parties.

###### Processes of development

```
rails new inquisitive --skip-bundle --skip-active-record --skip-test --skip-system-test
```  
We pass --skip-active-record to request that ActiveRecord is not added as a dependency, because we will be using Mongoid instead. Additionally we pass --skip-bundle because we’ll be modifying the Gemfile to add the mongoid dependency. We pass --skip-test --skip-system-test because we will be using RSpec.
