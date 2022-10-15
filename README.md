# 1 - Recipe generator

### Using:
Create a new irb session in your code edit and use as an example:

```ruby
irb(main):001:0> load "lib/recipe.rb"
irb(main):002:0> recipe = Recipe.new(name: "Potato Jello")
irb(main):003:0> puts recipe.generate
```

You can try:

```ruby
irb(main):002:0> story = RecipeStory.new(name: "Potato Jello")
irb(main):003:0> puts story.generate
```
Or test in your terminal out of irb:
```
ruby recipe_generator.rb
```
