# InvoiceItemCollection


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**links** | [**List[NsLink]**](NsLink.md) |  | [optional] [readonly] 
**total_results** | **int** |  | [optional] [readonly] 
**count** | **int** |  | [optional] [readonly] 
**has_more** | **bool** |  | [optional] [readonly] 
**offset** | **int** |  | [optional] [readonly] 
**items** | [**List[InvoiceItemElement]**](InvoiceItemElement.md) |  | [optional] 

## Example

```python
from pynetsuite.models.invoice_item_collection import InvoiceItemCollection

# TODO update the JSON string below
json = "{}"
# create an instance of InvoiceItemCollection from a JSON string
invoice_item_collection_instance = InvoiceItemCollection.from_json(json)
# print the JSON string representation of the object
print(InvoiceItemCollection.to_json())

# convert the object into a dict
invoice_item_collection_dict = invoice_item_collection_instance.to_dict()
# create an instance of InvoiceItemCollection from a dict
invoice_item_collection_from_dict = InvoiceItemCollection.from_dict(invoice_item_collection_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


