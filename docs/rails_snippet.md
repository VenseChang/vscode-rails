# Rails Snippet v0.4.0

|Prefix|shortcut||
|---|---|---|
|pre||<%  %>|
|preb||<%  %><br><br><% end %>|
|pre-||<%=  %>|
|preb-||<%=  %><br><br><% end %>|
|each||<% @variable.each do \|variable\| %><br><br><% end %>|
|form_for||<%= form_for variable do \|f\| %><br><br><% end %>|
|simple_form_for||<%= simple_form_for variable do \|f\| %><br><br><% end %>|
|time_zone_select||<%= f.time_zone_select :id_name %>|
|range_field||<%= range_field (:model_name, :id_name, in: 1..100) %>|
|select_tag||<%= select_tag (:id_name, options_for_select(options)) %>|
|options_for_select||options_for_select([options])|
|color_field||<%= color_field :id_name %>|
|render||<%= render  \"path\" %>|
|render_variable||<%= render  "path", variable: variable %>|
|link_to||<%= link_to  \"text\", path %>|
|link_to_class|litoc|<%= link_to  "text", path, class:"class" %>|
|link_to_method_data|ltmd|<%= link_to "link_text", path, method: "method", data:{ data } %>|
|link_to_method_data|ltmdc|<%= link_to "link_text", path, method: "method", data:{ data }, class:"class" %>|
|link_to_method_confirm|ltmdc|<%= link_to "link_text", path, method: "method", data:{ confirm: "confirm" } %>|
|link_to_method_confirm_class|ltmdcc|<%= link_to "link_text", path, method: "method", data:{ confirm: "confirm" }, class:"class" %>|
|f.number_field||<%= f.number_field (:id_name, in: 1.0..20.0, step: 0.5) %>|
|f.time_field||<%= f.time_field :id_name %>|
|f.hidden_field||<%= f.hidden_field :id_name %>|
|f.email_field||<%= f.email_field :id_name %>|
|f.url_field||<%= f.url_field :id_name %>|
|f.password_field||<%= f.password_field :id_name %>|
|f.text_area||<%= f.text_area :id_name %>|
|f.check_box||<%= f.check_box :id_name %>|
|f.text_field||<%= f.text_field :id_name %>|
|f.radio_button||<%= f.radio_button :name, :value => \"value\" %>|
|f.label||<%= f.label :id_name, "text" %>|
|f.input||<%= f.input :id, label: "text" %>|
|f.submit||<%= f.submit %>|
|path||{path}_path|
|new_path||new_{path}_path|
|edit_path||edit_{path}_path|
|f.date||<%= f.date_field :id_name %>|
|f.datetime||<%= f.datetime_field :id_name %>|
|2018-1-5|||
|if||<% if $1 %><br>&nbsp;&nbsp;$2<br><% end %>|
|if else||<% if $1 %><br>&nbsp;&nbsp;$2<br><% else %><br>&nbsp;&nbsp;$3<br><% end %>|
|if elsif||<% if $1 %><br>&nbsp;&nbsp;$2<br><% elsif $3 %><br>&nbsp;&nbsp;$4<br><% end %>|
|if elsif else||<% if $1 %><br>&nbsp;&nbsp;$2<br><% elsif $3 %><br>&nbsp;&nbsp;$4<br><% else %><br>&nbsp;&nbsp;$5<br><% end %>|
|***Feature***|||
