
## 2 Issue Overview  

The following table contains all the issues discovered during the audit. The issues are ordered based on their severity. More detailed description on the  levels of severity can be found in Appendix 2. The table also contains the Github status of any discovered issue.

| Chapter | Issue Title  | Issue Status | Severity |
| ------------- | ------------- | ------------- | ------------- |
<% issues_ordered_with_links.each_with_index do |issue,index| %> | 3.<%= index+1 %> | <%= issue["title"] %> | **<%= issue["state"].to_s %>** | **<%=issue["severity"].to_s %>** | 
<% end %>



## 3 Issue Detail  


<%= issues_markdown %>
