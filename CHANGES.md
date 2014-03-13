### March 10, 2014

- Enabled brakeman security reports collection for ruby projects that use "brakeman" gem
- Enabled experimental rails security reports pages for all ruby projects

### March 9, 2014

- Added "--expire" flag to "heroku pgbackups:capture" command to overwrite old backups
- Fixed issue with invalid .magnum.yml YAML contents that triggers a successful build

### February 28, 2014

- Fixed issue with NPM self-signed certificate (http://blog.npmjs.org/post/78085451721/npms-self-signed-certificate-is-no-more)
- Execute composer self-update on every build
- Log composer update to dev/null

### January 20, 2014

- Switch to PostgreSQL 3.0 for all project types
- Deprecate node.js v0.6 support, only 0.8, 0.10 and 0.11 are supported now
- Added MRI Ruby 2.1
- Git is updated to 1.8.5.2
- Subversion is updated to 1.7.9
- Mercurial is updated to 2.8.2
- Updated OpenJDK / JRE to 1.7
- Added heroku toolbelt to all project images
- Added QT dev libraries to all project images
- Fixed issue with ImageMagick dev libraries, they were missing

### January 19, 2014

- Added Heroku deployment integration
- Added capistrano deployment integration
- Added bash deployment integaration

### January 18, 2014

- Set number of builds on public pages to 30
- Fix issue with gitlab project type detection
- Fix issue with flash auto-hiding in 5 seconds

### January 14, 2014

- Fixed hipchat addon notifications. There was an issue with changed hipchat API endpoint.
- Added support for hipchat message colors (green/red build messages)
- Updated build badge images
- Ruby 1.8.7 support has been removed
- Go 1.0.3 support has been removed
- Added initial Clojure support
