# README

Project description link: https://www.theodinproject.com/lessons/ruby-on-rails-forms

Main things in this project:
- Generate a model/controller for User
```bash
rails g controller/model <name-here>
```
- Learn how to build forms in Rails template
```html.erb
<%= form_with model: @user do |form| %>
  <div>
    <%= form.label :username %><br>
    <%= form.text_field :username %>
  </div>

  <div>
    <%= form.label :email %><br>
    <%= form.text_field :email %>
  </div>

  <div>
    <%= form.submit "Update" %>
  </div>

<% end %>
```
- Learn how to use form helpers in Rails