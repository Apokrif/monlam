# monlam
Modeling as Service
#Connect:Accounting, AuthorizationMethods 
-[Verb]:Session o-- Context -> DiagramsList
-Search:Repository.GetElementsByQuery
-Notify
-Empty

Search delegatesTo
Repository.GetElementsByQuery
(string QueryName, string SearchTerm)
Collection (of type Element)
Notes: run a search in Enterprise Architect, returning the result as a collection.

Parameters:
· QueryName: String - the name of the search to run, for example 'Simple'
· SearchTerm: String - the term to search for

Example: 
GetElementsByQuery('Simple','TextToFind'), 
where the results list elements with 'TextToFind' in the 'Name' and 'Notes' fields.

