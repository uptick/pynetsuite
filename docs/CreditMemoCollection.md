# CreditMemoCollection


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**total_results** | **int** |  | [optional] [readonly] 
**items** | [**List[CreditMemo]**](CreditMemo.md) | An array field that represents a collection of elements, for example, sublist lines, multiselect items, or search results. | [optional] 
**links** | [**List[NsLink]**](NsLink.md) |  | [optional] [readonly] 
**count** | **int** |  | [optional] [readonly] 
**has_more** | **bool** |  | [optional] [readonly] 
**offset** | **int** |  | [optional] [readonly] 

## Example

```python
from pynetsuite.models.credit_memo_collection import CreditMemoCollection

# TODO update the JSON string below
json = "{}"
# create an instance of CreditMemoCollection from a JSON string
credit_memo_collection_instance = CreditMemoCollection.from_json(json)
# print the JSON string representation of the object
print(CreditMemoCollection.to_json())

# convert the object into a dict
credit_memo_collection_dict = credit_memo_collection_instance.to_dict()
# create an instance of CreditMemoCollection from a dict
credit_memo_collection_from_dict = CreditMemoCollection.from_dict(credit_memo_collection_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


