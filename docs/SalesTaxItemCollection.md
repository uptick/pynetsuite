# SalesTaxItemCollection


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**total_results** | **int** |  | [optional] [readonly] 
**items** | [**List[SalesTaxItem]**](SalesTaxItem.md) | An array field that represents a collection of elements, for example, sublist lines, multiselect items, or search results. | [optional] 
**links** | [**List[NsLink]**](NsLink.md) |  | [optional] [readonly] 
**count** | **int** |  | [optional] [readonly] 
**has_more** | **bool** |  | [optional] [readonly] 
**offset** | **int** |  | [optional] [readonly] 

## Example

```python
from pynetsuite.models.sales_tax_item_collection import SalesTaxItemCollection

# TODO update the JSON string below
json = "{}"
# create an instance of SalesTaxItemCollection from a JSON string
sales_tax_item_collection_instance = SalesTaxItemCollection.from_json(json)
# print the JSON string representation of the object
print(SalesTaxItemCollection.to_json())

# convert the object into a dict
sales_tax_item_collection_dict = sales_tax_item_collection_instance.to_dict()
# create an instance of SalesTaxItemCollection from a dict
sales_tax_item_collection_from_dict = SalesTaxItemCollection.from_dict(sales_tax_item_collection_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


