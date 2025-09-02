| Server Name | Tool Name | Tool Description | Endpoint |
|-------------|-----------|------------------|----------|
| data-cloud-queries | get_dc_metadata | Query the metadata API to lists all entities in the dataspace. | /ssot/metadata |
| data-cloud-queries | post_dc_query_sql | Execute a Data Cloud SQL query, returning the first chunk of data and metadata | /ssot/query-sql |
| insurance-cloud | add_eligible_product_clauses | add eligible product clauses | /connect/insurance/product-clauses/add-eligible-product-clauses |
| insurance-cloud | bulk_create_product_clauses | create product clauses in bulk | /connect/insurance/product-clauses/bulk |
| insurance-cloud | bulk_create_product_surcharges | create product surcharges in bulk | /connect/insurance/product-surcharges/bulk |
| insurance-cloud | calculate_product_surcharge_tax | calculate tax on a quote or a context | /connect/insurance/product-surcharges/tax-calculation |
| insurance-cloud | create_underwriting_rules | create underwriting rules | /connect/insurance/underwriting-rules |
| insurance-cloud | describe_global | Describe Global (List all sObjects) | /sobjects |
| insurance-cloud | describe_sobject | Describe sObject | /sobjects/{sobject-name}/describe |
| insurance-cloud | find | Execute a SOSL search | /search |
| insurance-cloud | get_eligible_clauses | get eligible clauses | /connect/insurance/product-clauses/eligible-product-clauses |
| insurance-cloud | get_insurance_policy_details | Comprehensive Policy Information Retrieval - Retrieves complete insurance policy information including coverage details, participants, billing history, and transaction records | /connect/insurance/policies/{policyId} |
| insurance-cloud | get_insurance_quote_details | Comprehensive Quote Information Retrieval - Retrieves complete insurance quote information including rating details, coverage specifications, participant information, and documentation | /connect/insurance/quotes/{quoteId} |
| insurance-cloud | invoke_underwriting_rules | invoke underwriting rules | /connect/insurance/underwriting-rules/invoke |
| insurance-cloud | soql_query | Execute SOQL Query | /query |
| insurance-cloud | underwriting_rule_group_update_status | Updates the status of the ruleset backing the specified Underwriting Rule Group | /connect/insurance/underwriting-rule-group-status/{uwrGroupId} |
| insurance-cloud | update_product_clause | update a product clause | /connect/insurance/product-clauses/{productClauseId} |
| insurance-cloud | update_product_surcharge | update a product surcharge | /connect/insurance/product-surcharges/{productSurchargeId} |
| insurance-cloud | update_underwriting_rule | update an underwriting rule | /connect/insurance/underwriting-rules/{underwritingRuleId} |
| invocable_actions | get_invocable_action_schema | Gets the input and output schema for a specific invocable action. | /invocableactions/{id} |
| invocable_actions | get_invocable_actions | Invocable Actions are tools/functions that abstract many functionalities. Use this tool to explore what actions might be present in your salesforce org. Gets all invocable actions, each returned item contains id and label. The returned Id should be used as is when subsequent tools such as invoke_invocable_action and get_invocable_action_schema are used. When you don't find a mcp tool to achieve something, use this tool to dynamically discover additional capabilities. | /invocableactions |
| invocable_actions | invoke_invocable_action | Invokes the specified invocable action with the provided input and returns the output. | /invocableactions/{id}/invocations |
| pricing-ngp | get_price | Perform pricing using input data mapped to a pricing context and procedure. | /connect/core-pricing/pricing |
| revenue-cloud | add-nodes | Resource for the Add Nodes Configurator API | /connect/cpq/configurator/actions/add-nodes |
| revenue-cloud | amend | Resource for the Amend Asset API | /connect/revenue-management/assets/actions/amend |
| revenue-cloud | cancel | Resource for the Cancel Asset API | /connect/revenue-management/assets/actions/cancel |
| revenue-cloud | create_or_update_asset_from_order | Create or Update Assets from Order | /actions/standard/createOrUpdateAssetFromOrder |
| revenue-cloud | create_order_from_quote | API for creating an Order from Quote | /actions/standard/createOrderFromQuote |
| revenue-cloud | delete-nodes | Resource for the Delete Nodes Configurator API | /connect/cpq/configurator/actions/delete-nodes |
| revenue-cloud | describe_global | Describe Global (List all sObjects) | /sobjects |
| revenue-cloud | describe_sobject | Describe sObject | /sobjects/{sobject-name}/describe |
| revenue-cloud | find | Execute a SOSL search | /search |
| revenue-cloud | load-instance | Resource for the Load Configuration Instance API | /connect/cpq/configurator/actions/load-instance |
| revenue-cloud | place_sales_transaction | Create or Update RLM Quote Or Order | /connect/rev/sales-transaction/actions/place |
| revenue-cloud | renew | Resource for the Renew Asset API | /connect/revenue-management/assets/actions/renew |
| revenue-cloud | soql_query | Execute SOQL Query | /query |
| revenue-cloud | update-nodes | Resource for the Update Nodes Configurator API | /connect/cpq/configurator/actions/update-nodes |
| setup-apis-context | get_metadata_type_context | Provides contextual information about Salesforce metadata types to help generate accurate Salesforce metadata files. This tool gives you complete field definitions, valid values, constraints, and examples for metadata types. It is a useful resource for creating valid Salesforce metadata files when you need to generate them programmatically, or want to ensure accuracy. | /metadatamcp/{metadataTypeName} |
| sobject-all | create_sobject_record | Create a record for sObject | /sobjects/{sobject-name} |
| sobject-all | delete_related_record | Delete a related record via relationship traversal | /sobjects/{sobject-name}/{id}/{relationship-path} |
| sobject-all | delete_sobject_record | Delete a record for sObject | /sobjects/{sobject-name}/{id} |
| sobject-all | describe_global | Describe Global (List all sObjects) | /sobjects |
| sobject-all | describe_sobject | Describe sObject | /sobjects/{sobject-name}/describe |
| sobject-all | find | Execute a SOSL search | /search |
| sobject-all | get_related_records | Retrieve related records via relationship traversal (multi-level) | /sobjects/{sobject-name}/{id}/{relationship-path} |
| sobject-all | get_user_info | Get User Info | /chatter/users/me |
| sobject-all | list_recent_sobject_records | List records for sObject | /sobjects/{sobject-name} |
| sobject-all | soql_query | Execute SOQL Query | /query |
| sobject-all | update_related_record | Update a related record via relationship traversal | /sobjects/{sobject-name}/{id}/{relationship-path} |
| sobject-all | update_sobject_record | Update a record for sObject | /sobjects/{sobject-name}/{id} |
| sobject-deletes | delete_related_record | Delete a related record via relationship traversal | /sobjects/{sobject-name}/{id}/{relationship-path} |
| sobject-deletes | delete_sobject_record | Delete a record for sObject | /sobjects/{sobject-name}/{id} |
| sobject-deletes | describe_global | Describe Global (List all sObjects) | /sobjects |
| sobject-deletes | describe_sobject | Describe sObject | /sobjects/{sobject-name}/describe |
| sobject-deletes | find | Execute a SOSL search | /search |
| sobject-deletes | soql_query | Execute SOQL Query | /query |
| sobject-mutations | create_sobject_record | Create a record for sObject | /sobjects/{sobject-name} |
| sobject-mutations | describe_global | Describe Global (List all sObjects) | /sobjects |
| sobject-mutations | describe_sobject | Describe sObject | /sobjects/{sobject-name}/describe |
| sobject-mutations | find | Execute a SOSL search | /search |
| sobject-mutations | soql_query | Execute SOQL Query | /query |
| sobject-mutations | update_related_record | Update a related record via relationship traversal | /sobjects/{sobject-name}/{id}/{relationship-path} |
| sobject-mutations | update_sobject_record | Update a record for sObject | /sobjects/{sobject-name}/{id} |
| sobject-reads | describe_global | Describe Global (List all sObjects) | /sobjects |
| sobject-reads | describe_sobject | Describe sObject | /sobjects/{sobject-name}/describe |
| sobject-reads | find | Execute a SOSL search | /search |
| sobject-reads | get_related_records | Retrieve related records via relationship traversal (multi-level) | /sobjects/{sobject-name}/{id}/{relationship-path} |
| sobject-reads | get_user_info | Get User Info | /chatter/users/me |
| sobject-reads | list_recent_sobject_records | List records for sObject | /sobjects/{sobject-name} |
| sobject-reads | soql_query | Execute SOQL Query | /query |
