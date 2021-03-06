**RuboCop**'s installation is pretty standard:

```sh
$ gem install rubocop
```

If you'd rather install RuboCop using `bundler`, don't require it in your `Gemfile`:

```rb
gem 'rubocop', require: false
```

RuboCop's development is moving at a very rapid pace and there are
often backward-incompatible changes between minor releases (since we
haven't reached version 1.0 yet). To prevent an unwanted RuboCop update you
might want to use a conservative version locking in your `Gemfile`:

```rb
gem 'rubocop', '~> 0.67.0', require: false
```

!!! Note

    You can check out our progress on the road to version 1.0 [here](https://github.com/rubocop-hq/rubocop/milestone/4).
    You can also help us get there faster! :-)
