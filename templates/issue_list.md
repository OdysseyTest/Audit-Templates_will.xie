| Chapter | Issue Title  | Issue Status | Severity |
| ------------- | ------------- | ------------- | ------------- |
<% issues_ordered_with_links.each_with_index do |issue,index| %> | 3.<%= index+1 %> | [<%= issue["title"] %>](<%= issue["link"] %>) | <img height="30px" src="static-content/<%= issue["state"].to_s.downcase %>.png"/>| <img height="30px" src="static-content/<%=issue["severity"].to_s.downcase %>.png"/> | 
<% end %>
