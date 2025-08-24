# InvoiceBillingAddressCountry


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**ref_name** | **str** |  | [optional] 

## Example

```python
from pynetsuite.models.invoice_billing_address_country import InvoiceBillingAddressCountry

# TODO update the JSON string below
json = "{}"
# create an instance of InvoiceBillingAddressCountry from a JSON string
invoice_billing_address_country_instance = InvoiceBillingAddressCountry.from_json(json)
# print the JSON string representation of the object
print(InvoiceBillingAddressCountry.to_json())

# convert the object into a dict
invoice_billing_address_country_dict = invoice_billing_address_country_instance.to_dict()
# create an instance of InvoiceBillingAddressCountry from a dict
invoice_billing_address_country_from_dict = InvoiceBillingAddressCountry.from_dict(invoice_billing_address_country_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


