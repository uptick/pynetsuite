# InvoiceAccountingBookDetailElement


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**links** | [**List[NsLink]**](NsLink.md) |  | [optional] [readonly] 
**exchange_rate** | **float** |  | [optional] 
**ref_name** | **str** |  | [optional] 
**subsidiary** | [**NsResource**](NsResource.md) |  | [optional] 
**accounting_book** | [**NsResource**](NsResource.md) |  | [optional] 

## Example

```python
from pynetsuite.models.invoice_accounting_book_detail_element import InvoiceAccountingBookDetailElement

# TODO update the JSON string below
json = "{}"
# create an instance of InvoiceAccountingBookDetailElement from a JSON string
invoice_accounting_book_detail_element_instance = InvoiceAccountingBookDetailElement.from_json(json)
# print the JSON string representation of the object
print(InvoiceAccountingBookDetailElement.to_json())

# convert the object into a dict
invoice_accounting_book_detail_element_dict = invoice_accounting_book_detail_element_instance.to_dict()
# create an instance of InvoiceAccountingBookDetailElement from a dict
invoice_accounting_book_detail_element_from_dict = InvoiceAccountingBookDetailElement.from_dict(invoice_accounting_book_detail_element_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


