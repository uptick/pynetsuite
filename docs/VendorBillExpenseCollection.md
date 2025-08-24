# VendorBillExpenseCollection


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**links** | [**List[NsLink]**](NsLink.md) |  | [optional] [readonly] 
**total_results** | **int** |  | [optional] [readonly] 
**count** | **int** |  | [optional] [readonly] 
**has_more** | **bool** |  | [optional] [readonly] 
**offset** | **int** |  | [optional] [readonly] 
**items** | [**List[VendorBillExpenseElement]**](VendorBillExpenseElement.md) |  | [optional] 

## Example

```python
from pynetsuite.models.vendor_bill_expense_collection import VendorBillExpenseCollection

# TODO update the JSON string below
json = "{}"
# create an instance of VendorBillExpenseCollection from a JSON string
vendor_bill_expense_collection_instance = VendorBillExpenseCollection.from_json(json)
# print the JSON string representation of the object
print(VendorBillExpenseCollection.to_json())

# convert the object into a dict
vendor_bill_expense_collection_dict = vendor_bill_expense_collection_instance.to_dict()
# create an instance of VendorBillExpenseCollection from a dict
vendor_bill_expense_collection_from_dict = VendorBillExpenseCollection.from_dict(vendor_bill_expense_collection_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


