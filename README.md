# Rails Starter Template

Inspired by [Denny Britz's](https://raw.github.com/dennybritz/rails_startup_template/master/template.rb) Rails staturp template

I decided to create my own flavor. 

## How to use 

```bash
rails new [your_app_name] -m https://raw.githubusercontent.com/bodefuwa/rails_starter_template/master/bootstrap.rb
```

---

## Script provides the following:

- Sets up your Gemfile

- Modifies your application.css with sass extension and removes the include_tree directives.

### Gives you the following options: 

- [Haml](https://github.com/indirect/haml-rails), [Slim](https://github.com/slim-template/slim-rails) or leaves ERB

- [Twitter bootstrap](https://github.com/twbs/bootstrap-sass) or [Zurb foundation](https://github.com/zurb/foundation-rails)

- [PostgreSQL](https://rubygems.org/gems/pg), [MySQL](https://github.com/brianmario/mysql2), [MongoDB](https://github.com/mongodb/mongoid), or [Redis](https://github.com/redis-store/redis-rails)

- [Font Awesome](https://github.com/bokmann/font-awesome-rails)

- [Active Admin](https://github.com/activeadmin/activeadmin) or [Upmin](https://github.com/upmin/upmin-admin-ruby)

- Installs [Cancan](https://github.com/ryanb/cancan)

- [Devise](https://github.com/plataformatec/devise) or [OmniAuth](https://github.com/intridea/omniauth-rails)

- Installs [Better Errors](https://github.com/charliesome/better_errors)

- [Puma](https://github.com/puma/puma) or [Unicorn](https://github.com/defunkt/unicorn)

- [Elasticsearch](https://github.com/elastic/elasticsearch-rails)

- Installs [Active Model Serializers](https://github.com/rails-api/active_model_serializers)

- [Rspec](https://github.com/rspec/rspec-rails) or [Minitest](https://github.com/seattlerb/minitest)

- API facilities [Grape](https://github.com/ruby-grape/grape), [Rack-Cors](https://github.com/cyu/rack-cors), and [Grape-Swagger](https://github.com/tim-vandecasteele/grape-swagger)

- [Angular js](https://github.com/ludicast/angular-rails), [Ember js](https://github.com/emberjs/ember-rails) or, [Backbone js](https://github.com/codebrew/backbone-rails)

- Initializes a new git repository with an initial commit

- Push to a [GitHub](http://github.com) or [Bitbucket](http://bitbucket.org) repository

- Create a [Heroku](http://heroku.com) stack and deploy 

---

```ruby
yourChoices = %w[experiment extend enjoy]
```

> Of course upon completing this small project, I saw so many other gems I could have added that would have provided more value. 
> That's what makes  the rails community great I guess. On to v0.2