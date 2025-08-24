# CreditMemoStatus


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**ref_name** | **str** |  | [optional] 

## Example

```python
from pynetsuite.models.credit_memo_status import CreditMemoStatus

# TODO update the JSON string below
json = "{}"
# create an instance of CreditMemoStatus from a JSON string
credit_memo_status_instance = CreditMemoStatus.from_json(json)
# print the JSON string representation of the object
print(CreditMemoStatus.to_json())

# convert the object into a dict
credit_memo_status_dict = credit_memo_status_instance.to_dict()
# create an instance of CreditMemoStatus from a dict
credit_memo_status_from_dict = CreditMemoStatus.from_dict(credit_memo_status_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


