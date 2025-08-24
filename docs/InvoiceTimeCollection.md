# InvoiceTimeCollection


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**links** | [**List[NsLink]**](NsLink.md) |  | [optional] [readonly] 
**total_results** | **int** |  | [optional] [readonly] 
**count** | **int** |  | [optional] [readonly] 
**has_more** | **bool** |  | [optional] [readonly] 
**offset** | **int** |  | [optional] [readonly] 
**items** | [**List[InvoiceTimeElement]**](InvoiceTimeElement.md) |  | [optional] 

## Example

```python
from pynetsuite.models.invoice_time_collection import InvoiceTimeCollection

# TODO update the JSON string below
json = "{}"
# create an instance of InvoiceTimeCollection from a JSON string
invoice_time_collection_instance = InvoiceTimeCollection.from_json(json)
# print the JSON string representation of the object
print(InvoiceTimeCollection.to_json())

# convert the object into a dict
invoice_time_collection_dict = invoice_time_collection_instance.to_dict()
# create an instance of InvoiceTimeCollection from a dict
invoice_time_collection_from_dict = InvoiceTimeCollection.from_dict(invoice_time_collection_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


