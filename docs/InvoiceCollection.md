# InvoiceCollection


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**total_results** | **int** |  | [optional] [readonly] 
**items** | [**List[Invoice]**](Invoice.md) | An array field that represents a collection of elements, for example, sublist lines, multiselect items, or search results. | [optional] 
**links** | [**List[NsLink]**](NsLink.md) |  | [optional] [readonly] 
**count** | **int** |  | [optional] [readonly] 
**has_more** | **bool** |  | [optional] [readonly] 
**offset** | **int** |  | [optional] [readonly] 

## Example

```python
from pynetsuite.models.invoice_collection import InvoiceCollection

# TODO update the JSON string below
json = "{}"
# create an instance of InvoiceCollection from a JSON string
invoice_collection_instance = InvoiceCollection.from_json(json)
# print the JSON string representation of the object
print(InvoiceCollection.to_json())

# convert the object into a dict
invoice_collection_dict = invoice_collection_instance.to_dict()
# create an instance of InvoiceCollection from a dict
invoice_collection_from_dict = InvoiceCollection.from_dict(invoice_collection_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


