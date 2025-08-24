# InvoiceExpCostCollection


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**links** | [**List[NsLink]**](NsLink.md) |  | [optional] [readonly] 
**total_results** | **int** |  | [optional] [readonly] 
**count** | **int** |  | [optional] [readonly] 
**has_more** | **bool** |  | [optional] [readonly] 
**offset** | **int** |  | [optional] [readonly] 
**items** | [**List[InvoiceExpCostElement]**](InvoiceExpCostElement.md) |  | [optional] 

## Example

```python
from pynetsuite.models.invoice_exp_cost_collection import InvoiceExpCostCollection

# TODO update the JSON string below
json = "{}"
# create an instance of InvoiceExpCostCollection from a JSON string
invoice_exp_cost_collection_instance = InvoiceExpCostCollection.from_json(json)
# print the JSON string representation of the object
print(InvoiceExpCostCollection.to_json())

# convert the object into a dict
invoice_exp_cost_collection_dict = invoice_exp_cost_collection_instance.to_dict()
# create an instance of InvoiceExpCostCollection from a dict
invoice_exp_cost_collection_from_dict = InvoiceExpCostCollection.from_dict(invoice_exp_cost_collection_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


