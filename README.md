# Web Cache

## Intelligent caching

Web applications such as Salesforce have lots of Javascript and Cascading Style Sheets in order to provide a rich user experience that is comparable to what people experience with a desktop application. As a result, you’re going to have 3, 4 or 5MB javascript files that can take time to download, especially when you have packet loss. This one specific page with multiple plugins used by our Sales team has a total page size of 5 MB. Since it rarely changes, if you can enable caching on your network and create a cache derivative of it stored locally, you’ll be enabling larger file downloads and creating a much better experience for your users when loading Salesforce.
