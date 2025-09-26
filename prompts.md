# Microsoft Fabric Development Prompts

## Quick Start Prompts

### Fabric CLI Workflow

```
Provide step-by-step Fabric CLI commands to:
1. Navigate to workspace {workspace_name}
2. Create item {item_name} of type {item_type}
3. Upload local files
4. Verify deployment
Use proper fab:/ prompt format
```

## Code Generation Prompts

### Python Function Template

```
Generate a Python Fabric User data function for Microsoft Fabric that:
- Accepts HTTP requests with JSON payload
- Validates input parameters: {parameters}
- Implements business logic for: {functionality}
- Returns structured JSON response
- Includes comprehensive error handling
- Follows Fabric User Data Function patterns
```

### SQL Database Schema

```
Create SQL Database schema for {business_domain} including:
- Tables with proper constraints and indexes
- Views for common queries
- Stored procedures for business operations
- User-defined types where appropriate
- Security schema definitions
- Follow Fabric SQL Database project structure
```

### Notebook Development

```
Create a Fabric Notebook that:
- Connects to {data_source}
- Performs {analysis_type} analysis
- Uses proper Fabric SDK patterns
- Includes data visualization
- Documents methodology and assumptions
- Handles authentication securely
```

## Troubleshooting Prompts

### Debug Authentication Issues

```
Help me troubleshoot Fabric authentication issues:
- Current error: {error_message}
- Authentication method: {auth_method}
- Target resource: {resource}
Provide step-by-step resolution with fab CLI commands
```

### Validate Item Definitions

```
Review and validate this Fabric item definition:
{paste_definition_here}

Check for:
- Schema compliance
- Best practices
- Security considerations
- Performance implications
Suggest improvements with explanations
```

### Deployment Troubleshooting

```
My Fabric item deployment failed with: {error_message}
- Item type: {item_type}
- Target workspace: {workspace}
- Deployment method: {method}
Analyze the issue and provide resolution steps
```

## Template Variables

Use these variables in prompts:

- `{workspace_name}` - Target workspace
- `{item_name}` - Fabric item name
- `{item_type}` - UserDataFunction, SemanticModel, etc.
- `{function_name}` - Function identifier
- `{description}` - Functional description
- `{data_source}` - Source system or dataset
- `{parameters}` - Function parameters
- `{functionality}` - Business logic description
- `{error_message}` - Specific error text
- `{auth_method}` - Authentication approach
- `{business_domain}` - Business context

## Usage Guidelines

1. **Copy and customize** prompts for specific needs
2. **Fill in variables** with actual values
3. **Combine prompts** for complex scenarios
4. **Iterate and refine** based on results
5. **Share successful prompts** with team

---

_Use these prompts with the Fabric Developer Chatmode for optimal results_
