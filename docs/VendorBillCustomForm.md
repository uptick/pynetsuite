# VendorBillCustomForm


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**ref_name** | **str** |  | [optional] 

## Example

```python
from pynetsuite.models.vendor_bill_custom_form import VendorBillCustomForm

# TODO update the JSON string below
json = "{}"
# create an instance of VendorBillCustomForm from a JSON string
vendor_bill_custom_form_instance = VendorBillCustomForm.from_json(json)
# print the JSON string representation of the object
print(VendorBillCustomForm.to_json())

# convert the object into a dict
vendor_bill_custom_form_dict = vendor_bill_custom_form_instance.to_dict()
# create an instance of VendorBillCustomForm from a dict
vendor_bill_custom_form_from_dict = VendorBillCustomForm.from_dict(vendor_bill_custom_form_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


