### torquebox
---
https://github.com/torquebox/torquebox

```sh
torquebox run
rails s torquebox
rackup -s torquebox
bundle install
rake build
rake spec
cd integration-tests
rake spec

cd integration-tests
SPEC=spec/basic_sinatra_spec.rb rake spec

DEBUG=true rake spec

rake spec:all
rake install

git remote add release git@github.com:torquebox/torquebox-release.git
git push release master:master -f

git push release master:master -f
gem push <gem_name>.gem

git fetch release --tags
git merge release/master
git push origin master
git push origin <release_tag>
```

```
```

```
```


