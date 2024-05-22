# DecisionSuite_Token_in_Url

Demonstration of session hijacking vulnerability in Targit Business Decision Suite 23.2.15007.0 and older.
Session tokens are sent as part of the url for several functions creating base for the following attacks:

- Interception of the Session ID while in transit.
- Bookmarking & Browser History
- Mistakenly sharing the URL.
- Referer URL.

![image](https://github.com/DMCERTCE/DecisionSuite_Token_in_Url/assets/168325622/2cf3dbad-f079-46f4-a056-71cf7c69aec7)

Targit A/S has communicated that this has been resolved in the versions prior to Autumn 2023 and that sessions IDs are no longer sent as part of the URL.
