# Instagram Clone

## Built By [DannyMyles](https://github.com/DannyMyles/Instagram/)

## Description
This is an Instagram clone app, you can post image and like,share and comment.

## User Stories
* Sign in to the application to start using.
* Upload my pictures to the application.
* See my profile with all my pictures.
* Follow other users and see their pictures on my timeline.
* Like a picture and leave a comment on it.r.

Users would like to:
* View all images submitted.
* Click on images to display more details.
* Search for images by category.
* Copy links to images to share with their friends

## Admin Abilities
These are the behaviours/features that the application implements for use by the admin.

Admin should:
* Sign in to the gallery
* Create new images for showcasing
* Delete images


## Specifications
| Behaviour | Input | Output |
| :---------------- | :---------------: | ------------------: |
| Admin Authentication | **On demand** | Access Admin dashboard |
| Display all images | **Home page** | Clickable links to open any images in a modal |
| Display single images on click | **On  click** | All details should be viewed|
| To add an image  | **Through Admin dashboard** | Add and add categories and tag location of Image|
| To edit image  | **Through Admin dashboard** | Redirected to the  image form details and editing happens|
| To delete an image  | **Through Admin dashboard** | click on image object and confirm bhttps://me-gallery.herokuapp.com/y delete button|
| To search  | **Enter text in search bar** | Users can search by category|
| To filter by Location  | **Click drop-down on navbar** | Users can view images by Location|

## Application link
click [here]()


## SetUp / Installation Requirements
### Prerequisites
* python3
* pip
* virtualenv
* Requirements.txt

### Cloning
* In your terminal:

        $ git clone https://github.com/DannyMyles/Instagram
        $ cd Gallery

## Running the Application
* Creating the virtual environment

        $ python3 -m venv --without-pip virtual
        $ source virtual/bin/activate
        $ curl https://bootstrap.pypa.io/get-pip.py | python

* Installing Django and other Modules

        $ see Requirements.txt

* To run the application, in your terminal:

        $ python3 manage.py runserver

## Testing the Application
* To run the tests for the class files:

        $ python3 manage.py test images

## Technologies Used
* Python3
* Django and postgresql

## License

Copyright (c) 2021 DannyMyles

------------

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

