# CustomerContactRolesElement


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**links** | [**List[NsLink]**](NsLink.md) |  | [optional] [readonly] 
**contact_name** | **str** |  | [optional] 
**give_access** | **bool** |  | [optional] 
**password** | **str** |  | [optional] 
**password_confirm** | **str** |  | [optional] 
**email** | **str** |  | [optional] 
**ref_name** | **str** |  | [optional] 
**role** | [**NsResource**](NsResource.md) |  | [optional] 
**contact** | [**NsResource**](NsResource.md) |  | [optional] 

## Example

```python
from pynetsuite.models.customer_contact_roles_element import CustomerContactRolesElement

# TODO update the JSON string below
json = "{}"
# create an instance of CustomerContactRolesElement from a JSON string
customer_contact_roles_element_instance = CustomerContactRolesElement.from_json(json)
# print the JSON string representation of the object
print(CustomerContactRolesElement.to_json())

# convert the object into a dict
customer_contact_roles_element_dict = customer_contact_roles_element_instance.to_dict()
# create an instance of CustomerContactRolesElement from a dict
customer_contact_roles_element_from_dict = CustomerContactRolesElement.from_dict(customer_contact_roles_element_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


