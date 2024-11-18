<link rel="stylesheet" href="./assets/webAppEntry.css">
<script type="module" src="./assets/webAppEntry.js"></script>

Prod
client ab27ced0-7633-4912-b9fc-767716ad9da0
secret 6191d7fb66a94dc2a79c88c28039887f
cohort e7dc997a-4511-4dd6-9aab-ba6abeebd0a6

staging 
client  a5d4f774-489a-406c-9094-599a8802449e
cohort id e7dc997a-4511-4dd6-9aab-ba6abeebd0a6
secret 8d33567a11954c878e090de07fb4d3bb

Dev
client 8dd2d11d-dfb6-4079-b7df-915f103cdf49
cohort id e7dc997a-4511-4dd6-9aab-ba6abeebd0a6


# To test production
1. Replace the api.staging url with prod api url in the webAppEntry.js
2. We are already pointing to the test bucket so just overwrite with prod.
3. Use prod credentials to start the session.