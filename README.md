## Laravel 5 example ##

### Features ###

* Home page
* Custom error pages 403, 404 and 503
* Authentication (registration, login, logout, password reset, mail confirmation, throttle)
* Users roles : administrator (all access), redactor (create and edit post, upload and use medias in personnal directory), and user (create comment in blog)
* Blog with comments
* Search in posts
* Tags on posts
* Contact us page
* Admin dashboard with messages, users, posts, roles and comments
* Users admin (roles filter, show, edit, delete, create, blog report)
* Posts admin (list with dynamic order, show, edit, delete, create)
* Multi users medias gestion
* Localization
* Application tests
* Use of new notifications to send emails and notify redactors for new comments

### Assets ###

CSS is compiled with Elixir, look at **gulpfile.js** for details.

### Tests ###

When you want to launch the tests first rollback the database :

`php artisan migrate:rollback`

Then migrate and seed :

`php artisan migrate --seed`

You can then use PHPUnit
