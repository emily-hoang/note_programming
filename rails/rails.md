rails blog
cd blog
rails server

rails g controller controller_name action ( rails g controller Welcome index)
	-index.html.erb (add message)
	-routes.rb (add get and root, add resources)

rails g controller Articles
	-articles_controller.rb (add new method)
	-new.html.erb (add message, add form)

rails g model Article title:string body:text

rails db:migrate (to run the migration)

articles_controller.rb(change the create method, add strong parameter, add show method)
	-show.html.erb (add instance variable, linl_to 'Back')
	-articles.rb (add validates)
	-new.html.erb (add error message)
	-articles_controller.rb (add edit method)
	-edit.thml.erb
	-articles_controller.rb (add update method)
	-index.html.erb (add link_to 'Edit')
	-show.html.erb (add link_to 'Edit')
	-make a new file: _form.html.erb
	-new/edit.html.erb (rewriting completely with render 'form')
	-articles_controller.rb (add destroy method)
	-index.html.erb (add 'Destroy' link)