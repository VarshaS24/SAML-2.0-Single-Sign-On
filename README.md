# SAML-2.0-Single-Sign-On

Step 1: Application Environment Setup: 

Action: Accessed the Okta Admin Console to manage the application lifecycle.

Observation: The dashboard shows an active users and multiple applications.

Goal: Establish a central hub for identity management and application integrations.

Step 2: Choosing the Authentication Protocol:

Action: Initiated a new app integration by selecting between industry-standard protocols.

Observation: Chose SAML 2.0 (XML-based SSO) over OIDC to support service providers that require traditional identity federation.

Goal: Match the security protocol to the requirements of the external service provider.

Step 3: Configuring the SAML Integration:

Action: Created a new SAML integration named "Sami_set" within the General Settings.

Observation: Configured the application visibility and branding options before moving to protocol-specific settings.

Goal: Define the basic identity of the application within the Okta ecosystem.

Step 4: Defining Service Provider (SP) Metadata:

Action: Inputted critical SAML endpoints including the Single Sign-On URL and Audience URI (Entity ID).

Observation: Used link as sptest.iamshowcase.com as the recipient destination for SAML assertions.

Goal: Ensure the "handshake" between Okta and the test application is mathematically and logically secure.

Step 5: User Assignment & Access Control:

Action: Assigned specific individuals to the new application to grant them login permissions.

Observation: Successfully assigned user Varsha Senthil to the "Sami_set" application.

Goal: Implement the "Least Privilege" model by only allowing authorized users to access the integration.

Step 6: Identity Provider (IdP) Metadata Exchange:

Action: Generated the Metadata URL and setup instructions needed by the external application.

Observation: Provided the unique Okta SSO URL to the test service provider to establish the trust relationship.

Goal: Complete the two-way trust bond between the Identity Provider (Okta) and the Service Provider.

Step 7: Multi-Factor Authentication (MFA) Enforcement:
Action: Triggered secondary security checks during the login process to verify user identity.

Observation: Configured multiple factors including Okta Verify (push notifications) and Google Authenticator (OTP codes).

Goal: Add a "Smart Security Guard" layer to protect accounts even if a password is compromised.

Step 8: Successful SSO Verification:
Action: Tested the end-to-end flow from the Okta login page to the final application.

Observation: The user was successfully redirected to the "Simple Test Service Provider" page after passing MFA.

Goal: Confirm that the SAML assertion was correctly parsed and the user is fully authenticated.

DEMO VIDEO:



https://github.com/user-attachments/assets/ebfb4562-f82b-463a-9849-293c8e8bd78c



