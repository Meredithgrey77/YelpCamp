# Introduction

## Model

### Campground Model

- CRUD: allow users to create, edit and delete campgrounds they've visited, and upload campground photos.
- Validate data and raise errors when needed.
- Display campground location on Google Maps.

### Review Model

- CRUD: allow users to create, edit and delete campground reviews.
- Validate data and raise errors when needed.
- Display review star rating.

### User Model

- Authentication:

- - Register
  - User login with username and password

- Authorization:

- - One cannot create, edit or delete any campgrounds if not logged in. One cannot edit and delete campgrounds created by other users. 
  - One cannot create, edit or delete any reviews if not logged in. One cannot edit or delete posts and comments created by other users.

## Styles

- Mainly used Bootstrap5 to format the page.

- Responsive web design.
- Used fancy cluster map on index page to show all campgrounds created.

## Other functionalities

### Flash

- Flash messages responding to users' interaction with the app.

### Common security Issues

- Avoid mongo injection, cross site scripting issues.
- Using helmet to apply content security policy.





 