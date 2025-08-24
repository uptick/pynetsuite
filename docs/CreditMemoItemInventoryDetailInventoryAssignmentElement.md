# CreditMemoItemInventoryDetailInventoryAssignmentElement


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**links** | [**List[NsLink]**](NsLink.md) |  | [optional] [readonly] 
**pack_carton** | **str** |  | [optional] 
**quantity** | **float** |  | [optional] 
**expiration_date** | **date** |  | [optional] 
**inventory_detail** | **int** |  | [optional] 
**receipt_inventory_number** | **str** |  | [optional] 
**internal_id** | **int** |  | [optional] 
**quantity_available** | **float** |  | [optional] 
**pick_carton** | **str** |  | [optional] 
**ref_name** | **str** |  | [optional] 
**inventory_status** | [**NsResource**](NsResource.md) |  | [optional] 
**to_bin_number** | [**NsResource**](NsResource.md) |  | [optional] 
**to_inventory_status** | [**NsResource**](NsResource.md) |  | [optional] 
**bin_number** | [**NsResource**](NsResource.md) |  | [optional] 
**issue_inventory_number** | [**NsResource**](NsResource.md) |  | [optional] 

## Example

```python
from pynetsuite.models.credit_memo_item_inventory_detail_inventory_assignment_element import CreditMemoItemInventoryDetailInventoryAssignmentElement

# TODO update the JSON string below
json = "{}"
# create an instance of CreditMemoItemInventoryDetailInventoryAssignmentElement from a JSON string
credit_memo_item_inventory_detail_inventory_assignment_element_instance = CreditMemoItemInventoryDetailInventoryAssignmentElement.from_json(json)
# print the JSON string representation of the object
print(CreditMemoItemInventoryDetailInventoryAssignmentElement.to_json())

# convert the object into a dict
credit_memo_item_inventory_detail_inventory_assignment_element_dict = credit_memo_item_inventory_detail_inventory_assignment_element_instance.to_dict()
# create an instance of CreditMemoItemInventoryDetailInventoryAssignmentElement from a dict
credit_memo_item_inventory_detail_inventory_assignment_element_from_dict = CreditMemoItemInventoryDetailInventoryAssignmentElement.from_dict(credit_memo_item_inventory_detail_inventory_assignment_element_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


