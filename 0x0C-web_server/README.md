0x0C. Web server
0. Write a Bash script that transfers a file from our client to a server:
1. Web servers are the piece of software generating and serving HTML pages, let’s install one!
2. When your domain name is setup, please verify the Registrar here: https://whois.whoisxmlapi.com/ and you must see in the JSON response: "registrarName": "Dotserve Inc"
3. Configure your Nginx server so that /redirect_me is redirecting to another page.
4. Configure your Nginx server to have a custom 404 page that contains the string Ceci n'est pas une page.
5. Time to practice configuring your server with Puppet! Just as you did before, we’d like you to install and configure an Nginx server using Puppet instead of Bash. To save time and effort, you should also include resources in your manifest to perform a 301 redirect when querying /redirect_me.
