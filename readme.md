Ruby Sample
=============

This sample helps you create a shippable.yml file for your Ruby project on Shippable. Please refer to our [language specific documentation on Ruby](http://docs.shippable.com/languages/#ruby) for more details.

### Build Image

The sample uses a ruby specific build image that's available for public use:
[shippableimages/ubuntu1204_ruby](https://registry.hub.docker.com/u/shippableimages/ubuntu1204_ruby)  ([Dockerfile](https://github.com/shippableImages/ubuntu1204_ruby/blob/master/Dockerfile)).

To set your build image in Shippable:
- Login to [Shippable](https://www.shippable.com) 
- Navigate to your project page by clicking on the project link
- Click on **Settings** and choose the following option:

`Pull Image from : shippableimages/ubuntu1204_ruby`

For more details on project settings, you can refer our docs on  [Build and Project Settings](http://docs.shippable.com/project_settings).
