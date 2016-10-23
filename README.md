Borderhack Website
==================

This is the official Borderhack website development repository. 
This is an [Hexo.io](https://hexo.io/) site repository so you need hexo to run the test server and preview the website. 

I assume you already have Node.js installed


Installing Hexo
---------------

Let's install _hexo-cli_ and _hexo-server_

	npm install hexo-cli -g
	npm install hexo-server -g 

Now clone the repository

	git clone https://github.com/B0rderh4ck/hexo_borderhack_site.git
	cd hexo_borderhack_site

Install hexo dependencies

	npm install


Hexo usage
----------

Read the documentation to lern how to write a post or customize the site layout: [Hexo.io docs](https://hexo.io/docs/index.html)



Deploy
------

The configuration file already have the repository defined. The section you need to check is in the __config.yml_  file:

	# Deployment
	## Docs: https://hexo.io/docs/deployment.html
	deploy:
	  type: git
	  repo: https://github.com/B0rderh4ck/B0rderh4ck.github.io.git
	  branch: master

_repo_ is the github.io site repository where our static files will be pushed.

To deploy with Hexo:

	hexo clean
	hexo generate
	hexo deploy


Usefull resources
-----------------

Tutorial used to implement this configuration: [How to Create a Blog with Hexo On Ubuntu 14.04](https://www.digitalocean.com/community/tutorials/how-to-create-a-blog-with-hexo-on-ubuntu-14-04)

Other:

-	[How To Set Up Automatic Deployment with Git with a VPS](https://www.digitalocean.com/community/tutorials/how-to-set-up-automatic-deployment-with-git-with-a-vps)
- 	[Deploy a live site with Git](https://www.gadgetdaily.xyz/create-a-background-changing-scroll-effect/)





