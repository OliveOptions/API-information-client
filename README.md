# test .NET API client to get token information

This .NET client encapsulates the private and public methods exposed by the API.

It targets .NET Standard 2.0

Requires `Visual Studio 2017+`

### Unit Tests

Tests require a single environment variable set with a CSV of baseUrl, apiKey and secret.

This can be set from an elevated powershell prompt like so:

`[Environment]::SetEnvironmentVariable("IR_DOTNETCLIENTAPI_TEST_CONFIG", "<url>,<key>,<secret>", "Machine")`


### Sample Application

The sample application shows how to use the client in a simple WPF application.

Specify your API Key and API Secret in the Sample Application configuration file `SampleApplication.exe.config`.


