# CreditMemoSource


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**ref_name** | **str** |  | [optional] 

## Example

```python
from pynetsuite.models.credit_memo_source import CreditMemoSource

# TODO update the JSON string below
json = "{}"
# create an instance of CreditMemoSource from a JSON string
credit_memo_source_instance = CreditMemoSource.from_json(json)
# print the JSON string representation of the object
print(CreditMemoSource.to_json())

# convert the object into a dict
credit_memo_source_dict = credit_memo_source_instance.to_dict()
# create an instance of CreditMemoSource from a dict
credit_memo_source_from_dict = CreditMemoSource.from_dict(credit_memo_source_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


