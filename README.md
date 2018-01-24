Steps to reproduce
------------------

* Clone the project, create a virtualenv, install requirements.

* Create a superuser and log into the admin.

* Create an `Upload` object with this image: https://fleschenberg.net/IMG_9992.jpg

Note that the permissions are `0600`. For other (smaller?) images, they are
`0644` as expected.
