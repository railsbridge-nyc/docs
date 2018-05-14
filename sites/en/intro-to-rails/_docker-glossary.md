**docker-compose run web <<commands>>** will runs given commands in web service container.

**docker-compose run web rails c** will run rails console in web service container.

**docker-compose run web bash** runs bash to interact with the directory inside
the web service container. You can also use this to run Rails commands such as `rails console` too.

**docker-compose build** will build an image when `Dockerfile` changes or when you want to update or add gems.

**docker-compose up** starts up the containers.

**docker-compose up -d** starts up the containers **in the background**.

**docker-compose down** stops containers. If you have a Rails server running, this is how you stop it.

**docker-compose ps** lists container processes, container name, container id.

**docker attach <<contianer_name>>** attaches to the named container to interact
with `binding.pry`. `Control + p`, `Control + q`, detach from container.
