---
title:  Fair Web Services Certification - Manifest
layout: certification
---
## Manifest

To provide a standardized way of expressing compliance with the Fair Web Services Certification there is a formal definition of a manifest file which each service can put on their site. It's a HTML file at a standard location with embedded meta tags containing detailed information about how the service complies with the five sections of the Fair Web Services Specification. While the HTML part is free form and can be designed by the service provider as needed the meta tags follow a formal specification and need to be present in order to be a valid manifest.

### Location

The file is served as `is_a_fair_web_service.html` on the root level of the services` web site. See the example of the FWS site: http://fairwebservices.org/is_a_fair_web_service.html.

### Fields

The following fields need to be present and contain valid data:

* API endpoint
* API documentation
* Documentation how to export data
* Link to succession provision
* Link to terms of use
* Link to privacy statement
* Link to privacy settings
* Instructions how to report security issues
* Report about security issues
* Advertisement policy

### Example

```
<html>
<head prefix="fws: http://fairwebservices.org/ns#">
<title>Example FWS Manifest</title>
<meta property="fws:api_endpoint" content="https://example.com/api/v1" />
<meta property="fws:api_docs" content="https://docs.example.com/api" />
<meta property="fws:data_export" content="https://example.com/settings/export" />
<meta property="fws:succession_provision" content="https://example.com/tou.html#succession" />
<meta property="fws:terms_of_use" content="https://example.com/tou.html" />
<meta property="fws:privacy_statement" content="https://example.com/privacy.html" />
<meta property="fws:privacy_settings" content="https://example.com/settings/privacy" />
<meta property="fws:security_report" content="https://example.com/blog/security" />
<meta property="fws:security_contact" content="mailto:security@example.com" />
<meta property="fws:advertisement_policy" content="https://example.com/privacy.html#advertising" />
...
</head>
...
</html>
```
