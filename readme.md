GDE Sample: Chrome extension Google APIs
========================================

This is a sample Google Chrome extension that demonstrates using the Chrome Identity API to authorize access to the [Gmail](https://developers.google.com/gmail/api/v1/reference/users/labels/get) and [Google+](https://developers.google.com/+/api/latest/people/get) APIs. It is a quick start to the [Chrome User Authentication documentation](https://developer.chrome.com/apps/app_identity).


Getting started
---------------

The quick and easy to get the code running on your computer.

1. Download the source code.
1. [Load the extension](https://developer.chrome.com/extensions/getstarted#unpacked) in developer mode.
1. Authorize extension.

Diving further
--------------

Getting the code working for your extension is a little more work since this sample comes preloaded with an existing Chrome extension id and Google APIs client details.

1. Have a [Chrome extension published](https://developer.chrome.com/apps/app_identity#add_permissions) with `identity` permission. It can be a private extension that does nothing.
1. Install extension from the CWS and [get the `key`](https://developer.chrome.com/apps/app_identity#copy_key). Adding this to your unpacked extension source makes the development ID match what the Google APIs app expects.
1. [Register Google APIs client](https://developer.chrome.com/apps/app_identity#client_id) and enable the Google APIs you plan on using.
1. Set the [API client details](https://developer.chrome.com/apps/app_identity#update_manifest) in the manifest.
1. Authorize extension.

Notes
-----

* The URLs of the Google APIs you will be using must be whitelisted in the manifest.


<sub>Google product names and logos are owned by Google.</sub>
