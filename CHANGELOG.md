Changes
-------

# 2.0

* Switched to new api, dependencies upgraded.
* Solved problem with defining protocol (thanks to chrisgrande).
* Django 1.11 added to tox for tests.

# 1.3.0

* Added url for inbound messages (receive sms messages)
* Fixed problem with IncomingSMSView
* Improved test project (logging and settings improvements)

# 1.2.0

* Fixed setup using django documentations (included migrations folder)

# 1.1.0

* Fixed bug in decorator
* Added test for twilio response by simulating twilio request.
* CHANGELOG added
* De-attached from fork in github due to complex pull requests (github uses fork by default)

# 1.0.0

* Folder structure changed (src -> dj_twilio_sms)
* Sample project to test app
* Travis-CI with tox to test pull requests
* Added first test with sending sms
* Migrations added so requirement to makemigrations after install removed

# 0.3.0

* First release for fork
* Django 1.10 support
* Timezone Fixed
* Dependencies updated
