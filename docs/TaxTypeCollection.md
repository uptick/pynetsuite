# TaxTypeCollection


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**total_results** | **int** |  | [optional] [readonly] 
**items** | [**List[TaxType]**](TaxType.md) | An array field that represents a collection of elements, for example, sublist lines, multiselect items, or search results. | [optional] 
**links** | [**List[NsLink]**](NsLink.md) |  | [optional] [readonly] 
**count** | **int** |  | [optional] [readonly] 
**has_more** | **bool** |  | [optional] [readonly] 
**offset** | **int** |  | [optional] [readonly] 

## Example

```python
from pynetsuite.models.tax_type_collection import TaxTypeCollection

# TODO update the JSON string below
json = "{}"
# create an instance of TaxTypeCollection from a JSON string
tax_type_collection_instance = TaxTypeCollection.from_json(json)
# print the JSON string representation of the object
print(TaxTypeCollection.to_json())

# convert the object into a dict
tax_type_collection_dict = tax_type_collection_instance.to_dict()
# create an instance of TaxTypeCollection from a dict
tax_type_collection_from_dict = TaxTypeCollection.from_dict(tax_type_collection_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


