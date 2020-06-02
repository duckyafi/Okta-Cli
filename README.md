# Okta-Cli
This is my collection Okta-Cli Commands

<h1>How to install Okta-Cli</h1>

<li>install https://pypi.org/project/okta-cli/ or if you have pip installed (pip install okta-cli)</li>

<li>Setup config file: okta-cli config new -n xx-username -u https://companyurl.okta.com -t <API_TOKEN></li>

<li>If you run into issues after installing delete the config file and try running the install again file is located inside the ~/Library/Application\ Support/okta-cli if you installed on a Mac</li>

<li>If you need to run two commands simultaneously use the | option</li>
----------------------------------

<h2>User Commands</h2>

<li>okta-cli users list (list all the users in your Okta tenet)</li>
<li>okta-cli users deactivate test@example.com (you can use the user ID or email)</li>
<li>okta-cli users get email or id (when searching for a specific user)</li>
<li>okta-cli users update 00ub0a1uveQ1IZ0BZ4x6 -s credentials.password.value="password2020!" (to change users password)</li>
<li>okta-cli users list | grep username (use this to find a specific user)</li>

----------------------------------

<h3>Application Commands</h3>

<li>okta-cli apps list (list all the application in your Okta tenet)</li>
<li>okta-cli apps activate appid</li>
<li>okta-cli apps deactivate appid</li>
<li>okta-cli apps delete appid (Deactivate must happen before deletion)</li>
<li>okta-cli apps users -i appid (list all the users who are assigned this application)</li>
<li>okta-cli apps users --csv -i appid (prints out the csv version)</li>
<li>okta-cli apps users -j -i appid (prints out the YAML version)</li>

----------------------------------

<h3>Group Commands</h3>

<li>okta-cli groups list (list all the groups in your Okta tenet)</li>
<li>okta-cli groups users groupid (list all the users in the group)</li>
<li>okta-cli groups delete groupid</li>

----------------------------------
<h4>Bulk Functions</h4>

<li>okta-cli dump (use this to dump all your Okta info tenet into a csv)</li>
