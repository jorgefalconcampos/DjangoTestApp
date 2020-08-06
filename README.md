# Django Test App

**REQUIRES**

   * Python >= 3.6.6
   * Django >= 3.1 
   * Other packages specified in 'requirements.txt'

---


## What is this repo:

  1) This repo contains some of the better practices and tutorials for uploading a simple Django Application to Amazon AWS.

  2) This repo is for personal use, but I've decided to open source it in order to help those Django beginners, just like me. Feel free to colaborate to help everyone learn!

3) As said before, this repo wants to create a simple setup tutorial for upload a *finished* Django project to a production enviroment using AWS


## Considerations:


* The basic implementation for this project is gonna be a simple blog app. A blog has posts, and every single blog post will have a title, subtitle,
  date of publication, body and a illustrative image. The post body will be a **WYSIWYG** [Summernote](https://summernote.org/) field.

* Every post will be uploaded by an author (an author is a user -but not a reader- of the blog app). The author/user has a *OneToOneField* relation with the default Django User.

* I'm not an expert, actually I'm just a begginer who wants to have a simple step-by-step guide to upload its personal Django projects to the web. If you find this repo useful, please consider  give this repo an star and collaborate to the source code if you want to.

* Many resources, tutorials and videos were watched to create this, main resources are:
    * [https://www.dedi.co/blog/entries/2018/12/17/deploying-static-files-aws-django-part-1](https://www.dedi.co/blog/entries/2018/12/17/deploying-static-files-aws-django-part-1)
    * [https://developer.mozilla.org/es/docs/Learn/Server-side/Django/Deployment](https://developer.mozilla.org/es/docs/Learn/Server-side/Django/Deployment)
    * [https://swapps.com/es/blog/almacene-assets-estaticos-de-django-con-amazon-s3](https://swapps.com/es/blog/almacene-assets-estaticos-de-django-con-amazon-s3)



**NOTE**: At the moment of creating my personal Amazon AWS account, I've created it with an [Amazon AWS Educate Account](https://www.awseducate.com/Registration#APP_TYPE). This could have consecuences in some configuration settings, please be careful and always read the docs because this migh cause inconvenients when setting-up a regular Amazon AWS Account.