# mygovlink
This repository contains the project for mygovlink website where you can find all important government services at one click.
Inpiration for the project: Problem Statement
With increasing number of government services, it is hard to keep track of all the great available services and portals by our government and it might be tricky to find. Also there has been drastic increase in the number of spoof and fraud websites. 
Impact: Several people face issues in find the websites and a lot of people are being targeted for cyber attacks via spoof websites
Consequence: Increase in number of cyber frauds and wastage of time leading to frustration and agony and mental breakdown. 
Urgency: If not now when? if not us who?

Functonal requirements: 1. providing correct website links 2. caetgorize links into different groups
Non functional requirements: 1. Fast content delivery 2. Low cost 3. Using IaC for infrastructure
Proposed Solution: A website acting as a centralized source for all the important websites. You can go to the wesbite and then navigate to your required services from there easily. Easy, Safe and secure way to find the correct link to the wesbites.
Proposed Structure: We will build the website using basic HTML and CSS. We will AWS for our server infrastructure and utilize Terraform to create infrastructure easily. This is to showcase your devops skills in Terraform and AWS

HLD: 
![mygovlink drawio](https://github.com/user-attachments/assets/1eef6fa0-193f-4aa0-a51c-a09bfb014c84)

Flow: The User will request to Route 53 which will utilize CloudFronts capabilities for fastest possible way to serve the customers. CloudFront is directed towards S3 bucket which will then serve the website.

Benefits of this solution: 1. Fast content delivery due to cloudfront 2. Route 53 will resolve the request to correct URL 3. S3 bucket website is a cheap and reliable solution for static websites. 

DevOps Skill Perspective: 1. Terraform is used to deliver infrastructure on AWS. 2. AWS solution have been used using AWS prowess.




