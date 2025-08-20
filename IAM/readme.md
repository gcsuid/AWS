# IAM
1. we know identity and access management service is for who is authenticated and authorized to use resources in aws acc.
2. we first create an EC2 or 'elastic cloud compute instance.
3. chosen new tags with key=env, value=production.
4. we got through this without key pair or secure shell.
5. ![network config](image.png)
6. then created an IAM, then to policies. Chose create policy, switched to JSON.
7. ![permission on the console](image-1.png)
8. create alias for the user to unboard.
9. creating a group: helps in simplifying and attaching policies to everyone at once.
10. ![name of group with permission attached](image-2.png)
11. we then add users to that group so that we dont have to do that for everyone. 
12. ![user](image-3.png)
13. ![failed usgae](image-4.png)
tried to access restricted stuff and failed since we're not allowed.
