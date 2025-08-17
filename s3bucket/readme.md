# S3 website hosting


1. created a s3 bucket and named it after my name. 
( buckets names are specific and can't be relicated anywhere, for eg unless i delete my bucket another bucket of same name can't be created.)
2. Used ACL(access control list) instead of bucket policies for Object Owndership,
![](image.png)
acl allow us to set rules for every single object on our device and who all can use it.
3. clear block all public access box since its been helps to be discovered in public traffic.
![alt text](image-1.png)
4. ![upload stuff](image-2.png)
5. ![static website hosting](image-3.png)
6. index document is chosen to any index.html file or  any main file to be displayed.
![hosting console](image-4.png)
7. get URL under bucket website endpoint
that end poin url shows the url to the website.
8. ![change permissions](image-5.png)
html is by default private we need to change it to public by changing permissions.
9. ![changed status](image-6.png)
when changed status this should look like this.
