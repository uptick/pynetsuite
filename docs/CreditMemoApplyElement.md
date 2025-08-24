# CreditMemoApplyElement


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**links** | [**List[NsLink]**](NsLink.md) |  | [optional] [readonly] 
**total** | **float** |  | [optional] 
**amount** | **float** |  | [optional] 
**apply_date** | **date** |  | [optional] 
**ref_num** | **str** |  | [optional] 
**apply** | **bool** |  | [optional] 
**due** | **float** |  | [optional] 
**line** | **int** |  | [optional] 
**created_from** | **str** |  | [optional] 
**currency** | **str** |  | [optional] 
**type** | **str** |  | [optional] 
**ref_name** | **str** |  | [optional] 
**doc** | [**NsResource**](NsResource.md) |  | [optional] 

## Example

```python
from pynetsuite.models.credit_memo_apply_element import CreditMemoApplyElement

# TODO update the JSON string below
json = "{}"
# create an instance of CreditMemoApplyElement from a JSON string
credit_memo_apply_element_instance = CreditMemoApplyElement.from_json(json)
# print the JSON string representation of the object
print(CreditMemoApplyElement.to_json())

# convert the object into a dict
credit_memo_apply_element_dict = credit_memo_apply_element_instance.to_dict()
# create an instance of CreditMemoApplyElement from a dict
credit_memo_apply_element_from_dict = CreditMemoApplyElement.from_dict(credit_memo_apply_element_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


