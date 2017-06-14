# Duedil Task	

Hi prospective DueDiler!

Having grown tired of Jira, Deidre Duedil decided to make a new task manager in her 10% time. However, she didn’t quite get around to finishing it, and we need you to fix some of the problems in it to make it ready to roll out to the rest of the engineering team. 

Your first step will be to check out the code at the following GitHub repository and install and run the Symfony 2.8 application.  You may find [this page](https://symfony.com/doc/2.8/setup.html#installing-an-existing-symfony-application) useful. Set any of the parameters you are prompted for to the default suggested values. 

There is an SQLite 3 database included in the repository, within the app/ directory.

Once the install has finished, run `app/console server:run` and you should be able to see the app at http://127.0.0.1:8000.

The good news is that Deidre has included a copy of PHPUnit in the `app/` directory, and you can run the tests with `app/phpunit.phar -c app/`. However, the bad news is that they are failing, and we need the tests to pass before sharing with the rest of the team.

The next step is to check if all the functionality of the app works as expected, and fix anything that's broken.

Once the tests are running successfully, it might be a good idea to have a look at all of the files within `src/AppBundle` and see if there is any code which can be made safer or more efficient.

Finally it would be great to have a way to mark tasks as completed, so we know what we've achieved!

As an optional bonus, add something cool to the application.

Have Fun!

Team DueDil

![DueDil Logo](https://www.duedil.com/sites/default/themes/duedil_web/images/duedil_logo_main.png)
