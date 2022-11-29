# Sparkplug Compatibility Program — "Get Listed" Requests

This repository is used to manage "Get Listed" requests for Sparkplug compatible products.

For more information about "Get Listed" requests, please visit https://sparkplug.eclipse.org/compatibility/get-listed. 

If you have questions, you can contact [sparkplug@eclipse.org](mailto:sparkplug@eclipse.org)

## Requirements 

Before submitting a "Get Listed" request, you need to fulfill the following requirements:
- Your organization is a member of the [Eclipse Foundation](https://eclipse.org) and the [Sparkplug Working Group](https://sparkplug.eclipse.org)
- Your organization signed the [Sparkplug Compatibility Trademark License Agreement](https://app.hellosign.com/s/2QZzWz64)
- Your product passes the [Sparkplug Technology Compatibility Kit (TCK)](https://github.com/eclipse-sparkplug/sparkplug/tree/master/tck)

Your request will only considered if the three requirements above are fulfilled. Requests older than three months that do not fulfill the requirements will be closed.


## Request Template

[Click here](https://github.com/eclipse-sparkplug/sparkplug.listings/issues/new?assignees=&labels=getlisted%2Ctriage&template=GET-LISTED.yml&title=Get+Listed+Request%3A+%5BADD+DETAILS+HERE%5D) to create a new issue using the template.

You must submit one request per product. Products can be devices or software.  

You will need to provide the following information in your request:
- Organization name and URL for its website
- Name of the product, version, and URL leading to product information on your website
- URL to download the product's logo (if applicable)
- Version of the specification used and download URL
- Sparkplug conformance profile(s) implemented by the product (Edge Node, Host Application, Sparkplug-compliant MQTT server, Sparkplug-aware MQTT server)
- TCK version used, digital SHA-256 Fingerprint, and download URL
- Public URL for your TCK Results Summary
- Summary decription of the environment used for compatibility testing (Devices, Software Components, Operating Systems, Cloud Services, etc.)

You will also need to accept the terms of the [Eclipse Fondation TCK License](https://www.eclipse.org/legal/tck.php) to submit your request.

Finally, you will have to attest that all TCK requirements have been met, including any compatibility rules.

## Process
Once your request has been submitted, a committer of the Sparkplug Specification project will review it. If they have questions or need additional information, they will comment on your request. Please make sure to monitor your emails.

After it has been approved by a committer, your request will be passed to an Eclipse webmaster for processing. The webmaster will add your product to the list of compatible products on the website.

## Challenges
If you feel the TCK does not properly test one or several of the normative statements found in the specification, you can fill a challenge.

The following scenarios are considered in scope for test challenges:

- Claims that a test assertion conflicts with the specification.
- Claims that a test asserts requirements over and above that of the specification.
- Claims that an assertion of the specification is not sufficiently implementable.
- Claims that a test is not portable or depends on a particular implementation.

Please review the [Sparkplug TCK process](https://sparkplug.eclipse.org/specification/tck-process/) for more information.
