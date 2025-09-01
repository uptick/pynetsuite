# Term


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**is_inactive** | **bool** | Check this box to remove all references to this record from your account. You can reactivate the record at any time. | [optional] 
**discount_percent_date_driven** | **float** | For date driven terms, enter the percentage discount if the invoice is paid early. | [optional] 
**last_modified_date** | **datetime** |  | [optional] 
**external_id** | **str** |  | [optional] 
**tname** | **str** |  | [optional] 
**discount_percent** | **float** | For standard terms, enter the percentage discount if the invoice is paid early. | [optional] 
**date_driven** | [**TermDateDriven**](TermDateDriven.md) |  | [optional] 
**due_next_month_if_within_days** | **int** | For date driven terms, enter the number of days before the due date that the invoice can be postponed until the next month&amp;apos;s due date. For example, if invoices are due on the 30th of each month and you enter 5 in this field, then invoices issued between the 25th and 30th are due for payment by the 30th of the following month. For another example, Day of Month Net Due &#x3D; 15 and Due Next Month if Within Days &#x3D; 30 Date range within 30 days: 5/16-6/14 move to 7/15 6/15-7/15 move to 8/15 8/16-9/14 move to 10/15 9/15-10/15 move to 11/15 10/16-11/14 move to 12/15 11/15-12/15 move to 1/5 | [optional] 
**days_until_expiry** | **int** | For standard terms, enter the number of days the early payment discount is available. For example, if the early payment discount is available for 15 days after the bill is issued, enter 15 in this field. | [optional] 
**day_of_month_net_due** | **int** | For date driven terms, enter the day of the month when the net amount of the invoice is due. If you enter a date that does not exist in the month the transaction is due, the last day of the month becomes the due date. | [optional] 
**name** | **str** | Enter the name for this record. This name appears in lists that include this record. | [optional] 
**days_until_net_due** | **int** | Enter the number of days until the net amount of the bill becomes due. For example, if you are creating a term of Net 30, enter 30 in this field. | [optional] 
**longitemtype** | **str** |  | [optional] 
**id** | **str** |  | [optional] 
**preferred** | **bool** | Check this box to make this term or message show by default on sales transactions you create. Note: Terms set on customer records override terms marked as preferred. | [optional] 
**day_discount_expires** | **int** | If you offer a discount for early payment under date driven terms, enter the last day of the month the early payment discount is available. For example, if the early payment discount is available through the 20th of each month, enter 20 in this field. | [optional] 
**ref_name** | **str** |  | [optional] 
**links** | [**List[NsLink]**](NsLink.md) |  | [optional] [readonly] 

## Example

```python
from pynetsuite.models.term import Term

# TODO update the JSON string below
json = "{}"
# create an instance of Term from a JSON string
term_instance = Term.from_json(json)
# print the JSON string representation of the object
print(Term.to_json())

# convert the object into a dict
term_dict = term_instance.to_dict()
# create an instance of Term from a dict
term_from_dict = Term.from_dict(term_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


