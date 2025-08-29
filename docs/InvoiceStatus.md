# InvoiceStatus


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**ref_name** | **str** |  | [optional] 

## Example

```python
from pynetsuite.models.invoice_status import InvoiceStatus

# TODO update the JSON string below
json = "{}"
# create an instance of InvoiceStatus from a JSON string
invoice_status_instance = InvoiceStatus.from_json(json)
# print the JSON string representation of the object
print(InvoiceStatus.to_json())

# convert the object into a dict
invoice_status_dict = invoice_status_instance.to_dict()
# create an instance of InvoiceStatus from a dict
invoice_status_from_dict = InvoiceStatus.from_dict(invoice_status_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


