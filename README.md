# CrytoNotes

## SAML (Security Assertion Markup Language) - authenticate once and tell all application this person is legit
SAML, is a standardized way to tell external applications and services that a user is who they say they are. 
SAML makes single sign-on (SSO) technology possible by providing a way to authenticate a user once and then communicate that authentication to multiple applications. 
The most current version of SAML is SAML 2.0.

SAML is esp useful in micro-service cloud environment, where we just need to authenticate the user once, but he/she could use all the services in the cloud.

## SSO (Single Sign-on)
Single sign-on (SSO) is a way for users to be authenticated for multiple applications and services at once. 
With SSO, a user signs in at a single login screen and can then use a number of apps. Users do not need to confirm their identity with every single service they use.
For this to take place, the SSO system must communicate with every external app to tell them that the user is signed in — which is where SAML comes into play.


![Alt text](./3way.jpg)
