
# Syncano API Postman Collection

[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/700c0727c26520f21ab0#?env%5BSyncano%20API%20-%20My%20Instance%5D=W3sidHlwZSI6InRleHQiLCJlbmFibGVkIjp0cnVlLCJrZXkiOiJzeW5jYW5vLXVybCIsInZhbHVlIjoiaHR0cHM6Ly9hcGkuc3luY2Fuby5pby92MS4xLyJ9LHsidHlwZSI6InRleHQiLCJlbmFibGVkIjp0cnVlLCJrZXkiOiJpbnN0YW5jZS1uYW1lIiwidmFsdWUiOiI8PFlPVVIgSU5TVEFOQ0UgTkFNRT4+In0seyJ0eXBlIjoidGV4dCIsImVuYWJsZWQiOnRydWUsImtleSI6InVzZXIta2V5IiwidmFsdWUiOiI8PFVTRVIgS0VZPj4ifSx7InR5cGUiOiJ0ZXh0IiwiZW5hYmxlZCI6dHJ1ZSwia2V5IjoiYmFzaWMtYXBpLWtleSIsInZhbHVlIjoiPDxCQVNJQyBJTlNUQU5DRSBLRVk+PiJ9LHsidHlwZSI6InRleHQiLCJlbmFibGVkIjp0cnVlLCJrZXkiOiJ1c2VycmVnLWFwaS1rZXkiLCJ2YWx1ZSI6Ijw8VVNFUiBSRUcgSU5TVEFOQ0UgS0VZPj4ifV0=)

## Installing postman.
Select an option below:

* [Google store - Chrome Web Browser Plugin](https://chrome.google.com/webstore/detail/postman/fhbjgbiflinjbdggehcddcbncdddomop?hl=en)
* [Postman download page](https://www.getpostman.com/)

## Main screen of the postman app.

* The most important button is the 'Import' - on the top left on the bar;

![Main screen](images/howto/postman_main_screen.png)

## Import environments.

* Click 'Import'.
* Choose 'Import Folder' and navigate to the enironments/ in this repo.
* Click 'Upload'
* Done - you may have a feeling that nothing happens, but on the top right your envs should appers in the dropdown select.

![Import environments](images/howto/postman_import_envs.png)

## Import schema definitions.

* Click 'Import'
* Choose 'Import File' and navigate for the file: Syncano-API-V1.json.postman_collection in this repo under the definitions/
* Click 'Upload'
* Done - your schema should appear in the side panel

![Import definitions](images/howto/postman_import_schema.png)

## Updating the environments. You need to provide an api_key for your envs - default one is 'xxxx'

* Click on the top left dropdown and pick 'Manage environments'
* choose one of the env (or all of them - one by one) and click on them
* in the value column with name api_key - provide your api_key
* you can set here also 'instance' value for a valid instance; or overwrite them in the url directly on the request screen;

![Import definitions](images/howto/postman_manage_envs.png)

![Import definitions](images/howto/postman_api_key_set.png)

## Use your calls! One to rule them all.

* Choose right env: the one you just set up in the environment dropdown;
* In the side panel choose an interesting request: "instance_list" for example:
* Click 'Send' button :)
* Done;

![Import definitions](images/howto/postman_make_get_query.png)

## Making POST, PUT, PATCH query is also simple: just go to the 'Body' tab and fill all needed parameters;
