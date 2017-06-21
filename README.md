<b>Yahoo IDP Social Authentication Module</b>
<br/>
This directory contains the basic configuration bundle for setting up Yahoo as a social identity provider.
This bundle is to be used as a starting template configuration to accelerate integration.  Once imported the configuration would need manual changes specific to the deployment for settings such as clientId, clientSecret, scopes, logo's etc.
<br/>
<br/>
<b>Installation Steps</b>
<br/>
0 - Download / clone this repo containing the authentication module template, authentication chain template and Amster script
<br/>
1 - Run Amster with the "create-yahoo-social-idp.amster" script
<br/>
2 - Open the AM admin UI and edit the newly created YahooSocialAuthentication module, adding in the necessary clientId, clientSecret and required scopes.
<br/>
3 - Open the AM admin UI, navigate to the realm, services and Social Authentication Implementations page, if you wish to add a Yahoo logo onto the AM login page.  Copy the appropriate logo to the AM server.
<br/>
4 - To test the social IDP, call the necessary login URL - ../openam/XUI/?service=YahooSocialAuthenticationService&realm=/#login/
<br/>
<br/>
DISCLAIMER: The sample code described herein is provided on an "as is" basis, without warranty of any kind, to the fullest extent permitted by law. ForgeRock does not warrant or guarantee the individual success developers may have in implementing the sample code on their development platforms or in production configurations.

ForgeRock does not warrant, guarantee or make any representations regarding the use, results of use, accuracy, timeliness or completeness of any data or information relating to the sample code. ForgeRock disclaims all warranties, expressed or implied, and in particular, disclaims all warranties of merchantability, and warranties related to the code, or any service or software related thereto.

ForgeRock shall not be liable for any direct, indirect or consequential damages or costs of any type arising out of any action taken by you or others related to the sample code.
