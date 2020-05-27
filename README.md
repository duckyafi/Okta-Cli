# Okta-Cli
This is my collection Okta-Cli Commands

<h1>How to install Okta-Cli</h1>

<li>install https://pypi.org/project/okta-cli/ or if you have pip installed (pip install okta-cli)</li>

<li>Setup config file: okta-cli config new -n xx-username -u https://companyurl.okta.com -t <API_TOKEN></li>

<li>* If you run into issues after installing delete the config file and try running the install again file is located inside the ~/Library/Application\ Support/okta-cli if you installed on a Mac</li>


----------------------------------

<h2>User Commands</h2>

<li>okta-cli users list (list all the users in your Okta tenet)</li>
<li>okta-cli users deactivate enter user id</li>

----------------------------------

<h3>Application Commands</h3>

<li>okta-cli apps list (list all the application in your Okta tenet)</li>

----------------------------------

<h3>Group Commands</h3>

<li>okta-cli groups list (list all the groups in your Okta tenet)</li>
