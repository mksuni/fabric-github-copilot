# Microsoft Fabric Development Prompts

## Quick Start Prompts

### Create New User Data Function

```
Create a new User Data Function named {function_name} that {description}. Include:
- Proper definition.json with schema validation
- Python function implementation with error handling
- Requirements.txt with necessary dependencies
- Local settings template
```

### Generate Semantic Model

```
Generate a Semantic Model named {model_name} for {data_source}. Include:
- Proper PBISM definition file
- TMDL database and model definitions
- Appropriate relationships and measures
- Documentation for business users
```

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
Generate a Python Azure Function for Microsoft Fabric that:
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

## Advanced Development Prompts

### Performance Optimization

```
Optimize this Fabric {item_type} for performance:
{paste_code_here}

Focus on:
- Resource utilization
- Query optimization
- Memory management
- Scalability considerations
Provide specific recommendations with code examples
```

### Security Review

```
Perform a security review of this Fabric implementation:
{paste_code_here}

Evaluate:
- Authentication patterns
- Data access controls
- Secret management
- Network security
- Compliance requirements
```

### Migration Planning

```
Create a migration plan from {source_system} to Microsoft Fabric:
- Current architecture: {description}
- Target capabilities: {requirements}
- Data volume: {size}
- Performance requirements: {sla}

Include:
- Step-by-step migration approach
- Risk mitigation strategies
- Testing procedures
- Rollback plans
```

## Integration Prompts

### CI/CD Pipeline

```
Create a GitHub Actions workflow for Fabric deployment:
- Source: {source_path}
- Target workspace: {workspace}
- Items to deploy: {item_types}
- Environment: {dev/test/prod}

Include:
- Authentication setup
- Testing stages
- Approval processes
- Environment-specific configurations
```

### API Integration

```
Create Fabric integration with external API:
- API endpoint: {endpoint}
- Authentication: {auth_type}
- Data transformation: {requirements}
- Error handling: {strategy}
- Scheduling: {frequency}

Implement as {item_type} with proper error handling
```

## Documentation Prompts

### Technical Documentation

```
Create technical documentation for Fabric {item_type}:
- Architecture overview
- Implementation details
- Configuration options
- Troubleshooting guide
- Usage examples
Include diagrams where helpful
```

### User Guide

```
Create end-user guide for Fabric solution:
- Business purpose: {description}
- Target audience: {users}
- Key features: {features}
- Step-by-step usage instructions
- FAQ section
Use non-technical language
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
