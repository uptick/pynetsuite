# CustomerContactRolesCollection


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**links** | [**List[NsLink]**](NsLink.md) |  | [optional] [readonly] 
**total_results** | **int** |  | [optional] [readonly] 
**count** | **int** |  | [optional] [readonly] 
**has_more** | **bool** |  | [optional] [readonly] 
**offset** | **int** |  | [optional] [readonly] 
**items** | [**List[CustomerContactRolesElement]**](CustomerContactRolesElement.md) |  | [optional] 

## Example

```python
from pynetsuite.models.customer_contact_roles_collection import CustomerContactRolesCollection

# TODO update the JSON string below
json = "{}"
# create an instance of CustomerContactRolesCollection from a JSON string
customer_contact_roles_collection_instance = CustomerContactRolesCollection.from_json(json)
# print the JSON string representation of the object
print(CustomerContactRolesCollection.to_json())

# convert the object into a dict
customer_contact_roles_collection_dict = customer_contact_roles_collection_instance.to_dict()
# create an instance of CustomerContactRolesCollection from a dict
customer_contact_roles_collection_from_dict = CustomerContactRolesCollection.from_dict(customer_contact_roles_collection_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


