# Problem-set for Application Developer Training
 * Challenge: select, create and publish a cloud "instance" for your cloud application
 * Learning objectives (what will participants learn by completing these challenges?)
   * a.) learn how to select which image and flavour to use with your application.
   * b.) learn how to deploy your application to an instance (image+flavour) for use on a cloud.
   * c.) learn how to provide an HTTP web address (floating IP) so users can access your cloud application.
 * Relationship these problems have to other problems:
   * <link> to previously used problem-sets on API calls to the image service called Glance.
   * <link> to next problem-sets on scaling out your application to multiple instances (images+flavours)

## (1) Novice Problem: What size and shape of a cloud image do you need to host your cloud application for your users?
 * In pairs of people, solve the above problem by calculating the size and operating system which will host your application, once you have an answer compare it to another team's solution and discuss why you selected the image and flavour for your application.
 * ProTip: Decide which instance to use by listing the images and flavours the cloud has to offer.
 * Context: example code = http://developer.openstack.org/firstapp-libcloud/getting_started.html#flavors-and-images

## (2) Intermediate Problem: Boot and configure your instance with your application installed.
 * In groups of 4 people, select one of your application to deploy, once you think you have it deployed raise your hand and receive a prize from the one of the instructors/helpers!
 * ProTip: Don't forget OpenStack filters all traffic!
 * Context: example code = http://developer.openstack.org/firstapp-libcloud/getting_started.html#boot-and-configure-an-instance

## (3) Advanced Problem: Give your cloud application an HTTP web address so your users can use it!
 * In groups of 8 people, select one of your applications which have been deployed and associate a floatin IP with it so your external users can access it from around the world!
 * ProTip: what the differene between public vs private IPs for OpenStack?
 * Context: example code = http://developer.openstack.org/firstapp-libcloud/getting_started.html#associate-a-floating-ip-for-external-connectivity

---
This example taken from the "My First Cloud App" guide using the Python Libcloud SDK
 
