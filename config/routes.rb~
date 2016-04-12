Rails.application.routes.draw do
  get 'favs/new'=>'favs#new'

  get 'favs/:id/edit'=>'favs#edit'

  get 'favs/:id'=>'favs#show'

  get '/favs'=>'favs#index'
  get 'favs/page'=>'favs#page'


get 'favs/terms'=>'favs#terms'
get 'favs/about'=>'favs#about'
get 'favs/careers'=>'favs#careers'
get 'favs/blog'=>'favs#blog'
get 'favs/services'=>'favs#services'
get 'favs/contact'=>'favs#contact'

#service routes#
get 'favs/service1'=>'favs#service1'
get 'favs/service2'=>'favs#service2'
get 'favs/service3'=>'favs#service3'
get 'favs/service4'=>'favs#service4'
get 'favs/service5'=>'favs#service5'


  # The priority is based upon order of creation: first created -> highest priority.
  # See how all your routes lay out with "rake routes".

  # You can have the root of your site routed with "root"
   root 'favs#new'

  # Example of regular route:
  #   get 'products/:id' => 'catalog#view'

  # Example of named route that can be invoked with purchase_url(id: product.id)
  #   get 'products/:id/purchase' => 'catalog#purchase', as: :purchase

  # Example resource route (maps HTTP verbs to controller actions automatically):
  #   resources :products

  # Example resource route with options:
  #   resources :products do
  #     member do
  #       get 'short'
  #       post 'toggle'
  #     end
  #
  #     collection do
  #       get 'sold'
  #     end
  #   end

  # Example resource route with sub-resources:
  #   resources :products do
  #     resources :comments, :sales
  #     resource :seller
  #   end

  # Example resource route with more complex sub-resources:
  #   resources :products do
  #     resources :comments
  #     resources :sales do
  #       get 'recent', on: :collection
  #     end
  #   end

  # Example resource route with concerns:
  #   concern :toggleable do
  #     post 'toggle'
  #   end
  #   resources :posts, concerns: :toggleable
  #   resources :photos, concerns: :toggleable

  # Example resource route within a namespace:
  #   namespace :admin do
  #     # Directs /admin/products/* to Admin::ProductsController
  #     # (app/controllers/admin/products_controller.rb)
  #     resources :products
  #   end
end
