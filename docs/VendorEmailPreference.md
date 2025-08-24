# VendorEmailPreference


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**ref_name** | **str** |  | [optional] 

## Example

```python
from pynetsuite.models.vendor_email_preference import VendorEmailPreference

# TODO update the JSON string below
json = "{}"
# create an instance of VendorEmailPreference from a JSON string
vendor_email_preference_instance = VendorEmailPreference.from_json(json)
# print the JSON string representation of the object
print(VendorEmailPreference.to_json())

# convert the object into a dict
vendor_email_preference_dict = vendor_email_preference_instance.to_dict()
# create an instance of VendorEmailPreference from a dict
vendor_email_preference_from_dict = VendorEmailPreference.from_dict(vendor_email_preference_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


