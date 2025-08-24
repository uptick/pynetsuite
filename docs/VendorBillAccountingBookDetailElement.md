# VendorBillAccountingBookDetailElement


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
from pynetsuite.models.vendor_bill_accounting_book_detail_element import VendorBillAccountingBookDetailElement

# TODO update the JSON string below
json = "{}"
# create an instance of VendorBillAccountingBookDetailElement from a JSON string
vendor_bill_accounting_book_detail_element_instance = VendorBillAccountingBookDetailElement.from_json(json)
# print the JSON string representation of the object
print(VendorBillAccountingBookDetailElement.to_json())

# convert the object into a dict
vendor_bill_accounting_book_detail_element_dict = vendor_bill_accounting_book_detail_element_instance.to_dict()
# create an instance of VendorBillAccountingBookDetailElement from a dict
vendor_bill_accounting_book_detail_element_from_dict = VendorBillAccountingBookDetailElement.from_dict(vendor_bill_accounting_book_detail_element_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


