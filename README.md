### polo
---
https://github.com/IFTTT/polo

```ruby
class Chef < ActiveRecord::Base
  has_many :recipes
  has_many :ingredients, through: :recipes
end
class Recipe < ActiveRecord::Base
  has_many :recipes_ingredients
  has_many :ingredients, throught: :recipes_ingredients
end
class Ingredient < ActiveRecord::Base
end
class RecipesIngredient < ActiveRecord::Base
  belongs_to :recipe
  belongs_to :ingredient
end

inserts = Polo.explore(Chef, 1)
INSERT INTO `chefs` (`id`, `name`) VALUES (1, 'Netto')

inserts = Polo.explore(Chef, 1, :recipes)

INSERT INTO `` () VALUES ()
INSERT INTO `` () VALUES ()
INSERT INTO `` () VALUES ()

inserts = Polo.explore(Chef, 1, :recipes => :ingredients)

INSERT INTO `` () VALUES()

Polo.configure do
end
Polo::Traveler.explore()

INSERT IGNORE INTO `` () VALUES ()

Polo.configure do
end
Polo::Traveler.explore(Chef, 1, :recipes)

INSERT INTO `` () VALUES ()
ON DUPLICATE KEY UPDATE id = VALUES(id), name = VALUES(name)

Polo.configure do
end
Polo::Traveler.explore(AR::Chef, 1)

Polo.configure do
  email_strategy = lambda do |email|
    first_part = email.split("@")[0]
    "#{first_part}@test.com"
  end
  credit_card_strategy = lambda do |credit_card|
    ""
  end
  socail_security_strategy = lambda do |ssn, instance|
  end
  obfuscate({
    'chef.email' => email_strategy,
    :credit_card => credit_card_strategy,
    :ssn_strategy => social_securty_strategy
  })
end

INSERT INTO `` (``, ``, ``) VALUES (1, '', '')

```

```
gem 'polo'
bundle
gem install polo

bundle install
bundle exec appraisal install
bundle exec appraisal rake

```

```
```


