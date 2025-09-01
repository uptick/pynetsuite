# Account


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**is_inactive** | **bool** | Check this box to inactivate this account. Inactive accounts do not show in lists on transactions and records. | [optional] 
**is_summary** | **bool** | Check this box to make this account record solely for reporting purposes. Summary accounts are useful when you want to create a non-posting, inactive parent account that has active child accounts. If you do not have a OneWorld account, new summary accounts cannot have an opening balance, but you can convert an existing account with a transaction balance into a summary account. In this case, you cannot post additional transactions to the account. Summary accounts appear with their children in the chart of accounts list. You cannot merge a summary account into another account. | [optional] 
**s_bank_name** | **str** | Enter the name of your bank. | [optional] 
**opening_balance** | **float** | Enter an opening balance for this account. | [optional] 
**tran_date** | **date** | Enter the date of the opening balance of this account. | [optional] 
**external_id** | **str** | Returns the account&amp;apos;s external ID, if one is assigned. | [optional] 
**s_bank_routing_number** | **str** | Enter the 9-digit routing number for this bank account. | [optional] 
**description** | **str** | Enter a description for this account. You can enter up to 255 alphanumeric characters. | [optional] 
**eliminate** | **bool** | Check this box to make this account an intercompany account. Intercompany accounts are used to record transactions between subsidiaries. You can post both intercompany transactions and non-intercompany transactions to most intercompany accounts. Intercompany Accounts Receivable and Intercompany Accounts Payable, however, can be used only for recording amounts that are candidates for eliminations. For details, see the help topic Intercompany Accounts. | [optional] 
**inventory** | **bool** | If this will be an Other Current Asset account and you want the balance of this account included in the total balance of the Inventory KPI, select the Inventory box. | [optional] 
**custrecord_ff_sc_acc_srvc_for_taxation** | **bool** |  | [optional] 
**revalue** | **bool** | Check this box to select this account for open balance currency revaluation. | [optional] 
**s_bank_company_id** | **str** | Enter the bank account number, up to 20 digits. | [optional] 
**acct_number** | **str** | Enter the number to identify this account. The number can be alphanumeric. The maximum number of characters is 60. | [optional] 
**cur_doc_num** | **int** | Enter a number to reset the default check number that appears on transactions such as checks and bill payments. By default, this field shows the highest check number in the account plus one. The number you enter in the Next Check Number field of the account record determines the number that appears in the Check Number field on transactions linked to that account. | [optional] 
**s_spec_acct** | [**AccountSSpecAcct**](AccountSSpecAcct.md) |  | [optional] 
**id** | **str** | Returns the account&amp;apos;s internal ID. | [optional] 
**account_search_display_name_copy** | **str** | Returns the account number and name, as it appears in searches. | [optional] 
**last_modified_date** | **datetime** | Returns the date on which the account record was last modified. | [optional] 
**general_rate** | [**AccountGeneralRate**](AccountGeneralRate.md) |  | [optional] 
**cash_flow_rate** | [**AccountGeneralRate**](AccountGeneralRate.md) |  | [optional] 
**acct_type** | [**AccountAcctType**](AccountAcctType.md) |  | [optional] 
**include_children** | **bool** | Check the Include Children box to share the account with all the sub-subsidiaries associated with each subsidiary selected in the Subsidiary field. | [optional] 
**account_search_display_name** | **str** | Returns the account number and name, as it appears in searches. The returned name is a link to the account record. | [optional] 
**unit** | **str** | This field displays the base unit assigned to the Unit Type. The default unit cannot be changed. | [optional] 
**display_name_with_hierarchy** | **str** | Returns the display name of the account in order of hierarchy. Accounts are returned grouped. If you have three statistical accounts, 1002 Conference Room Square Footage appears before 1003 Collaboration Space Square Footage. And that account appears before 1004 Development Staff. | [optional] 
**reconcile_with_matching** | **bool** | Check this box if you want to use the Match Bank Data and Reconcile Account Statement pages for this account. The original reconciliation pages are no longer supported but are still available. To use the original pages, clear the box. | [optional] 
**full_name** | **str** | Returns the name of the account, but does not include the account number. | [optional] 
**acct_name** | **str** | Enter up to 31 characters for an account name that will appear on all reports. If you want to use GL account numbers and do not see a Number field above the Name field, go to Setup &amp;gt; Accounting &amp;gt; Preferences &amp;gt; Accounting Preferences, and check the Use Account Numbers box. Save the preference, and return to this page. | [optional] 
**ref_name** | **str** |  | [optional] 
**links** | [**List[NsLink]**](NsLink.md) |  | [optional] [readonly] 
**subsidiary** | [**NsResourceCollection**](NsResourceCollection.md) |  | [optional] 
**deferral_acct** | [**Account**](Account.md) |  | [optional] 
**location** | [**NsResource**](NsResource.md) |  | [optional] 
**billable_expenses_acct** | [**Account**](Account.md) |  | [optional] 
**department** | [**NsResource**](NsResource.md) |  | [optional] 
**units_type** | [**NsResource**](NsResource.md) |  | [optional] 
**currency** | [**Currency**](Currency.md) |  | [optional] 
**var_class** | [**NsResource**](NsResource.md) |  | [optional] 
**account_context_search** | [**AccountAccountContextSearchCollection**](AccountAccountContextSearchCollection.md) |  | [optional] 
**localizations** | [**AccountLocalizationsCollection**](AccountLocalizationsCollection.md) |  | [optional] 
**category1099_misc** | [**NsResource**](NsResource.md) |  | [optional] 
**parent** | [**Account**](Account.md) |  | [optional] 

## Example

```python
from pynetsuite.models.account import Account

# TODO update the JSON string below
json = "{}"
# create an instance of Account from a JSON string
account_instance = Account.from_json(json)
# print the JSON string representation of the object
print(Account.to_json())

# convert the object into a dict
account_dict = account_instance.to_dict()
# create an instance of Account from a dict
account_from_dict = Account.from_dict(account_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


