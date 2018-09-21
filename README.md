# monlam
Modeling as Service
-Connect:Accounting, AuthorizationMethods 
-[Verb]:Session o-- Context -> DiagramsList
-Search:Repository.GetElementsByQuery
-Notify
-Empty

Repository.GetElementsByQuery
(string QueryName, string
SearchTerm)
Collection (of type Element)
Notes: Helps you to run a search in Enterprise Architect, returning the result as a
collection.

For example: GetElementsByQuery('Simple','Class1'), where the results list
elements with 'Class1' in the 'Name' and 'Notes' fields.
Parameters:
· QueryName: String - the name of the search to run, for example 'Simple'
· SearchTerm: String - the term to search for