# About Dokku Farmer

Dokku farmer is an API control layer built around dokku-alt. As you deploy more and more nodes running dokku-alt you can add them into dokku-farmer through the Admin Interface. After you can use Rest API to deploy apps to your site.

## How can you use dokku-farmer?

If you run sites like wordpress.com, you can integrate your application logic with Dokku Farmer. Whenever newsite needs to be launched, you simply create an API call passing an Git URL of your choice. Dokku Farmer will find a node for you and deploy container for you. 

## How does it work?

Dokku-farmer is written in PHP and takes advantage of Queues for running your long-time jobs. You can extend Dokku-Farmer for extra procedures you might want to run. Using internal API you can deploy jobs across all of your deployments and tweak.