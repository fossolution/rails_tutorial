# rails_tutorial
Short Tutorial on Ruby On Rails
Creaate Vagrantfile

vagarant up
vagrant ssh

# on VM
mkdir -p /vagrant_share/list-app
cd /vagrant_share/list-app

rails new . --api --database=postgresql -T --no-rdoc --no-ri

rails db:create
rails db:migrate
rails s

# React App
npx create-react-app client


# Lets build it 
# Create user model first
rails g model User name email password_digest
rails db:migrate


