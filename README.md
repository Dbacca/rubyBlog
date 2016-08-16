# Ruby on Rails: My First App

This is a simple blog application I built using Ruby on Rails. I have exclusively done front end work up to this and was curious to see how the back end worked. Learning about the MVC structure and how each item worked together to produce the content was really interesting and enlightening to me.

### Knowledge Prep
Before creating this app I did a few very basic courses on Code School that taught basic Ruby syntax and read a few articles about MVC that gave me a very basic understanding of how Ruby works and what MVC is all about.

- [Code School "Try Ruby"](https://www.codeschool.com/learn/ruby)

- [MVC for Noobs](http://www.dummies.com/web-design-development/mobile-apps/the-model-view-controller-mvc-design-pattern/)

### Setting up rbenv
After a little investigation it was clear if I planned to work with ruby on any sort of ongoing basis setting up a version manager would be well worth my time. The clear choice [rbenv](https://github.com/rbenv/rbenv), after hearing from several sources it was more user friendly than it's competitor [RVM](https://rvm.io/)

It took some trial and error to get everything set up properly but once found a few key commands and I realized you could set a global version that acts as a system default I was all set.

```
# list all available versions:
$ rbenv install -l

#install a Ruby Version:
$ rbenv install 2.3.1
```

##### rbenv global

  >Sets the global version of Ruby to be used in all shells by writing the version name to the ~/.rbenv/version file. This version can be overridden by an application-specific .ruby-version file, or by setting the RBENV_VERSION environment variable.

  ```
  $ rbenv global 2.3.1
  ```

### The Rails tutorial
  A friend I met while traveling in Thailand is a self taught Ruby developer and he recommended this tutorial to guide me through creating my first rails app.

  [Getting Started with Ruby on Rails](http://guides.rubyonrails.org/getting_started.html)

  Some of the content went over my head and I found myself rereading entire sections multiple times and still struggling to fully comprehend what I was reading.

  But a couple Models, Views and Controllers later I started to actually understand what I was building and how each piece of interacted with one another

### The "Magic" of Rails
I think the fact the the first real programing language I learned was JavaScript lead me to believe that coding was all about semi-colons and curly braces and super explicit instructions. Like THAT was what made something *code*.

Ruby on Rails really gave me a different perspective in the sense that it is incredibly simple to read/write and it does **so much** for you with so little code.

A senior dev buddy of mine started to "translate" some of the ruby code into Javascript to help illustrate the point and after typing 6 or 7 lines of JS to mimic the 1 line of Ruby he was frustrated and I was convinced.

At this point I see this is a double edged sword because, as much as I appreciate the simplicity and convenience I feel like I am missing a fundamental understanding of what Ruby and Rails are doing behind the scenes.

## 1st day wrap up
So after diving into Ruby on Rails for one day I feel like I took in a ton of information and was able to process about half. Seeing as how this was day 1 of not only Ruby but also looking at the back end in general I feel like things went pretty smoothly.

I am confident by the end of the week I will have a fully functional app deployed and better understanding of both Ruby on Rails and MVC.
