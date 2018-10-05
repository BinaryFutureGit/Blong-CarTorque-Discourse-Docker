Repositories
1. Blong-CarTorque-Discourse-Docker - this repo is synced to the production server. It contains the configuration & setup for the productions server. See containers/app.yml
2. Blong-CarTorque-Discourse-topic-previews - Customized version of topic preview plugin, include all the template customization
3. Blong-Cartorque-Event - Clone version of event plugin, remove the conflicted template
4. Blong-Cartorque-Theme - Repo include theme file to import ionic framework and CSS stylesheet for mobile view
5. discourse - Local Version of Discouse for development purpose

Development
1. Launch Docker Manager
2. [repo: discourse] ./bin/docker/rails s

[ additional step and details ] 
Dev Login details:
james@binaryfuture.world
insite12345

shutdown docker instance: ./bin/docker/shutdown_dev
bootup docker instance: ./bin/docker/boot_dev --init


Theme Syncing
1. Configuration File location ~/.discourse_theme
2. change directory to ~/Documents/GitHub
3. discourse_theme watch ./cartorque_theme/


How to run on server
1. clone this repo onto the server
2. ./launcher restart

Important Information
https://meta.discourse.org/t/developer-s-guide-to-discourse-themes/93648

