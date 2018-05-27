fastlane documentation
================
# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```
xcode-select --install
```

## Choose your installation method:

<table width="100%" >
<tr>
<th width="33%"><a href="http://brew.sh">Homebrew</a></td>
<th width="33%">Installer Script</td>
<th width="33%">Rubygems</td>
</tr>
<tr>
<td width="33%" align="center">macOS</td>
<td width="33%" align="center">macOS</td>
<td width="33%" align="center">macOS or Linux with Ruby 2.0.0 or above</td>
</tr>
<tr>
<td width="33%"><code>brew cask install fastlane</code></td>
<td width="33%"><a href="https://download.fastlane.tools">Download the zip file</a>. Then double click on the <code>install</code> script (or run it in a terminal window).</td>
<td width="33%"><code>sudo gem install fastlane -NV</code></td>
</tr>
</table>

# Available Actions
## iOS
### ios open_release_branch_and_tag
```
fastlane ios open_release_branch_and_tag
```
Create and checkout release branch from develop

Checkout master, add tag and increment build number
### ios publish_changelog_and_release_notes_to_slack
```
fastlane ios publish_changelog_and_release_notes_to_slack
```
Publish changelog and release notes to Slack channel
### ios hsbc_beta_certificate_and_provisioning
```
fastlane ios hsbc_beta_certificate_and_provisioning
```

### ios install_certificates
```
fastlane ios install_certificates
```

### ios distribution
```
fastlane ios distribution
```
Runs unit tests

Increment build number

Builds and archives app

Hockey app distribution

resets git repo
### ios hockey_app_distribution
```
fastlane ios hockey_app_distribution
```
Hockey app distribution groups
### ios debug_test_coverage
```
fastlane ios debug_test_coverage
```

### ios production_build_create_release_branch_and_archive_for_test_flight
```
fastlane ios production_build_create_release_branch_and_archive_for_test_flight
```
Creates release branch

Runs unit tests

Builds and archives, then creates zip and moves to build directory

Merges release branch into master and develop

Creates changelog and publishes release notes to Slack
### ios production_build_archive_and_zip
```
fastlane ios production_build_archive_and_zip
```
Runs unit tests

Builds and archives, then creates zip and moves to build directory

Creates changelog and publishes release notes to Slack
### ios hsbc_beta_test
```
fastlane ios hsbc_beta_test
```
Runs unit tests
### ios development_build
```
fastlane ios development_build
```
Builds and archive app
### ios adhoc_build
```
fastlane ios adhoc_build
```
Builds and archive app
### ios zip_xcarchive
```
fastlane ios zip_xcarchive
```
Creates zip and directory in root
### ios create_zip_and_move_to_build_directory
```
fastlane ios create_zip_and_move_to_build_directory
```
Creates zip and moves to build directory

----

This README.md is auto-generated and will be re-generated every time [fastlane](https://fastlane.tools) is run.
More information about fastlane can be found on [fastlane.tools](https://fastlane.tools).
The documentation of fastlane can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
