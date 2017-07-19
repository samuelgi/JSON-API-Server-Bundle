Changelog
=========

## Version 2.0.0
* updated dependency `enm/json-api-server` to version `2.0.0`
* replaced all controller actions with "jsonApiAction"
* added `JsonApiServerDecorator` to use symfony http foundation with json api
* all services except the controller and exception handler are now private
* added `ResourceProviderPass`
* renamed service tag "json_api.resource_provider" to "json_api_server.resource_provider"
* added service tag "json_api_server.request_handler"
* added bundle configuration
* replaced all routes with route `enm.json_api`