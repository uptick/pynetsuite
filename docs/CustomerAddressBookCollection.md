# CustomerAddressBookCollection


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**links** | [**List[NsLink]**](NsLink.md) |  | [optional] [readonly] 
**total_results** | **int** |  | [optional] [readonly] 
**count** | **int** |  | [optional] [readonly] 
**has_more** | **bool** |  | [optional] [readonly] 
**offset** | **int** |  | [optional] [readonly] 
**items** | [**List[CustomerAddressBookElement]**](CustomerAddressBookElement.md) |  | [optional] 

## Example

```python
from pynetsuite.models.customer_address_book_collection import CustomerAddressBookCollection

# TODO update the JSON string below
json = "{}"
# create an instance of CustomerAddressBookCollection from a JSON string
customer_address_book_collection_instance = CustomerAddressBookCollection.from_json(json)
# print the JSON string representation of the object
print(CustomerAddressBookCollection.to_json())

# convert the object into a dict
customer_address_book_collection_dict = customer_address_book_collection_instance.to_dict()
# create an instance of CustomerAddressBookCollection from a dict
customer_address_book_collection_from_dict = CustomerAddressBookCollection.from_dict(customer_address_book_collection_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


