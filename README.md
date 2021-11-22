# docker-wordpress
A starter Docker configuration to allow for local Wordpress development.

# Environment file
You'll need to create a .env file as a sibling to the docker-compose.yml file.

Provide values for the following variables, e.g.:

- MYSQL_ROOT_PASSWORD=password1234
- MYSQL_USER=mysql
- MYSQL_PASSWORD=mysql_password

# Custom plugin development
Assume the custom plugin is stored locally at `/home/user1/src/wp-custom-plugin`.

From the root of this repo: `ln -s /home/user1/src/wp-custom-plugin custom-plugin`

# Custom theme development
Assume the custom theme is stored locally at `/home/user1/src/wp-custom-theme`.

From the root of this repo: `ln -s /home/user1/src/wp-custom-theme custom-theme`
