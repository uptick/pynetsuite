# VendorBillApprovalStatus


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**ref_name** | **str** |  | [optional] 

## Example

```python
from pynetsuite.models.vendor_bill_approval_status import VendorBillApprovalStatus

# TODO update the JSON string below
json = "{}"
# create an instance of VendorBillApprovalStatus from a JSON string
vendor_bill_approval_status_instance = VendorBillApprovalStatus.from_json(json)
# print the JSON string representation of the object
print(VendorBillApprovalStatus.to_json())

# convert the object into a dict
vendor_bill_approval_status_dict = vendor_bill_approval_status_instance.to_dict()
# create an instance of VendorBillApprovalStatus from a dict
vendor_bill_approval_status_from_dict = VendorBillApprovalStatus.from_dict(vendor_bill_approval_status_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


