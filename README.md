# RailsCasts Episode #395: Action Controller Walkthrough

http://railscasts.com/episodes/395-action-controller-walkthrough

Requires Ruby 1.9.2 or higher.


### Commands used in Terminal

```
git clone https://github.com/rails/rails.git
cd rails
git checkout 3.2.9
```

### Commands used in rails console

```
puts ArticlesController.ancestors
puts ArticlesController.ancestors - ArticlesController.included_methods
ArticlesController.action(:index)
ArticlesController.method(:action).source_location
```
