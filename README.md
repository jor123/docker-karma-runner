Docker container to run Karma test with the selenium docker images.

Expose the default karma port, so e.g. a docker selenium/standalone-chrome container 
can access these tests.
Should configure the `hostname` in your karma.config.js to point back to this docker container.

Also contains git, so the source for a project can be retrieved.

