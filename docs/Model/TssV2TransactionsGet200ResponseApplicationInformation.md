# TssV2TransactionsGet200ResponseApplicationInformation

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **string** | The status of the submitted transaction. | [optional] 
**reasonCode** | **string** | Indicates the reason why a request succeeded or failed and possible action to take if a request fails.  For details, see the appendix of reason codes in the documentation for the relevant payment method. | [optional] 
**rCode** | **string** | Indicates whether the service request was successful. Possible values:  - &#x60;-1&#x60;: An error occurred. - &#x60;0&#x60;: The request was declined. - &#x60;1&#x60;: The request was successful.  For details, see &#x60;auth_rcode&#x60; field description in [Credit Card Services Using the SCMP API.](https://apps.cybersource.com/library/documentation/dev_guides/CC_Svcs_SCMP_API/html/) | [optional] 
**rFlag** | **string** | One-word description of the result of the application.  For details, see &#x60;auth_rflag&#x60; field description in [Credit Card Services Using the SCMP API.](https://apps.cybersource.com/library/documentation/dev_guides/CC_Svcs_SCMP_API/html/) | [optional] 
**applications** | [**\CyberSource\Model\TssV2TransactionsGet200ResponseApplicationInformationApplications[]**](TssV2TransactionsGet200ResponseApplicationInformationApplications.md) |  | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


