# Public Methods API
> (see [public methods for more information](http://apidocs.mendeley.com/home/public-resources )) 

**Statistics methods (from Mendeley Server)**

 * `authors` -- top authors (overall or by subject, trending)
 * `papers` -- all time top papers (overall or by subject, trending)
 * `publications` -- top journals 
 * `tags` -- most popular tags in week-long periods

**Search methods**

 * `msearch`-- all papers matching the search query
 * `authored` -- all papers with given author 
 * `related` -- related papers
 * `tagged` -- all papers with the tag
 * `Categories` -- a function to look up categories and their reference numbers 
 * `subcategories` - a function to look up subcategories and their reference numbers
 * `Details` -- more details such as authors, publication outlet, year, abstract, PubMed ID if available, etc. Also returns # readers, top 3 discipline stats, top 3 country stats, and top 3 education status stats.


**Public Group methods**

 * `Public groups overview` 
 * `Public groups details`
 * `Public groups documents`
 * `Public groups people`


# User Specific Methods

All user specific methods are currently under development and located in the [dev branch](https://github.com/ropensci/RMendeley/tree/dev).

