# VendorRolesElement


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**links** | [**List[NsLink]**](NsLink.md) |  | [optional] [readonly] 
**sso_only** | **str** |  | [optional] 
**ws_only** | **str** |  | [optional] 
**master_role** | **int** |  | [optional] 
**deviceid_only** | **str** |  | [optional] 
**billing_warn** | **str** |  | [optional] 
**center_type** | **str** |  | [optional] 
**ref_name** | **str** |  | [optional] 
**selected_role** | [**NsResource**](NsResource.md) |  | [optional] 

## Example

```python
from pynetsuite.models.vendor_roles_element import VendorRolesElement

# TODO update the JSON string below
json = "{}"
# create an instance of VendorRolesElement from a JSON string
vendor_roles_element_instance = VendorRolesElement.from_json(json)
# print the JSON string representation of the object
print(VendorRolesElement.to_json())

# convert the object into a dict
vendor_roles_element_dict = vendor_roles_element_instance.to_dict()
# create an instance of VendorRolesElement from a dict
vendor_roles_element_from_dict = VendorRolesElement.from_dict(vendor_roles_element_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


