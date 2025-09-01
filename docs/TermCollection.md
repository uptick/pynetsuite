# TermCollection


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**total_results** | **int** |  | [optional] [readonly] 
**items** | [**List[Term]**](Term.md) | An array field that represents a collection of elements, for example, sublist lines, multiselect items, or search results. | [optional] 
**links** | [**List[NsLink]**](NsLink.md) |  | [optional] [readonly] 
**count** | **int** |  | [optional] [readonly] 
**has_more** | **bool** |  | [optional] [readonly] 
**offset** | **int** |  | [optional] [readonly] 

## Example

```python
from pynetsuite.models.term_collection import TermCollection

# TODO update the JSON string below
json = "{}"
# create an instance of TermCollection from a JSON string
term_collection_instance = TermCollection.from_json(json)
# print the JSON string representation of the object
print(TermCollection.to_json())

# convert the object into a dict
term_collection_dict = term_collection_instance.to_dict()
# create an instance of TermCollection from a dict
term_collection_from_dict = TermCollection.from_dict(term_collection_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


