rails blog
cd blog
rails server
rails g controller controller_name action ( rails g controller Welcome index)
	-index.html.erb (add message)
	-routes.rb (add get and root)
	-routes.rb (add resources)
rails g controller Articles
	-articles_controller.rb (add new method)
	-new.html.erb (add message, add form)
rails g model Article title:string body:text
rails db:migrate (to run the migration)
articles_controller.rb(change the create method)