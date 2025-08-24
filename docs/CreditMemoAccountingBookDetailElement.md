# CreditMemoAccountingBookDetailElement


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**links** | [**List[NsLink]**](NsLink.md) |  | [optional] [readonly] 
**exchange_rate** | **float** |  | [optional] 
**ref_name** | **str** |  | [optional] 
**accounting_book** | [**NsResource**](NsResource.md) |  | [optional] 
**subsidiary** | [**NsResource**](NsResource.md) |  | [optional] 

## Example

```python
from pynetsuite.models.credit_memo_accounting_book_detail_element import CreditMemoAccountingBookDetailElement

# TODO update the JSON string below
json = "{}"
# create an instance of CreditMemoAccountingBookDetailElement from a JSON string
credit_memo_accounting_book_detail_element_instance = CreditMemoAccountingBookDetailElement.from_json(json)
# print the JSON string representation of the object
print(CreditMemoAccountingBookDetailElement.to_json())

# convert the object into a dict
credit_memo_accounting_book_detail_element_dict = credit_memo_accounting_book_detail_element_instance.to_dict()
# create an instance of CreditMemoAccountingBookDetailElement from a dict
credit_memo_accounting_book_detail_element_from_dict = CreditMemoAccountingBookDetailElement.from_dict(credit_memo_accounting_book_detail_element_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


