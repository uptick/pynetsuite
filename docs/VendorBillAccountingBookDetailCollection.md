# VendorBillAccountingBookDetailCollection


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**links** | [**List[NsLink]**](NsLink.md) |  | [optional] [readonly] 
**total_results** | **int** |  | [optional] [readonly] 
**count** | **int** |  | [optional] [readonly] 
**has_more** | **bool** |  | [optional] [readonly] 
**offset** | **int** |  | [optional] [readonly] 
**items** | [**List[VendorBillAccountingBookDetailElement]**](VendorBillAccountingBookDetailElement.md) |  | [optional] 

## Example

```python
from pynetsuite.models.vendor_bill_accounting_book_detail_collection import VendorBillAccountingBookDetailCollection

# TODO update the JSON string below
json = "{}"
# create an instance of VendorBillAccountingBookDetailCollection from a JSON string
vendor_bill_accounting_book_detail_collection_instance = VendorBillAccountingBookDetailCollection.from_json(json)
# print the JSON string representation of the object
print(VendorBillAccountingBookDetailCollection.to_json())

# convert the object into a dict
vendor_bill_accounting_book_detail_collection_dict = vendor_bill_accounting_book_detail_collection_instance.to_dict()
# create an instance of VendorBillAccountingBookDetailCollection from a dict
vendor_bill_accounting_book_detail_collection_from_dict = VendorBillAccountingBookDetailCollection.from_dict(vendor_bill_accounting_book_detail_collection_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


