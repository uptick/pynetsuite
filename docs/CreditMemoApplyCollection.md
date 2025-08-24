# CreditMemoApplyCollection


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**links** | [**List[NsLink]**](NsLink.md) |  | [optional] [readonly] 
**total_results** | **int** |  | [optional] [readonly] 
**count** | **int** |  | [optional] [readonly] 
**has_more** | **bool** |  | [optional] [readonly] 
**offset** | **int** |  | [optional] [readonly] 
**items** | [**List[CreditMemoApplyElement]**](CreditMemoApplyElement.md) |  | [optional] 

## Example

```python
from pynetsuite.models.credit_memo_apply_collection import CreditMemoApplyCollection

# TODO update the JSON string below
json = "{}"
# create an instance of CreditMemoApplyCollection from a JSON string
credit_memo_apply_collection_instance = CreditMemoApplyCollection.from_json(json)
# print the JSON string representation of the object
print(CreditMemoApplyCollection.to_json())

# convert the object into a dict
credit_memo_apply_collection_dict = credit_memo_apply_collection_instance.to_dict()
# create an instance of CreditMemoApplyCollection from a dict
credit_memo_apply_collection_from_dict = CreditMemoApplyCollection.from_dict(credit_memo_apply_collection_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


